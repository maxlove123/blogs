1. [polka -- 基于express的微型Web服务器](https://github.com/lukeed/polka)简单程序上比express快30%；支持中间件：包括express中间件；和express几乎相同的api和路由模式；
## Koa
1. [safe-start-koa2 -- 简單直接的 Koa2 的脚手架](https://github.com/chungchi300/safe-start-koa2)

## 数据库驱动
1. [node-mongodb-native -- Mongo DB本机NodeJS驱动程序](https://github.com/mongodb/node-mongodb-native)
2. [better-sqlite3 -- Node.js中最快和最简单的SQLite3库](https://github.com/JoshuaWise/better-sqlite3)
3. [bull -- 用于处理NodeJS中的作业和消息的高级包，最快，最可靠，基于Redis的Node队列](https://github.com/OptimalBits/bull)

## 科学计算
1. [stdlib -- stdlib是JavaScript和Node.js的标准库，重点放在数字和科学计算应用程序上。](https://github.com/stdlib-js/stdlib)

    ![demo](https://camo.githubusercontent.com/603be274fc41ee39a4095b7c349016f85ee31945/68747470733a2f2f63646e2e7261776769742e636f6d2f7374646c69622d6a732f7374646c69622f323033383339333533626337343239376665363431323037323730663739313764326264613536302f646f63732f6173736574732f726561646d652f626173655f7370656369616c5f6d6174682e706e67)
## 路径匹配
1. [node-glob -- node中glob模式下路径匹配](https://github.com/isaacs/node-glob)
```js
var glob = require("glob")

// options is optional
glob("**/*.js", options, function (er, files) {
  // files is an array of filenames.
  // If the `nonull` option is set, and nothing
  // was found, then files is ["**/*.js"]
  // er is an error object or null.
})
```
## 调试工具
1. [ndb -- ndb是针对Node.js的改进调试体验，由Chrome DevTools启用](https://github.com/GoogleChromeLabs/ndb)