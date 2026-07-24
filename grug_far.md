# Grug Far

Uses ripgrep `rg` under the hood

## Examples
```
Search:
    init_logging\(log_level\)
    service_name = "([A-Z]*)"

Flags:
-U

Matches:
    init_logging(log_level)
    service_name = "TUNE"
...
```
