# npmdoc-npmlist

#### api documentation for  [npmlist (v3.1.2)](https://github.com/geekjuice/npmlist)  [![npm package](https://img.shields.io/npm/v/npmdoc-npmlist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npmlist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npmlist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npmlist)

#### Pretty npm list

[![NPM](https://nodei.co/npm/npmlist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npmlist)

- [https://npmdoc.github.io/node-npmdoc-npmlist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npmlist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npmlist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npmlist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npmlist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npmlist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npmlist",
    "version": "3.1.2",
    "author": "Nicholas Hwang <nick.joosung.hwang@gmail.com>",
    "license": "MIT",
    "description": "Pretty npm list",
    "repository": {
        "type": "git",
        "url": "git://github.com/geekjuice/npmlist.git"
    },
    "bugs": {
        "url": "https://github.com/geekjuice/npmlist/issues"
    },
    "homepage": "https://github.com/geekjuice/npmlist",
    "bin": "./bin/npmlist",
    "scripts": {
        "start": "./bin/npmlist",
        "watch": "gulp watch",
        "build": "gulp build"
    },
    "dependencies": {
        "chalk": "^1.0.0"
    },
    "devDependencies": {
        "mocha": "^2.2.5",
        "chai": "^3.0.0",
        "del": "^1.2.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.1.0",
        "gulp-bump": "^0.3.1",
        "gulp-filter": "^2.0.2",
        "gulp-plumber": "^1.0.1",
        "gulp-tag-version": "^1.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
