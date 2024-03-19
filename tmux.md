# TMUX


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

`tmux lsk -Tprefix`
`tmux lsk -Tprefix -N`

### `bind` vs `bind-key`

https://superuser.com/questions/581939/on-tmux-what-is-the-difference-between-bind-and-bind-key

They are the same: `bind` is an alias for `bind-key`

