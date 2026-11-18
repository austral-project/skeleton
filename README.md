# Austral Skeleton

[![Version](https://img.shields.io/packagist/v/austral/skeleton?label=version)](https://packagist.org/packages/austral/skeleton)
[![CI](https://github.com/austral-project/skeleton/actions/workflows/ci.yml/badge.svg?branch=4.x)](https://github.com/austral-project/skeleton/actions/workflows/ci.yml)
[![PHP](https://img.shields.io/packagist/dependency-v/austral/skeleton/php?version=4.x-dev)](https://packagist.org/packages/austral/skeleton)
[![Symfony](https://img.shields.io/badge/symfony-7.4-black)](https://symfony.com/releases/7.4)
[![License](https://img.shields.io/github/license/austral-project/skeleton)](LICENSE)

Starter project for a new Austral application: back office, website and Docker setup, ready to run.

> **Work in progress.** This skeleton is being built for Austral 4.0 and has not been released yet. It replaces the former [sandbox](https://github.com/austral-project/sandbox) project.

> This project is part of [Austral](https://github.com/austral-project), a modular back office and CMS for Symfony.

## What it will provide

- A Symfony 7.4 application with the Austral bundles installed and configured.
- A back office and a website ready to use, with a first administrator account.
- A Docker setup based on the Austral images ([docker-php](https://github.com/austral-project/docker-php), [docker-nginx](https://github.com/austral-project/docker-nginx)).

## Requirements

- PHP 8.2 or higher and Composer, or Docker
- A database supported by Doctrine (MySQL / MariaDB or PostgreSQL)

## Getting started

```bash
composer create-project austral/skeleton my-project "^4.0"
```

## Documentation

The full documentation will be available at https://austral.dev.

## Contributing

Contributions are welcome: see the [contributing guide](https://github.com/austral-project/.github/blob/master/CONTRIBUTING.md). To report a security issue, follow the [security policy](https://github.com/austral-project/.github/blob/master/SECURITY.md).

## License

MIT, see [LICENSE](LICENSE).

## Credits

Created by [Matthieu Beurel](https://www.mbeurel.com). Sponsored by [Yipikai Studio](https://yipikai.studio).
