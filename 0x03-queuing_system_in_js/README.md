<div align="center">
    <img align="center" src="https://github.com/tivereidoro/assets/assets/105525310/8d298662-9874-46b0-aabc-54f837bcc6a4" alt="alx_swe" width="60"  height="60"/>
    
---
### 0x03. QUEUING SYSTEM IN JS
<img src="https://img.shields.io/badge/Back-end-eed718"> &nbsp;<img src="https://img.shields.io/badge/JavaScript-eed718"> &nbsp;<img src="https://img.shields.io/badge/ES6-3EAABF"> &nbsp;<img src="https://img.shields.io/badge/Redis-A41E11"> &nbsp;<img src="https://img.shields.io/badge/NodeJS-3EAABF"> &nbsp;<img src="https://img.shields.io/badge/ExpressJS-3EAABF"> &nbsp;<img src="https://img.shields.io/badge/Kue-3EAABF">

##
![91e1c50322b2428428f9](https://github.com/tivereidoro/assets/assets/105525310/52ca8586-618f-4163-8f4a-167b8d7a96ac)
</div>

##
### Resources (Read or watch):
* [Redis quick start](https://redis.io/docs/install/install-redis/)
* [Redis client interface](https://redis.io/docs/connect/cli/)
* [Redis client for Node JS](https://github.com/redis/node-redis)
* [Kue](https://github.com/Automattic/kue) _deprecated but still use in the industry_

## General Requirements:
* All of your code will be compiled/interpreted on Ubuntu 18.04, Node 12.x, and Redis 5.0.7
* All of your files should end with a new line
* A `README.md` file, at the root of the folder of the project, is mandatory
* Your code should use the `js` extension

## Project Requirements:
**`package.json`**
<details>
  <summary>Click to show/hide file contents</summary>
  
```groovy

{
    "name": "queuing_system_in_js",
    "version": "1.0.0",
    "description": "",
    "main": "index.js",
    "scripts": {
      "lint": "./node_modules/.bin/eslint",
      "check-lint": "lint [0-9]*.js",
      "test": "./node_modules/.bin/mocha --require @babel/register --exit",
      "dev": "nodemon --exec babel-node --presets @babel/preset-env"
    },
    "author": "",
    "license": "ISC",
    "dependencies": {
      "chai-http": "^4.3.0",
      "express": "^4.17.1",
      "kue": "^0.11.6",
      "redis": "^2.8.0"
    },
    "devDependencies": {
      "@babel/cli": "^7.8.0",
      "@babel/core": "^7.8.0",
      "@babel/node": "^7.8.0",
      "@babel/preset-env": "^7.8.2",
      "@babel/register": "^7.8.0",
      "eslint": "^6.4.0",
      "eslint-config-airbnb-base": "^14.0.0",
      "eslint-plugin-import": "^2.18.2",
      "eslint-plugin-jest": "^22.17.0",
      "nodemon": "^2.0.2",
      "chai": "^4.2.0",
      "mocha": "^6.2.2",
      "request": "^2.88.0",
      "sinon": "^7.5.0"
    }
  }

```
</details>


**`.babelrc`**
<details>
  <summary>Click to show/hide file contents</summary>
  
```groovy

{
  "presets": [
    "@babel/preset-env"
  ]
}

```
</details>


**and…**

Don’t forget to run `$ npm install` when you have the `package.json`

---

#### Code Editor used: Mostly `VS-Code`; also  `Vim`
##
#### AUTHOR 👨🏽‍💻:
[_Tivere IDORO_](https://github.com/tivereidoro)
