# dragging.js简介
dragging.js使用原生JS开发，主要用于弹出框等元素的鼠标来回拖动！

![image](https://github.com/zymseo/dragging/blob/master/images/dragging.png)

### 在线demo
- [http://www.zymseo.com/demo/dragging/](http://www.zymseo.com/demo/dragging/)
- 以上demo请在PC浏览器的手机模式下浏览

### 说明 
- 如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^
- 或者您可以 "follow" 一下，我会不断开源更多的有趣的项目

### 使用方法

### 配置
``` javascript
dragging({
	targetObj: '#edit-title', // 鼠标按下的目标dom对象
	movingObj: '#edit-wraper' // 外部移动的dom对象
});
```

### html

``` html
<link rel="stylesheet" type="text/css" href="./css/dragging.css" />
<script type="text/javascript" src="./js/dragging.js"></script>
```

### （1）使用script 标签引入:

``` javascript
<script type="text/javascript" src="./js/dragging.js"></script>
<script type="text/javascript">
	dragging({
		targetObj: '#edit-title',
		movingObj: '#edit-wraper'
	});
</script>
```
### （2）使用requireJs异步引入:
``` javascript
require(['dragging'], function (dragging) {
	dragging({
		targetObj: '#edit-title',
		movingObj: '#edit-wraper'
	});
});
```
### （3）使用ES6方式导入：
``` javascript
import dragging from './js/dragging.js';
dragging({
	targetObj: '#edit-title',
	movingObj: '#edit-wraper'
});
```
### 基于 MIT license 开源
- 博客：[@赵一鸣](http://www.zymseo.com)
- QQ：1047832475
