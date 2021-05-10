# bastille-postgres
[Bastille](https://github.com/bastillebsd/bastille) template for running PostgreSQL server in a FreeBSD jail

By default it installs the recent version of PostgreSQL (13) avilable in ports. You can use `ARG` option to choose a different version while applying the template (see usage).

## Bootstrap

```shell
bastille bootstrap https://github.com/yaazkal/bastille-postgres
```

## Usage

Install latest version of postgresql-server

```shell
bastille template TARGET yaazkal/bastille-postgres
```

Install a specific version (i.e 11) of postgresql-server

```shell
bastille template TARGET yaazkal/bastille-postgres --arg version=11
```
