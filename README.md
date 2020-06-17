# sequelize/cli [![npm version](https://badge.fury.io/js/sequelize-cli-mod.svg)](https://npmjs.com/package/sequelize-cli-mod) [![Build Status](https://travis-ci.org/sequelize/cli.svg?branch=master)](https://travis-ci.org/sequelize/cli)

The [Sequelize](https://sequelize.org) Command Line Interface (CLI)

## Table of Contents

-   [Installation](#installation)
-   [Contributing](#contributing)
-   [Documentation](#documentation)

## Installation

Make sure you have [Sequelize](https://sequelize.org) installed. Then install the Sequelize CLI to be used in your project with

```bash
npm install --save-dev sequelize-cli-mod // will install v5
npm install --save-dev sequelize-cli-mod@next // will install v6
```

And then you should be able to run the CLI with

```bash
npx sequelize-mod --help
```

### Usage

```
Sequelize CLI [Node: 10.15.0, CLI: 5.5.0, ORM: 5.11.0]

npx sequelize-mod [command]

Commands:
  sequelize-mod db:migrate                        Run pending migrations
  sequelize-mod db:migrate:schema:timestamps:add  Update migration table to have timestamps
  sequelize-mod db:migrate:status                 List the status of all migrations
  sequelize-mod db:migrate:undo                   Reverts a migration
  sequelize-mod db:migrate:undo:all               Revert all migrations ran
  sequelize-mod db:seed                           Run specified seeder
  sequelize-mod db:seed:undo                      Deletes data from the database
  sequelize-mod db:seed:all                       Run every seeder
  sequelize-mod db:seed:undo:all                  Deletes data from the database
  sequelize-mod db:create                         Create database specified by configuration
  sequelize-mod db:drop                           Drop database specified by configuration
  sequelize-mod init                              Initializes project
  sequelize-mod init:config                       Initializes configuration
  sequelize-mod init:migrations                   Initializes migrations
  sequelize-mod init:models                       Initializes models
  sequelize-mod init:seeders                      Initializes seeders
  sequelize-mod migration:generate                Generates a new migration file       [aliases: migration:create]
  sequelize-mod model:generate                    Generates a model and its migration  [aliases: model:create]
  sequelize-mod seed:generate                     Generates a new seed file            [aliases: seed:create]

Options:
  --version  Show version number                                         [boolean]
  --help     Show help                                                   [boolean]
```

## Contributing

Sequelize CLI is always looking for contributions. You can help us by fixing bugs, reporting bugs or improving documentation.

Please read the [contributing guidelines](CONTRIBUTING.md).

## Documentation

-   [Migrations Documentation](https://sequelize.org/master/manual/migrations.html)
-   [CLI Options](docs/README.md)
-   [Frequently Asked Questions](docs/FAQ.md)
