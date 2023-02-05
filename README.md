# config-tmux

Personal configuration of tmux

## Clone this repository

```
git clone https://github.com/VV0JC13CH/config-tmux ~/.config/tmux
```
## Keybindings

### tmux-sessionist

- `prefix + g` - prompts for session name and switches to it. Performs 'kind-of'
  name completion.<br/>
  Faster than the built-in `prefix + s` prompt for long session lists.
- `prefix + C` (shift + c) - prompt for creating a new session by name.
- `prefix + X` (shift + x) - kill current session without detaching tmux.
- `prefix + S` (shift + s) - switches to the last session.<br/>
  The same as built-in `prefix + L` that everyone seems to override with
  some other binding.
- `prefix + @` - promote current pane into a new session.<br/>
  Analogous to how `prefix + !` breaks current pane to a new window.
- `prefix + t<secondary-key>` - join currently marked pane (`prefix + m`) to current session/window, and switch to it
  - secondary-keys
    - `h`, `-`, `"`: join horizontally
    - `v`, `|`, `%`: join vertically
    - `f`, `@`: join full screen

### tmux-urlview
- `prefix + u` - listing all urls on bottom pane

### tmux-cowboy
- `prefix + *` - kill process running in current pane

### tmux-open
- `o` - "open" a highlighted selection with the system default program. `open`
    for OS X or `xdg-open` for Linux.
- `Ctrl-o` - open a highlighted selection with the `$EDITOR`

### ranger-tmux
- `prefix + r` - toggle ranger pane on/off

### laktak/extrakto
- `prefix + tab` - fzf finder for pane content
