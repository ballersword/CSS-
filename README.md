为了对照原始css用法和新css高级用法：

与示例无关属性用**other**表示：

~~~
<div class="other o">定位居中</div>
<style>
.other{background:#ffffff}
</style>
~~~

原始css示例用**o**表示：

~~~
<div class="color o">定位居中</div>
<style>
.o{width:300px;height:200px;position: absolute;left: 50%; top: 200px;margin:0 0 0 -150px;}
</style>
~~~
>如果有额外的属性，用数字罗列，例如：o2，o3等

新css示例用**x**表示：
~~~
<div class="color x">定位居中</div>
<style>
.x{width:fit-content;height:fit-content;position: absolute;left: 0; top: 0; right: 0;bottom: 0;margin: auto;}
</style>
~~~

动画调用使用**act**表示：
~~~
<div class="color act o">定位居中</div>
<style>
@keyframes tinyUp{
	from {transform: translateY(5px);}
	to {transform: translateY(0);}
}
.act{animation: tinyUp 1s;}
</style>
~~~
