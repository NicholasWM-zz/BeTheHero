Cria arquivo KNEX(Query Builder) que configura o bd
    knew init

    npx knex migrate:make create_ongs

Executa a migration no BD
    npx knex migrate:latest

Defaz ultima migration
    npx knex migrate:rollback

Lista as migrations executadas
    npx knex migrate:status

