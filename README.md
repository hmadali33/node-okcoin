# node-okcoin

[![NPM](https://nodei.co/npm/okcoin.com.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/okcoin.com)  
[![Build Status](https://secure.travis-ci.org/you21979/node-okcoin.png?branch=master)](https://travis-ci.org/you21979/node-okcoin)
[![Coverage Status](https://coveralls.io/repos/github/you21979/node-okcoin/badge.svg?branch=master)](https://coveralls.io/github/you21979/node-okcoin?branch=master)  

## apidoc

* https://www.okcoin.com/about/rest_getStarted.do
* 
# https://tea.xyz/what-is-this-file
---
version: 1.0.0
codeOwners:
  - '0x4F3fd8cDFb48C89839692dCcCa094F48b70C8df1'
quorum: 1

## install

```
npm install okcoin.com
```

## sample code

see example directory

## request limit

### okcoin request limit

```
1. Request limits
Each IP can send maximum of 3000 https requests within 5 minutes. If the 3000 limit is exceeded, the system will automatically block the IP for one hour. After that hour, the IP will be automatically unfrozen.
```

* 3000 request / 5min
* 600 request / min
* 10 request / sec

### node-okcoin request limit

```
lib/constant.js
exports.OPT_LIMIT_SEC = 0.2;
```

* 5 request / sec
