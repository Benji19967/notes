# Bash

## Iterate over a set of values

```bash
for i in 5 10 20; do echo $i; done
```

## Iterate over a range of values

```bash
for i in {5..20}; do echo $i; done
```

## Use remaining input args

```
#!/bin/bash

UI_FILENAME=$1
AGEBD_ENV=$2 

echo "${@:3}"
```

