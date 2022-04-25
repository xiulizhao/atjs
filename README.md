# atjs
用于输入框输入@功能<br>
<img src="http://www.wware.org/img/@@@.jpg?_5cc8" width="400px"><br>
普通属性<br>
data-iframeid	如果需要用iframe引入的，需要绑定该属性（iframe的类或者id）	#test/.test<br>
控制属性<br>
data--atdata	被@的数据	["Peter", "Tom", "Anne"]<br>
# 注意事项
1、元素input中的class不要删除，input可以修改为一切元素，但是元素的class名 note-editable一定不要删除<br>
2、如果该元素被 iframe引入了，一定要将iframe定义 类或者 id，将该iframe的类名或者id名绑定在输入框@元素上，右键也可以直接设置，格式为#test、.test<br>
