# TMUX

## To try out 

- `display-popup`
  - https://www.reddit.com/r/unixporn/comments/18yqmgk/tmux_always_feared_tmux_finally_managed_to/

## Key Bindings

https://github.com/tmux/tmux/wiki/Getting-Started#key-bindings

### Key tables

There are four key tables:

- `root`
- `prefix`
- `copy-mode`
- `copy-mode-vi`

### Listing keybindings

Use `list-key` / `lsk`:

- `tmux lsk -T prefix`
- `tmux lsk -T prefix -N`

Some options:

- `-T <key table to use>`
- `-n` is an alias for `-T root`

### `bind` vs `bind-key`

https://superuser.com/questions/581939/on-tmux-what-is-the-difference-between-bind-and-bind-key

They are the same: `bind` is an alias for `bind-key`

