# mapboxgl-module

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Github Actions CI][github-actions-ci-src]][github-actions-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

> Mapbox-GL module for Nuxt.js

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add `mapboxgl-module` dependency to your project

```bash
yarn add mapboxgl-module # or npm install mapboxgl-module
```

2. Add `mapboxgl-module` to the `modules` section of `nuxt.config.js`

```js
{
  modules: [
    // Simple usage
    'mapboxgl-module',

    // With options
    ['mapboxgl-module', { /* module options */ }]
  ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Vinayak Kulkarni <inbox.vinayak@gmail.com>

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/mapboxgl-module/latest.svg
[npm-version-href]: https://npmjs.com/package/mapboxgl-module

[npm-downloads-src]: https://img.shields.io/npm/dt/mapboxgl-module.svg
[npm-downloads-href]: https://npmjs.com/package/mapboxgl-module

[github-actions-ci-src]: https://github.com/vinayakkulkarni/mapboxgl-module/workflows/ci/badge.svg
[github-actions-ci-href]: https://github.com/vinayakkulkarni/mapboxgl-module/actions?query=workflow%3Aci

[codecov-src]: https://img.shields.io/codecov/c/github/vinayakkulkarni/mapboxgl-module.svg
[codecov-href]: https://codecov.io/gh/vinayakkulkarni/mapboxgl-module

[license-src]: https://img.shields.io/npm/l/mapboxgl-module.svg
[license-href]: https://npmjs.com/package/mapboxgl-module
