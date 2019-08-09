# vue2-demo

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## vw实现移动端适配

```
- postcss-import  
 // 会在项目根目录生成 **.postcssrc.js** 文件 主要是解决@import引入路径问题
 - postcss-url
  // 主要用来处理文件，比如图片文件、字体文件等引用路径的处理 
 - postcss-aspect-ratio-mini
  // 
 - postcss-cssnext
   // 该插件可以让我们使用CSS未来的特性，其会对这些特性做相关的兼容性处理
 - autoprefixer
 // 自动处理浏览器前缀的一个插件
 - postcss-px-to-viewport
  // 主要用来把px单位转换为vw、vh、vmin或者vmax这样的视窗单位，也是vw适配方案的核心插件之一
 - postcss-write-svg
  // 主要用来处理移动端1px的解决方案
 - cssnano
  // 主要用来压缩和清理CSS代码
 - postcss-aspect-ratio-mini
 // 主要用来处理元素容器宽高比
```


For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
