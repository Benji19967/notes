# Notes on `jq`

## Examples

`man jq`

## List keys

`... | jq 'keys'`

## Gey value of keys `results` in a JSON object

`... | jq .results`

## Index a list

`... | jq '.a_list.[0]`
