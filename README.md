# Notes about Sequelize

### Quero criar um banco

```
    $ yarn sequelize db:create
```

### Quero criar uma migration

```
    $ yarn sequelize migration:create --name=migration_name
```

### Quero enviar as alterações nas migrations

```
    $ yarn sequelize db:migrate
```

### Quero remover a última migration para att algo (PRODUÇÃO)

Caso esteja em produção, para att algo, tem que criar outra migration

```
    $ yarn sequelize db:migrate:undo
```
