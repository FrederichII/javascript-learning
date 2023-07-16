创建数组：

1.利用new关键字创建数组
var name_of_array = new Array();
var arr= new Array;
在js中Array是一个类

2.利用数组字面量创建数组
var name_of_array = [];
var name_of_array = [1,'two',false,undefined,null];

访问数组元素：
arr[2]

数组长度：
arr.length

数组新增元素：
1.通过修改length长度实现扩容
var arr=[1,2,3];
arr.length=5;
[1,2,3,undefined,undefined]

2.修改数组索引新增数组元素
var arr=[1,2,3];
arr[3]='pink';
[1,2,3,'pink']
