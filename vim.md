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

## Global `:g`
- Duplicate lines matching a pattern
`:g/pattern/copy .`
- Indent all lines matching a pattern
`:g/pattern/>`
- Add new line after all lines matchin a pattern
and insert text on that line
`:g/pattern|copy .|s/.*/text to insert`
- Indent lines containing multiple patterns 
`:g/patter1\|pattern2/>`

## How to 

- Check keymaps.lua

### Move block of lines
- Go into visual block mode (Ctrl + v) or visual line (Shift + v)
- j/k to select lines
- Shift + j/k: move selected lines up/down

### Comment out line or block of lines
- line: `gcc` or `Ctrl + /`
- multi-line: `gc` or `Ctrl + /`

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

## search and replace
 - `:s/hello/world/g`: replace all instances of `hello` with `world` on current line
 - `:%s/hello/world`: replace all instances of `hello` with `world`

 ## record a macro and replay it
- `q<where to store the macro>`, example `qj`
- `@<where the macro was stored>`, example `@j`
