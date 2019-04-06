使用=写一级标题 这是一级标题  
========================  
使用-写一级标题 这是二级标题
----------------------
# 使用#可写1-6级标题，#与标题之间用空格间隔 标题后可以不用两空格换行
# 一级标题  
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
# 段落的换行是使用两个空格加回车  
# 字体
*斜体文字*  
_斜体文字_  
**粗体文字**  
__粗体文字__  
***粗斜体文字***  
___粗斜体文字___  
# 分割线可以使用三个以上的*或-或_来建立分割线，中间可以有空格
--------------------
************
_______________
* * * *
- - - - 
_ _ _ _
# 删除线 使用~~对文字进行包围
学习  
~~贪玩~~  
# 下划线 可通过html的<u>来实现  
<u>带下划线的文本，这个方法失败了</u>
# 脚注
创建脚注的格式为 [^happy]  
[^happy]: 要开心呀，哎 又失败了  
# 列表
无序列表使用*，+，-作列表标记 有空格
* 第一项
+ 第二项
- 第三项
- 第四项 感觉*，+隔得开一点  
有序列表，数字加.   
1. 第一  
2. 第二  
# 列表嵌套只需在子列表选项添加四个空格  
1. 第一项：  
    - 一嵌套
    - 一嵌套2
2. 第二项：  
    - 同理
    -同理2
# 区块
> 段落开头使用>符号，然后跟一个空格  
> 区块引用  
> 爬虫好难  
> 学习也好难  
# 区块嵌套
> 最外层  
>> 第一嵌套层
>>> 第二嵌套层
# 区块中使用列表
> 1. 第一项  
> 2. 第二项  
> + first
> + second
> + third
# 列表中放区块，需要在>前放四个空格的缩进
* first
    > study  
    > well done
* second
    > come on
****************
# 代码
用```包裹一段代码 可以指定一种语言 比如javascript 也可以不指定
```javascript
$(document).ready(function () {
    alert('runoob');
});
```
****
# 链接
[]内是链接名称，()里面放链接地址
这是一个链接[好好学习](http://www.runoob.com)  
也可以直接使用<http://www.runoob.com/markdown>
-------
# 高级链接
链接也可以用变量来代替，文档末尾附带变量地址：  
这个链接用 1 作为网址变量 [Google][1]  
这个链接用 runoob 作为网址变量 [Runoob][runoob]  
然后在文档结尾为变量赋值（网址）

[1]:http://www.google.com  
[runoob]:http://www.runoob.com
****
# 图片
* 开头一个感叹号！  
* 接着一个[]，里面放上图片的替代文字  
* 接着一个(),里面放图片网址，最后可以用引号包住并加上选择性的'tittle'属性文字  
![image](https://github.com/Jcduhdt/learn-tensorflow/blob/master/image/tensorboard.png)  
![Test 图标](https://github.com/Jcduhdt/learn-tensorflow/blob/master/image/tensorboard.png 'test')
<img src="https://github.com/Jcduhdt/learn-tensorflow/blob/master/image/tensorboard.png" width="50%">  
_____________
# 表格
使用|分割不同单元格，使用-分割表头和其他行，感觉又失败了   
|左对齐  | 居中 | 右对齐|  
| :---  | :---: | ---:|  
| 单元格 | 单元格 | 单元格|  
| 单元格 | 单元格 | 单元格|  
*******
# 高级技巧
支持HTML元素，不再markdown涵盖范围内的标签都可以直接用HTML撰写  
比如：  
使用 <kdb>Ctrl</kdb>+<kdb>Alt</kdb>+<kdb>Del</kdb> 重启电脑  
***
# 转义
利用反斜杠键入普通符号 比如\* \_ \#
*****
# 公式
插入数学公式时，可以使用两个美元符号$$包裹Tex或LaTex格式的数学公式来实现  
又失败了，慢慢学吧。。  
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}  
\mathbf{i} & \mathbf{j} & \mathbf{k} \\  
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\  
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\  
\end{vmatrix}  
$$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}  
$$
