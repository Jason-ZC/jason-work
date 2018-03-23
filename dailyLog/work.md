工作日志 先这样，之后整理
2018/3/22
补grunt requirejs 项目需要 已补
encodeURIComponent(URIstring) 可以把字符串作为URI组件进行编译
2018/3/23
js中 o = o || {};是什么意思
    如果o为null或undefined，则将o初始化空对象（即{}），否则o不变。目的是防止o为null或未定义的错误
require.js
    1.实现js文件的异步加载，避免网页失去响应；
    2.管理模块之间的依赖性，便于代码的编写和维护。
shim和polyfill
    一个shim是一个库,它将一个新的API引入到一个旧的环境中,而且仅靠旧环境中已有的手段实现
    一个polyfill就是一个用在浏览器API上的shim.我们通常的做法是先检查当前浏览器是否支持某个API,如果不支持的话就加载对应的polyfill.然后新旧浏览器就都可以使用这个API了.
    在实际中为了方便做对比，会特指 shim 的 api 不是遵循标准的，而是自己设计的。
