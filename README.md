[![Release](https://jitpack.io/v/rollo-team/rsm-testcontainers.svg)](https://jitpack.io/rollo-team/rsm-testcontainers)


This is simple project for configuring Testcontainers with using custom database (https://habr.com/ru/post/328226/)

We are applying an approach to apply database migrations inside a container and use it for tests and jooq generators.

`hub.image.name.prefix=ghcr.io/rollo-team/rsm-` allows us to use `rsm-postgres` repository with default configuration for `org.testcontainers.jdbc.ContainerDatabaseDriver` - `jdbc:tc:postgresql:latest:///rollo`

`ryuk.container.image=ryuk:0.3.3` - fix repository url to use with Github Container Repository
