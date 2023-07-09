# MIP-Nuxt-FrontEnd

> 一个医疗信息平台前端项目

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).

## 1.遇到的问题和解决方法：
1.css的代码中url一定要规范，不能多空格和少空格，否则会报错。

例如：```'/hosp/detail/'``` 不能写为 ```'/hosp/detail /'```，也不能写为 ```'/hosp/detail/ '```

排错思路：

（1）先F12查看响应状态码，如果是404，说明是路径错误，如果是500，说明是服务器错误。

（2）查看后端代码错误信息，或者前端控制台错误信息。

（3）修改相应的代码，重新运行。





