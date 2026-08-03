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

## Variable exports

Note: `MY_ENV_VAR` is only set in the context of `script.sh` (i.e. it won't be 
set in the shell that called `script.sh` once the script finishes running)

`script.sh`:
```
export MY_ENV_VAR=5
./bin/test_script_2.sh 
```
or 

`script.sh`:
```
MY_ENV_VAR=5
export MY_ENV_VAR
./bin/test_script_2.sh 
```
or 

`script.sh`:
```
MY_ENV_VAR=5 ./bin/test_script_2.sh 
```

test_script_2:
```
echo $MY_ENV_VAR
```
