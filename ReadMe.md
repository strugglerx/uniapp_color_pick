# uniapp 颜色选择器 用户自定义主题色

颜色选择器 用户可以自己选择主题色，觉得不错可以点个赞哦 :+1: 使用环境为 `uni-app`。  
  

## 如何获取
github仓库: [https://github.com/strugglerx/uniapp_color_pick](https://github.com/strugglerx/uniapp_color_pick)  
  
## props
| 参数|描述|类型|默认值|
|--|--|--|--|
|:unitWidth|基准单位,右边色相带宽度为40，左边选择块宽高为40*7+20，单位为px，需要使用者自己规划布局|number|40|

## methods
| 参数|描述|类型|默认值|
|--|--|--|--|
|@callBack|返回选择的颜色|object|--|

## 如何使用
*.vue
```html
<color-picker :unitWidth="unitWidth" @callBack="callBack"/>
```
  
```javascript
    import colorPicker from "../../components/struggler-colorPicker/struggler-colorPicker"
    export default {
        data() {
            return {
                unitWidth:30
            }
        },
        components:{
            colorPicker
        },
        methods:{
            callBack(e){
                //do Something
            }
        }
    }
```

  
## 实际效果

![](https://github.com/strugglerx/uniapp_color_pick/blob/master/1.png?raw=true)

![](https://github.com/strugglerx/uniapp_color_pick/blob/master/2.png?raw=true)



## 反馈问题
如在使用中发现bug或有优化的建议和意见，请发邮件 <str@li.cm> 或在 [gitHub](https://github.com/strugglerx/uniapp_color_pick) 上反馈。

:zap:wechat:strongdreams
  
## 更新日志

- 2019/12/03 v0.0.1