# vue
this repository record something about learn vue

在微信中，点击可能不起作用，可能是内置浏览器不支持，有两种解决办法

1.改为$(‘#select’).click(function(){}) 有效 
2.给目标元素加一条样式规则 cursor: pointer;

 
移动端做层中层的滑动，不是很流畅，在加上overflow-y: scroll的容器上，再加一个属性-webkit-overflow-scrolling: touch;
