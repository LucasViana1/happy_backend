# Happy Back-End

## Inicio

inicializa package.json
`yarn init -y`

inicializa configuração ts
`yarn tsc --init`

## Migrations

cria uma migration
`yarn typeorm migration:create -n migration-name`

executa todas migrations
`yarn typeorm migration:run`

desfaz última migration
`yarn typeorm migration:revert`
