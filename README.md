# Rental APP

## Installation

```bash
$ npm install
```

## Set ENV variables

```
TYPEORM_CONNECTION=
TYPEORM_HOST=
TYPEORM_USERNAME=
TYPEORM_PASSWORD=
TYPEORM_DATABASE=
TYPEORM_PORT=
TYPEORM_SYNCHRONIZE=
TYPEORM_LOGGING=
TYPEORM_ENTITIES=
TYPEORM_MIGRATIONS=
TYPEORM_SEEDING_SEEDS=
TYPEORM_SEEDING_FACTORIES=
TYPEORM_SUBSCRIBERS=
TYPEORM_ENTITIES_DIR=
TYPEORM_MIGRATIONS_DIR=
TYPEORM_MIGRATIONS_RUN=

MAILER_HOST=
MAILER_PORT=
MAILER_USER=
MAILER_PASSWORD=

AWS_ACCESS_KEY_ID=
AWS_ACCESS_KEY_SECRET=
AWS_BUCKET=

JWT_SECRET=
JWT_EXPIRATION_TIME=
```

## Running Migrations and Database Seeding

First, you should create the schema on your postgres, then run the following commands

```
$ npm run migration:run

$ npm run migration:seed
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
