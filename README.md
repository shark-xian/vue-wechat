# vue-wechat
> 用vue.js开发微信app(ios版)界面的demo

vue 
vuex 
vue-cli
vue-router 
vue-toutch 
vue-animated-list

weui
zepto
fastclick




### 安装

``` bash
# install dependencies
cnpm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

```

## 基本操作
####页面切换,动画过渡
(仿照ios系统切换风格:下一页打开时,当前页左偏移-30%;当前页关闭时,上一页左偏移从-30%过渡到0%)
![](./src/assets/images/readme/view-wechat-animation.gif)

####消息列表 (未读/已读)操作 及 删除
![](./src/assets/images/readme/view-wechat-chat.gif)

####发现-朋友圈
![](./src/assets/images/readme/view-wechat-find-albums-friends.gif)

####发现-扫一扫
![](./src/assets/images/readme/view-wechat-find-sao-yi-sao.gif)


### 开发约定
``` bash
所有变量名 统一小写
所有方法   统一驼峰
常量    全部大写+下划线
所有组件.vue名 都统一 《短横线》 命名
引入时,components选项改为驼峰
减少使用分号( ; )  大括号后面不加,var 命名要加,return 要加
单引号优先
css内下划线( _ )开始的为通用类
js中内下划线( _ )开头的为私有属性
所有events均使用短横线 命名
所有组件(.vue)里template标签包含的元素必须是component-xx 开头
所有state统一下划线 命名
所有 action统一下划线命名
```


### 参考

[Vue-cnodejs](https://github.com/shinygang/Vue-cnodejs)

[vue-zhihu-daily](https://github.com/hilongjw/vue-zhihu-daily)

[vue-mobile-qq](https://github.com/hilongjw/vue-mobile-qq)

[vue-shopping](https://github.com/andylei18/vue-shopping)
