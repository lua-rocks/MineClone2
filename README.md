# MineClone2 : Better Inventory

## Improvements

This branch adds two improvements to the game:

### Minecraft-like shift-clicking

Shift-clicking works between inventory and hotbar (instead of inventory and
crafting panel).

![player example](https://i.imgur.com/dmVOSHD.gif)

![chest example](https://i.imgur.com/xaCkouQ.gif)

### Clean hotbar

All garbage you pick up from the ground is moved to your inventory, not to the
hotbar. The only exception is items you put on hotbar manually.

![garbage example](https://i.imgur.com/MsmzQrw.gif)

## Disadvantages

- You can't wear armor on shift-click (because of the primitive listring logic).
  - Not sure, but maybe I can fix it...
- All mods must be adapted to use 2 inventories: "default" instead of "main" and
  "main" as player's hotbar.