<div align="center">
<a href="https://nanite-systems.net/" target="blank">
  <img src="https://nanite-systems.net/images/ns.colored.svg" width="200" alt="Nest Logo" />
</a>

[![version](https://img.shields.io/github/package-json/v/nanite-systems/stream-health?color=blue)](https://github.com/nanite-systems/stream-health)
[![issues](https://img.shields.io/github/issues/nanite-systems/stream-health)](https://github.com/nanite-systems/stream-health/issues)
[![dependecies](https://img.shields.io/librariesio/github/nanite-systems/stream-health)](https://libraries.io/github/nanite-systems/stream-health)
[![license](https://img.shields.io/github/license/nanite-systems/stream-health)](https://github.com/nanite-systems/stream-health/blob/main/LICENSE)

</div>

## Description

Health service that monitors stream degradation.

## Requirements

- NodeJS v16
- [Stream devkit](https://github.com/nanite-systems/stream-devkit/)

## Installation

```bash
# configuration
$ cp .env.example .env

# install dependencies
$ yarn install
```

## Running the service

```bash
# development
$ yarn start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## License

All NS projects are [Apache-2.0 licensed](LICENSE).
