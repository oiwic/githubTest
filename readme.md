# 大标题使用
MD学习手册
=

# 中标题使用
这是中标题
-

# 分级标题使用
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

# 正常文本使用
这是普通文本需要以\<br>换行或者是用两个回车<br>
一个回车、多个Tab、多个空格只能识别为1个占位符

两个回车换行可以增加行间距实现分段。<br>

# 多行文本使用
	 在行前面加1*Tab+空格实现
		 在行前面加2*Tab+空格实现
			 在行前面加3*Tab+空格实现
# 使用高亮
这是`Tab`上面的符号,包围的`文本`实现高亮<br>

# 文字超链接
[MarkDown作者文档](https://daringfireball.net/projects/markdown/syntax)<br>
[github](github.com)<br>
[github](github.com "悬停")

[para1]: baidu.com "para1"
[para2]: baidu.com "para2"
add([para1],[para2])<br>
[github徽章介绍](http://www.cocoachina.com/programmer/20170512/19256.html)

# 图片超链接
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")

[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"  
[![baidu]](http://baidu.com)  

# 树状图使用
>数据结构
>>数
>>>二叉树
>>>>平衡二叉树
>>>>平衡二叉树
>>>>>满二叉树<br>满二叉树

# 插入代码
单行代码可以用\`\`例如`int k`
多行使用如下：
```Bash
echo "Hello"
```
```cpp
int x=0;
String x = "Hello"
```

# 分割线使用
***

# 序号使用
1. 1
1. 2
1. 3

* 1
* 2
* 3

* [哈哈1](baidu.com)
* [哈哈2](baidu.com)

* 1级圆点
	* 二级圆点

# 表格使用
| name | age | sex |
|:-:|:-:|:-:|
|Weiliam Shakespeare|46|男|
|Eili|14|女|

学号|姓名|分数
-|-|-
1|小明|59
2|小红|59
3|小李|59

表头1|表头2
-|-
1|2
3|4

# 斜体
*这是一个斜体字*

# 加粗
__字体加粗1__<br>
**字体加粗2**

# 删除线
~~这是被删除的内容~~

# 转义
* \\
* \`
* \~
* \_
* \-
* \+
* \.
* \!
