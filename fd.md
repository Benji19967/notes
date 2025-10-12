# fd: modern alternative to find

## Find all directories matching the names `.venv` and `.poetry_venv` and delete them

fd -t d -IH "\.venv|\.poetry_venv" -X rm -rf

Explanation:

- `-t d`: look for directories
- `-I`: include exluded files (files in .gitignore)
- `-H`: include hidden files
- `-X`: execute a command for each of the outputs of the search
