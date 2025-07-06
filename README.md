# Tetris in Command Line!

NES-like _Tetris_ game, playable in terminal. It uses curses - basic module which allows to manipulate content of terminal window.

To start a new game type in terminal:

`python game.py`

<p align="center">
  <img src=preview.gif/>
</p>

```bash
uv sync
source ./venv/bin/activate
uv run game.py
```

On windows:

```bash
uv pip install windows-curses
```

Note: This repo is mirrored from https://github.com/kszczupak/command-line-tetris.