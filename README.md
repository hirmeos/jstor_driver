# JSTOR Driver
[![Build Status](https://travis-ci.org/hirmeos/jstor_driver.svg?branch=master)](https://travis-ci.org/hirmeos/jstor_driver) [![Release](https://img.shields.io/github/release/hirmeos/jstor_driver.svg?colorB=58839b)](https://github.com/hirmeos/jstor_driver/releases) [![License](https://img.shields.io/github/license/hirmeos/jstor_driver.svg?colorB=ff0000)](https://github.com/hirmeos/jstor_driver/blob/master/LICENSE)

## Run via crontab
```
0 0 * * 0 docker run --rm --name "jstor_driver" --env-file /path/to/config.env -v jstor_cache:/usr/src/app/cache -v metrics:/usr/src/app/output openbookpublishers/jstor_driver:1
```
