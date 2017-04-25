# npmdoc-react-images

#### basic api documentation for  [react-images (v0.5.2)](http://jossmac.github.io/react-images)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-images.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-images) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-images.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-images)

#### A simple, responsive lightbox component for displaying an array of images with React.js

[![NPM](https://nodei.co/npm/react-images.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-images)

- [https://npmdoc.github.io/node-npmdoc-react-images/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-images/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-images/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-images/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-images/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-images/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joss Mackison"
    },
    "browserify-shim": {
        "react": "global:React"
    },
    "bugs": {
        "url": "https://github.com/jossmac/react-images/issues"
    },
    "dependencies": {
        "aphrodite": "^0.5.0",
        "react-addons-css-transition-group": "^15.3.0",
        "react-scrolllock": "^1.0.1"
    },
    "description": "A simple, responsive lightbox component for displaying an array of images with React.js",
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-eslint": "^6.0.4",
        "eslint": "2.9.0",
        "eslint-config-keystone": "2.2.0",
        "eslint-plugin-react": "5.1.1",
        "gulp": "^3.9.0",
        "react": "^15.3.0",
        "react-component-gulp-tasks": "^0.7.0",
        "react-dom": "^15.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e1d537f9bcc71b8ba46b8d3ec984e0ee2ffd641b",
        "tarball": "https://registry.npmjs.org/react-images/-/react-images-0.5.2.tgz"
    },
    "gitHead": "c9e9b93b04683593058ef7cff4472ba3221da87f",
    "homepage": "http://jossmac.github.io/react-images",
    "keywords": [
        "react",
        "react-component",
        "react-images",
        "react-lightbox",
        "react-carousel",
        "react-gallery",
        "react images",
        "react lightbox",
        "react carousel",
        "react gallery",
        "lightbox",
        "carousel",
        "gallery"
    ],
    "license": "MIT",
    "main": "lib/Lightbox.js",
    "maintainers": [
        {
            "name": "jedwatson"
        },
        {
            "name": "jossmac"
        }
    ],
    "name": "react-images",
    "optionalDependencies": {},
    "peerDependencies": {
        "react-dom": "^0.14 || ^15.0",
        "react": "^0.14 || ^15.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jossmac/react-images.git"
    },
    "scripts": {
        "build": "gulp clean && NODE_ENV=production gulp build",
        "bump": "gulp bump",
        "bump:major": "gulp bump:major",
        "bump:minor": "gulp bump:minor",
        "examples": "gulp dev:server",
        "lint": "eslint src/** examples/src/app.js examples/src/components/Gallery.js",
        "publish:examples": "gulp publish:examples",
        "release": "gulp release",
        "start": "gulp dev",
        "watch": "gulp watch:lib"
    },
    "version": "0.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
