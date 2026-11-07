# so_long

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![MiniLibX](https://img.shields.io/badge/MiniLibX-555555?style=flat-square) ![42 Roma Luiss](https://img.shields.io/badge/42_Roma_Luiss-000000?style=flat-square&logo=42&logoColor=white)

A small 2D top-down game made with MiniLibX. Collect all the coins and reach the exit, and stay away from the enemy.

## Features

- Maps loaded from `.ber` files, checked to be rectangular and closed by walls, with one player, one exit and at least one coin
- Animated coin sprites and an enemy
- Move counter shown in the window
- `W A S D` to move, `ESC` or the window's close button to quit

## Build & run

```bash
make
./so_long maps/map_ok.ber
```

Map characters: `1` wall · `0` floor · `P` player · `C` coin · `E` exit

---

<sub>Part of my 42 Roma Luiss curriculum · [more projects](https://github.com/Fbiondo00) · MIT License</sub>
