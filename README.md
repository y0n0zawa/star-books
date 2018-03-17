# Star Books [![CircleCI](https://circleci.com/gh/y0n0zawa/star-books.svg?style=svg)](https://circleci.com/gh/y0n0zawa/star-books)

## Requirements

* Docker 17.12+ (Compose 1.18+)

## Start development

### Clone git repository.

```
$ git@github.com:y0n0zawa/star-books.git
```

### Setup database and migration

```
$ docker-compose run app bundle exec rails db:setup
$ docker-compose run app bundle exec rails db:migration
```

### Install yarn package

```
$ docker-compose run app bundle exec rails yarn install
```
