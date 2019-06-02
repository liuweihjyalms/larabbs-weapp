# larabbs-weapp
 微信小程序,WePY--小程序组件化开发框架，开发风格接近 Vue.js，更贴近于 MVVM 架构模式，相比小程序原生开发要更加的方便快捷

## 初始化 WePY 
- 首先需要全局安装 wepy-cli
- sudo yarn global add wepy-cli
- wepy -v 可以查看到目前版本
- wepy init standard ./  初始化项目交互式命令行程序
- wepy build --watch 项目进行编译

## sublime 手动安装插件
- [wpy文件高亮](https://github.com/vuejs/vue-syntax-highlight)

## WeUI
- [WeUI](https://github.com/Tencent/weui) 是一套同微信原生视觉体验一致的基础样式库，由微信官方设计团队为微信 Web 开发量身设计，可以令用户的使用感知更加统一，当然也有小程序版本的 [WeUI](https://github.com/Tencent/weui-wxss)，这一节我们来了解 WeUI 的使用。
- 我们使用了 WePY 框架，那么 WePY 如何使用 WeUI 呢，这里 有一个官方推荐的例子供大家参考，我们先将这个项目导入开发者工具。
- git clone git@github.com:wepyjs/wepy-weui-demo.git