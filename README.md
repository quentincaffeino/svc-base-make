# Base repo for services with make

Make setup which makes use of per-environment dotenv files

## Table of contents

- [Base repo for services with make](#base-repo-for-services-with-make)
	- [Usage](#usage)
	- [dotenv](#dotenv)
		- [Overrides](#overrides)

## Usage

```sh
make help
```

## dotenv

Using `make` and per-environment dotenv files it is prepaired to run on several environments.

### Overrides

To override variables locally create `.env.local` or `.env.ENVIRONMENT-NAME.local` (eg.: `.env.prod.local`) files.
