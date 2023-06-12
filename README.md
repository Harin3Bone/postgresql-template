## PostgreSQL

![Docker](https://img.shields.io/badge/Docker-2496ED?&style=flat&logo=docker&logoColor=ffffff)
![Postgres](https://img.shields.io/badge/Postgresql-F7F7F7?&style=flat&logo=postgresql&logoColor=336791)

## Description

Simple template of PostgreSQL with Docker Compose

## Prerequisite

* [Docker](https://docs.docker.com/engine/install/ubuntu/)
* [Docker Compose](https://docs.docker.com/compose/install/)
* [Postgresql](https://hub.docker.com/_/postgres)

## Default Value

Change value in `default.env` file to define your own value

| Variable name             | Default value | Datatype  |               Description |
|:--------------------------|:--------------|:---------:|--------------------------:|
| POSTGRES_VERSION          | 12.5          |  String   | Postgres image version    |
| POSTGRES_PORT             | 5432          |  Integer  | Initial password          |
| POSTGRES_USER             | postgres      |  String   | Default postgres user     |
| POSTGRES_PASSWORD         | postgres      |  String   | Default postgres password |
| POSTGRES_DB               | postgres      |  String   | Initial postgres database |
| POSTGRES_CPU_LIMIT        | 1             |  Integer  | Limit CPU usage           |
| POSTGRES_MEMORY_LIMIT     | 512M          |  String   | Limit Memory usage        |


## Reference

* [PostgreSQL](https://hub.docker.com/_/postgres)

## Contributor

[![Github](https://img.shields.io/badge/Harin3Bone-181717?style=flat&logo=github&logoColor=ffffff)](https://github.com/Harin3Bone)
