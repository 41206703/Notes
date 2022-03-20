

[TOC]

# 基础

## 收集表单

- v-model可以双向绑定，用于收集**value属性**的值
- 如果是多组的勾选框，v-model所绑定的应该是一个数组，且要赋予value值



## 过滤器

- {{arguments | function}}



# 重要的vue

>语雀收藏的VUE课程笔记



## vue重要的思想

- vue是==数据驱动==的，我们只需要去维护数据

  > 例如：我们点击一个数据框控制他是否选定的时候，会弄出来一个isChecked放进data里面

- 

## 组件

- 父传递给子：props
  - 但是注意：props传参数只能适用于父穿子，因为vue不允许子修改props里面的数据
- 子到父：
  - 方法1：
    - 父传给子方法（通过props）
    - ==用事件总线，自定义组件事件==（挂载在vue.prototye.\$bus）上,子组件用this.\$emit散发出去，接受的父组件用回掉函数接受数据
    - pubsub-js库



## Vuex



## Vue-Router

- ![image-20220317202612577](https://s2.loli.net/2022/03/17/XAG1JbFKCRwHUSf.png)
  - 确实巧妙，':'这个后面的“”中的表达式按照js解析，js里面用``表达式这样可以模板解析数据
- include=""中间的是**组件名**，而不是理由名

