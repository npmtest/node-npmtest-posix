# npmtest-posix

#### basic test coverage for  [posix (v4.1.1)](http://github.com/ohmu/node-posix)  [![npm package](https://img.shields.io/npm/v/npmtest-posix.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-posix) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-posix.svg)](https://travis-ci.org/npmtest/node-npmtest-posix)

#### The missing POSIX system calls

[![NPM](https://nodei.co/npm/posix.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/posix)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-posix/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-posix/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-posix/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-posix/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-posix/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-posix/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-posix/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-posix/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-posix/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-posix/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-posix/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-posix/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-posix/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-posix/build/test-report.html](https://npmtest.github.io/node-npmtest-posix/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-posix/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-posix/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-posix/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-posix/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-posix/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-posix/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-posix/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-posix/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mika Eloranta"
    },
    "bugs": {
        "url": "https://github.com/ohmu/node-posix/issues"
    },
    "dependencies": {
        "nan": "2.4.x"
    },
    "description": "The missing POSIX system calls",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "cc9e1b87316f68e782a4316c94dca0d1741e471a",
        "tarball": "https://registry.npmjs.org/posix/-/posix-4.1.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "8a7b79e04372169309e47298213478fdd9c2d149",
    "gypfile": true,
    "homepage": "http://github.com/ohmu/node-posix",
    "keywords": [
        "posix",
        "rlimit",
        "getrlimit",
        "setrlimit",
        "ulimit",
        "setuid",
        "setgid",
        "seteuid",
        "setegid",
        "chroot",
        "setreuid",
        "setregid",
        "getpgrp",
        "setsid",
        "setpgid",
        "getpwnam",
        "getgrnam",
        "uid",
        "gid",
        "initgroups",
        "syslog",
        "setlogmask",
        "gethostname",
        "sethostname",
        "swapon",
        "swapoff"
    ],
    "license": "MIT",
    "main": "./lib/posix",
    "maintainers": [
        {
            "name": "mel"
        }
    ],
    "name": "posix",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ohmu/node-posix.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "make test"
    },
    "version": "4.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
