# MineClone2 : Better Inventory

## Improvements

This branch adds two improvements to the game:

### Minecraft-like shift-clicking

Shift-clicking works between inventory and hotbar (instead of inventory and
crafting panel).

### Clean hotbar

All garbage you pick up from the ground is moved to your inventory, not to the
hotbar. The only exception is items you put on hotbar manually.

## Disadvantages

- You can't wear armor on shift-click (because of the primitive listring logic).
- All mods must be adapted to use 2 inventories: "default" instead of "main" and
  "main" as player's hotbar.