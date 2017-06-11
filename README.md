# ts-sourcemap

Check TypeScript sourcemaps are being generated correctly.


## Install and build

```
$ cd ts
$ npm install
$ npm run build
```

Then check the `build/TestEmitter.js` and `build/TestEmitter.js.map` sourcemap in the visualizer: http://sokra.github.io/source-map-visualization/



For comparison there is a js version that compiles with Babel:

```
$ cd js
$ npm install
$ npm run build
```