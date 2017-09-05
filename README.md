# vue-better-confirm

## 这是什么(What is it)
为vue提供的仿原生ios confirm组件

## 代码演示如何使用

npm install vue-better-confirm

在需要的项目文件中导入改组件 import Confirm from 'vue-better-confirm'

具体代码引用
先注册改组件之后
```javascript
components: {
  Confirm
}
```
template模板使用例子如下
```javascript
<confirm ref="confirm" @confirm="yourEvent" text="标题内容" confirmBtnText="确定" cancelBtnText="取消"></confirm>
```

## 效果图

![](https://github.com/songhaoreact/vue-better-confirm/blob/master/gif.gif)











