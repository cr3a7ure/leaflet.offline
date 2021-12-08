# leaflet.offline version 2.x

[![npm version](https://badge.fury.io/js/leaflet.offline.svg)](https://badge.fury.io/js/leaflet.offline)
[![Build Status](https://travis-ci.org/allartk/leaflet.offline.png?branch=master)](https://travis-ci.org/allartk/leaflet.offline)

Just a modern and slim library to store tiles offline.

- [example](http://allartk.github.io/leaflet.offline/)
- [api docs](docs/api.md)

## Dependencies

- [Leafletjs](http://leafletjs.com/)
- [idb](https://www.npmjs.com/package/idb) To store the tiles with promises

## Install

### With npm

The package and it's dependencies can also be downloaded into
your existing project with [npm](http://npmjs.com):

```
npm install leaflet.offline
```

In your script add:

```
import 'leaflet.offline'
```

### Manual

Unpack the file for the release (find them under the releasestab ) and add dist/bundle.js in a script tag
to your page (after leaflet and idb).

### Development

For running the example locally, you'll need to clone the project and run:

```
npm i && npm run build
cd docs
npm install && npm run serve
```

You can test your code with `npm test`. Please configure eslint in your editor if you wish to contribute.

**pull requests welcome**

Please one feature at a time, if you can split your PR, please do so.

Also, do not mix a feature with package updates.

## Api

Generate docs with

```
npm run-script docs
```
