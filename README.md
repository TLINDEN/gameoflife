# Conway's game of life

I wanted to play around a little bit with GOL in golang and here's the
result. It's a simple game using
[ebitengine](https://github.com/hajimehoshi/ebiten/).

# Build and install

Just execute: `go build .` and use the resulting executable.

You'll need the golang toolchain.

# Usage

The game has a couple of commandline options:

```default

Usage of ./gameoflife:
  -c, --cellsize int     cell size in pixels (default 8)
  -d, --debug            show debug info
  -D, --density int      density of random cells (default 10)
  -e, --empty            start with an empty screen
  -H, --height int       grid height in cells (default 40)
  -i, --invert           invert colors (dead cell: black)
  -r, --rule string      game rule (default "B3/S23")
  -s, --show-evolution   show evolution tracks
  -t, --tps int          game speed in ticks per second (default 60)
  -v, --version          show version
  -W, --width int        grid width in cells (default 40)
```

While it runs, there are a couple of commands you can use:

* left mouse click: set a cell to alife
* right mouse click: set a cell to dead
* space: pause or resume the game
* q: quit
* up arrow: speed up
* down arrow: slow down
* page up: speed up more
* page down: slow down more

# Report bugs

[Please open an issue](https://github.com/TLINDEN/gameoflife/issues). Thanks!

# License

This work is licensed under the terms of the General Public Licens
version 3.

# Author

Copyleft (c) 2024 Thomas von Dein
