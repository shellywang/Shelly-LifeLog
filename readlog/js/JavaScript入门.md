---
时间: 2018-8-14 
作者：王召莉
---
# JavaScript 入门
JavaScript是一种轻量级的脚本语言，也是一种嵌入式语言。

Chrome 控制台进入方法：
	- Ctrl+Shift+J
	- 开发者工具 F12，或Ctrl+Shift+I
## 基本语法
### 语句
JavaScript程序的执行单位为行，也就是一行一行地执行，一行就是一个语句。
语句；号结束。
### 变量
变量是对值的具名引用，变量就是为值起名，然后引用这个名字。变量的名字就是变量名。
JavaScript的变量名区分大小写。
如果变量只是声明而没有赋值，则该变量的值是undefined。
undefined是JavaScript的关键字，表示无定义。
var命令声明变量。
如果使用var重新声明一个已经存在的变量，第二次声明无效。如果第二次声明赋值，则覆盖前面的值。
#### 变量提升
JavaScript先解析代码，获取所有被声明的变量，然后再一行一行地运行，所有的变量的声明语句，都会被提到代码的头部。
### 区块
对于var命令来说，JavaScript的区块不构成单独的作用域。
## 数据类型
- 数值number
- 字符串string
- 布尔值boolean
- undefined未定义
- null空值
- 对象object
### typeof运算符
- typeof运算符：返回一个值的数据类型
- instanceof运算符
- Object.prototype.toString方法