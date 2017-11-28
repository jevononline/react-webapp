# 使用React模仿大众点评

## 技术栈：
react + react-router4.1 + redux + less + ES6/7 + webpack + fetch + bundle-loader

## 下载

 	git clone https://github.com/jevononline/react-webapp.git

 	cd react-webapp-dianping

 	npm install

 ## 运行（nodejs 6.0+）
```
 npm run dev (正常编译模式)

 访问 http://localhost:8080

 npm run build （发布生产版本，对代码进行混淆压缩，提取公共代码，分离css文件）
```

```
初次提交
```

```
1.利用webpack的bundle-loader实现代码分割，最终实现根据路由按需加载，加快用户对首屏的访问速度
2.添加fastclick解决移动端300毫秒延迟
3.实现详情页面，复用之前的列表组件和加载组件，只是样式和数据结构不一样
```

```
利用CSS Modules进行解决css的命名混乱以及全局污染
```
## 说明

>  本项目主要理解 react 和 redux 的原理，以及 react + redux 之间的配合方式，同时对react-router4进行由浅入深的学习和探究，欢迎大家一起学习新的路由方式

>  如果觉得不错的话，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

