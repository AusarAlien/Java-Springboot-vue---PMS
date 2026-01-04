# 药房管理系统 药店管理系统   

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```



如果npm install 发生如下错误
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! node-sass@5.0.0 postinstall: `node scripts/build.js`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the node-sass@5.0.0 postinstall script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
npm verb exit [ 1, true ]
npm timing npm Completed in 35164ms

应该是 node-sass安装不成功 添加一个​​node-sass​​ 的数据源，在install 就OK了

解决方法：
执行 npm config set sass_binary_site=https://npm.taobao.org/mirrors/node-sass
再执行 npm install 就可以了


