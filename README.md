# qiankun-study
乾坤微实践
single-spa
2018年 Single-SPA诞生了， single-spa 是一个用于前端微服务化的 JavaScript 前端解决
方案 (本身没有处理样式隔离， js 执行隔离) 实现了路由劫持和应用加载
2019年 qiankun 基于Single-SPA, 提供了更加开箱即用的 API （ single-spa + sandbox
+ import-html-entry ） 做到了，技术栈无关、并且接入简单（像i frame 一样简单）
总结：子应用可以独立构建，运行时动态加载,主子应用完全解耦，技术栈无关，靠的是协
议接入（子应用必须导出 bootstrap、mount、unmount方法）