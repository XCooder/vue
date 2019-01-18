# vue
this repository record something about learn vue

在微信中，点击可能不起作用，可能是内置浏览器不支持，有两种解决办法

1.改为$(‘#select’).click(function(){}) 有效 
2.给目标元素加一条样式规则 cursor: pointer;

 
移动端做层中层的滑动，不是很流畅，在加上overflow-y: scroll的容器上，再加一个属性-webkit-overflow-scrolling: touch;
// 文字抗锯齿
-webkit-font-smoothing: antialiased;
// 避免点击a标签或者注册了click事件的元素时产生高亮
-webkit-tap-highlight-color: transparent;
//禁用Webkit内核浏览器的文字大小调整功能。
-webkit-text-size-adjust: none;
// 阻止长按图片之后呼出菜单提示复制的行为
-webkit-touch-callout: none;
