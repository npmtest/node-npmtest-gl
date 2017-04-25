# npmtest-gl

#### basic test coverage for  [gl (v4.0.3)](https://github.com/stackgl/headless-gl#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gl.svg)](https://travis-ci.org/npmtest/node-npmtest-gl)

#### Creates a WebGL context without a window

[![NPM](https://nodei.co/npm/gl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gl/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gl/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gl/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gl/build/test-report.html](https://npmtest.github.io/node-npmtest-gl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikola Lysenko"
    },
    "browser": "browser_index.js",
    "bugs": {
        "url": "https://github.com/stackgl/headless-gl/issues"
    },
    "dependencies": {
        "bindings": "^1.2.1",
        "bit-twiddle": "^1.0.2",
        "glsl-tokenizer": "^2.0.2",
        "nan": "^2.3.3",
        "node-gyp": "^3.3.1",
        "prebuild": "^5.1.2"
    },
    "description": "Creates a WebGL context without a window",
    "devDependencies": {
        "angle-normals": "^1.0.0",
        "bunny": "^1.0.1",
        "faucet": "0.0.1",
        "gl-conformance": "^2.0.9",
        "snazzy": "^3.0.0",
        "standard": "^6.0.8",
        "tape": "^4.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "277f8bd542c84f99fa5bf98821b32d7b27a05627",
        "tarball": "https://registry.npmjs.org/gl/-/gl-4.0.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "fa237d1f4f3d694cd21f9f8c32e47b1420a1221f",
    "gypfile": true,
    "homepage": "https://github.com/stackgl/headless-gl#readme",
    "keywords": [
        "webgl",
        "opengl",
        "gl",
        "headless",
        "server",
        "gpgpu"
    ],
    "license": "BSD",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hughsk"
        },
        {
            "name": "mattdesl"
        },
        {
            "name": "mikkoh"
        },
        {
            "name": "mikolalysenko"
        },
        {
            "name": "mourner"
        },
        {
            "name": "rezaali"
        },
        {
            "name": "springmeyer"
        },
        {
            "name": "substack"
        },
        {
            "name": "tatumcreative"
        },
        {
            "name": "thibauts"
        },
        {
            "name": "wwwtyro"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "gl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/stackgl/headless-gl.git"
    },
    "scripts": {
        "install": "prebuild --install",
        "prebuild": "prebuild --all --strip",
        "rebuild": "node-gyp rebuild --verbose",
        "test": "standard | snazzy && tape test/*.js | faucet"
    },
    "version": "4.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
