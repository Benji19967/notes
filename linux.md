### Symlink

- ln -s source_file(s) dir_name_where_to_link
`cd && ln -s .../dotfiles/.z* .`


### Disk usage

#### Display disk usage statistics (`man du`)
`du -sh`

#### Display free disk space (`man df`)
`df -h`

### Timing CLI comands
`hyperfine '<command>'`. Example: `hyperfine 'du -sh file.txt'`

### fzf: https://thevaluable.dev/fzf-shell-integration/

`Ctrl+r`: search history
`Ctrl+t`: find all files and subdirectories and output selection to STDOUT
`Alt+c`: find all subdirectories and `cd` into selected one
`fzf --preview="head -$LINES {}"`: find files with file preview!

### CPU Architecture

- `uname -a` will give you your CPU Architecture
  - aarch64 / arm64 --> 
  - x86_64 / amd64  --> 64 bit Intel / AMD CPUs

### `locate`

Searches pathnames in a Database based on a pattern. (`man locate`)

Database may be out-of-date. It is updated daily or weekly.
For real-time searches use `find`.

`locate <filename>`

### Print directory structure

- `tree -d . -L 3`: prints the directories of the current directory up to a depth of 3

### Reading `.h5` files (HDF)

- `sudo apt install hdf5-tools` (Ubuntu)
- `h5dump <path_to_h5_file`

### Creating directories with incrementing ids

`mkdir exercise_{01..15}`
