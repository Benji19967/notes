# Notes on `jq`

## Examples

`man jq`

## List keys

`... | jq 'keys'`

## Gey value of keys `results` in a JSON object

`... | jq .results`

## Index a list

`... | jq '.a_list.[0]`

## Index response list (no name)

`... | jq '.[0]'`

## Get keys of the objects in a list

`... | jq '.[0]' | jq 'keys'`

## Select all `id` keys from a list of objects

- https://stackoverflow.com/a/53676048/10288034

`... | jq '..|objects|.id'`

## Get all key paths

`...| jq 'paths | join(".")'`
