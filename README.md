This project is to pratice front-end skills. 
sticky nav bar
auto highlight nav bar
auto scroll smoothly
menu
auto hide aside
gapless slide show

添加loading动画

event.target 用户操作的元素
event.currentTarget 监听的元素
Node.nextSibling
NodeType 
1  -- 节点
3  -- 文本

Node.nodeName --- 大写 'BODY' 'HEAD'

magin-right:100% 父亲的100%

###### 解决一个问题的关键：是马上着手解决问题
####### 多次尝试，不停修改，不停的改进

<!-- CSS是没有完美的，所以你必须不断去完善 -->
使用锚点定位-看不见上面的title!!出现新的bugs


console.log(a.href); //输出解析的完整地址
console.log(a.getAttribute('href')); //里面写啥就输出啥

document.querySelectorAll('选择器') //返回数组

getBoudingClientRect()

offsetTop 
        为只读属性，它返回当前元素相对于其 offsetParent 元素的顶部内边距的距离。

<!-- window.scrollTo(x,y) 起始点都是左上角 -->
window.scrollTo(x-coord,y-coord)
coord：坐标的意思

offsetTop offsetLeft 属性详解：相对于上层元素 这个属性是不会变的
offsetParent 最近的具有定位最近的具有
定位的父级元素

var timeid = setInterval(()=>{
    if(n >= 200){
        window.clearInterval(timeid);
    }
})



动画的效果优化： tweenjs
<!-- <!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>JS Bin</title>
</head>
<body>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tween.js/18.6.0/tween.umd.js"></script>
  <script>
      function animate(time) {
	requestAnimationFrame(animate);
	TWEEN.update(time);
}
requestAnimationFrame(animate);
var coords = {x: 0, y: 0};
var tween = new TWEEN.Tween(coords)
	.to({x: 300, y: 200}, 1000)
	.easing(TWEEN.Easing.Quadratic.Out)
	.onUpdate(function(){
      console.log(coords.x,coords.y);
	})
	.start();
  </script>
</body>
</html> -->
学会如何在不懂的时候解决问，这个是关键
就是学会如何用基础知识学会如何去拷贝别人的代码


标签的标记！
<div data-x></div>
document.querySelectorAll('div[data-x]');


##### 不同的动作定义不同的类来定义，这样在js出发的时候不会产生冲突