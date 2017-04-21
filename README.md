# npmdoc-module-generator

#### api documentation for  [module-generator (v2.1.0)](https://github.com/mattdesl/module-generator)  [![npm package](https://img.shields.io/npm/v/npmdoc-module-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-module-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-module-generator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-module-generator)

#### The generator script I use for fresh modules

[![NPM](https://nodei.co/npm/module-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/module-generator)

- [https://npmdoc.github.io/node-npmdoc-module-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-module-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-module-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-module-generator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-module-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-module-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "module-generator",
    "version": "2.1.0",
    "bin": {
        "module-generator": "index.js"
    },
    "description": "The generator script I use for fresh modules",
    "main": "index.js",
    "license": "MIT",
    "scripts": {},
    "contributors": [
        "Matt DesLauriers <dave.des@gmail.com>"
    ],
    "author": "Hugh Kennedy <hughskennedy@gmail.com> (http://hughsk.io/)",
    "dependencies": {
        "chalk": "^0.5.1",
        "dotty": "0.0.2",
        "inquirer": "^0.5.1",
        "js-string-escape": "^1.0.0",
        "npm": "^2.1.2",
        "npmconf": "^1.0.1",
        "readdirp": "^1.0.1",
        "semver": "^4.0.3",
        "variable-name": "0.0.1",
        "xtend": "^3.0.0",
        "yargs": "^1.3.1"
    },
    "devDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mattdesl/module-generator.git"
    },
    "keywords": [
        "generator",
        "not-yeoman",
        "template",
        "module",
        "author",
        "npm"
    ],
    "homepage": "https://github.com/mattdesl/module-generator",
    "bugs": {
        "url": "https://github.com/mattdesl/module-generator/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
