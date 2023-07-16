Number数字型：整型，浮点型
Boolean布尔值
String字符串
Undefined声明了但是没有赋值
Null var a=null，生命变量a为空值

一、Number类型

**八进制表示：数码前面加0表示为八进制，例如010表示八进制的10，转为十进制得到8
**十六进制表示：数码前面加0x表示十六进制，例如0x9表示十六进制的9，转为十进制得到9

Number.MAX_VALUE  Number类型的最大值
Number.MIN_VALUE  Number类型的最小值

Infinity   Number类型中的无穷大
-Infinity  Number类型中的无穷小
NaN        Not a number非数值

isNan()方法，返回布尔值

二、String类型
'' or "", both okay, but '' is recommended.
字符串的嵌套中的引号规则：外双内单，外单内双

转义符（和java一样）：
\n 换行
\\ 斜杠
\' 单引号
\" 双引号
\t tab缩进
\b 空格

字符串长度: .length属性
字符串拼接：str1+str2

boolean中 true在数字运算时当作1，false在数字运算时当作0（数字逻辑中的正逻辑）

***
Undefined, Null
Undefined和数字相加，结果是NaN
Undefined和String(str)相加，结果是"Undefinedstr"
null和String(str)相加，结果是nullstr
null和数字（10）相加，结果是10

获取数据类型：例如 console.log(typeof 变量) typeof是一个关键字，不是一个方法
注意：typeof null=object
**prompt方法取过来的值会自动转换成String

chrome控制台中黑色表示String，蓝色是Num，深蓝色是boolean，灰色是undefined和null

数据类型转换：
1.转成String： toString(num), String(num), 加号拼接字符串
2.转成数字型： parseInt(str), parseFloat(str), Number(str),运用算术表达式进行隐式转换 例如： '12'-0得到12， '12'/1得到12， '12'*1得到12 （没有+，因为+同时也是字符串的运算表达式）
3.转换成布尔值： Boolean(var) 0,NaN,undefined,null均会转成false，其余都是true






