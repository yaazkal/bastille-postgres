# bastille-postgres
[Bastille](https://github.com/bastillebsd/bastille) template for running PostgreSQL server in a FreeBSD jail

By default it installs the recent version of PostgreSQL (13) avilable in ports. You can use `ARG` option to choose a different version.

## Bootstrap

```shell
bastille bootstrap https://github.com/yaazkal/bastille-postgres
```

## Usage

```shell
bastille template TARGET yaazkal/bastille-postgres
```
