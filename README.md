## st

My personal fork of `st` (simple terminal).

### patches added

- `alpha` & `changealpha` (transparency)
- `xresources-signal-reloading`
- `scrollback-mouse`
- `scrollback-ringbuffer`
- `anysize`

- If you're not using `~/.Xresources` or `pywal`, default colors fall back to **Kanagawa**.

### how to use

Clone, build, install:

```sh
git clone https://github.com/eoSalinas/st
cd st
sudo make install
```

- Keybindings live in `config.h`. Here's a few worth noting:
  - `Alt + [` / `Alt + ]` → Increase & decrease zoom
  - `Alt + k` / `Alt + j` → Scroll up & scroll down
  - `Ctrl + shift + c` / `Ctrl + shift + v` → for copy-paste

