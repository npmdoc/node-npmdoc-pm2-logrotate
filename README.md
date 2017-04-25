# npmdoc-pm2-logrotate

#### basic api documentation for  [pm2-logrotate (v2.2.0)](https://github.com/pm2-hive/pm2-logrotate)  [![npm package](https://img.shields.io/npm/v/npmdoc-pm2-logrotate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pm2-logrotate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pm2-logrotate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pm2-logrotate)

#### Module to rotate logs of every pm2 application

[![NPM](https://nodei.co/npm/pm2-logrotate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2-logrotate)

- [https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "apps": [
        {
            "name": "pm2-logrotate",
            "script": "app.js"
        }
    ],
    "author": {
        "name": "Joni SHKURTI"
    },
    "bugs": {
        "url": "https://github.com/pm2-hive/pm2-logrotate/issues"
    },
    "config": {
        "max_size": "10M",
        "retain": "all",
        "compress": false,
        "dateFormat": "YYYY-MM-DD_HH-mm-ss",
        "workerInterval": "30",
        "rotateInterval": "0 0 * * *",
        "rotateModule": true
    },
    "dependencies": {
        "moment-timezone": "0.5.5",
        "node-schedule": "1.1.1",
        "pm2": "latest",
        "pmx": "latest"
    },
    "description": "Module to rotate logs of every pm2 application",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "d46ef034156151857e7798e99c5d81ad2084c653",
        "tarball": "https://registry.npmjs.org/pm2-logrotate/-/pm2-logrotate-2.2.0.tgz"
    },
    "gitHead": "815ceb1294366405d30ef80fd0cd4c456dfe41f0",
    "homepage": "https://github.com/pm2-hive/pm2-logrotate",
    "license": "MIT",
    "main": "app.js",
    "maintainers": [
        {
            "name": "alavit-d"
        },
        {
            "name": "jshkurti"
        },
        {
            "name": "tknew"
        },
        {
            "name": "vmarchaud"
        }
    ],
    "name": "pm2-logrotate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pm2-hive/pm2-logrotate.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "2.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
