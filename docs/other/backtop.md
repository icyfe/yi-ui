# BackTop

## 基本使用

::: demo
```vue
<template>
    <div>
        <u-back-top :height="50"/>
        滚动后右下方显示
    <div>
</template>
```
:::

## Scope

::: demo
``` vue
<template>
    <u-back-top :height="100" :bottom="200">
        <div class="backtop-self-style">返回顶端</div>
    </u-back-top>
</template>

<style>
.backtop-self-style{
    padding: 10px;
    background: rgba(0, 153, 229, .7);
    color: #fff;
    text-align: center;
    border-radius: 2px;
}
</style>
```
:::

## API #
### u-back-top props #

 | 属性 | 说明 | 类型 | 默认值 |
 | -- | -- | -- | -- |
 | height | 页面滚动高度达到该值时才显示u-back-top组件 |  |  | Number | 400 | 
 | bottom | 组件距离底部的距离 | Number | 30 | 
 | right | 组件距离右部的距离 | Number | 30 | 
 | duration | 滚动动画持续时间，单位 毫秒 | Number | 1000 |

### u-back-top events #
 | 事件名 | 说明 | 返回值 | 
 | -- | -- | -- |
 | on-click | 点击按钮时触发 | 无 | 
