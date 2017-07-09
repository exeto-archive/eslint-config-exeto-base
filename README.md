# eslint-config-exeto-base [![Peer Dependency Status][peerdepstat-image]][peerdepstat-url]

> This repository is a fork of [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base)

**THIS PACKAGE IS NO LONGER MAINTAINED**

## Install

```bash
$ npm install --save-dev \
  eslint-config-exeto-base \
  eslint-plugin-import@^1.12.0 \
  eslint@^3.2.0
```

## Usage

Add one of the following in your `.eslintrc`:

- EcmaScript 6+

```json
"extends": "exeto-base"
```

- EcmaScript 6+ and specificity for node

```json
"extends": "exeto-base/node"
```

- EcmaScript 5 and below

```json
"extends": "exeto-base/legacy"
```

## License

[MIT](LICENSE.md) © [Airbnb](https://github.com/airbnb) and [Timofey Dergachev](https://exeto.me/en)

[peerdepstat-url]: https://david-dm.org/exeto-archive/eslint-config-exeto-base?type=peer
[peerdepstat-image]: https://david-dm.org/exeto-archive/eslint-config-exeto-base/peer-status.svg?style=flat-square
