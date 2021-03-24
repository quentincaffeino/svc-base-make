# Base repo for services with make

## Table of contents

- [Make](#make)
- [dotenv](#dotenv)
  - [Overrides](#overrides)

## Make

```sh
make help
```

## dotenv

Using `make` and per-environment dotenv files it is prepaired to run on several environments.

### Overrides

To override variables locally create `.env.local` or `.env.ENVIRONMENT-NAME.local` (eg.: `.env.prod.local`) files.
