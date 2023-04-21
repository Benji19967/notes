# Navigation

- Go to last opened file

`Ctrl-^`

## NVIM setup

`:checkhealth`

## NVIM LSP

- `:LspInstallInfo`
- `:LspInstall python`
- `:LspInfo` 
  - to show currently active LSP for file

- Go to line with error:
`gl`
- Hover over code piece and get info on in
`Shift+K`

- Duplicate lines matching a pattern
`:g/pattern/copy .`
- Indent all lines matching a pattern
`:g/pattern/>`
- Add new line after all lines matchin a pattern
and insert text on that line
`:g/pattern|copy .|s/.*/text to insert`

## NVIM comments
- gcc -> one line comment
- select visual + gc -> comment block

## How to 

- Check keymaps.lua

## NVIM packages repo locations:
- "~/.local/share/nvim/site/pack/packer/start/"

## Preview Markdow
```bash 
:Glow
```

## NVIM error messages
- `:messages`

## NVIM Markdown Preview in browsers
- `:MarkdownPreview`
