> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/weixin_48235955/article/details/135853400)

#### 文章目录

*   [0. 概述](#0_20)
*   [1.Typora 的快捷键](#1Typora_27)
*   [2. 文本](#2_49)
*   *   [2.1 文本颜色设置](#21__53)
    *   [2.2 文本背景色](#22__81)
    *   [2.3 文本字号设置](#23__99)
    *   [2.4 文本字体设置](#24__125)
    *   [2.5 实战演练](#25__154)
    *   [2.6 文字斜体](#26__168)
    *   [2.7 文字加粗](#27__183)
    *   [2.8 文本斜体 + 加粗](#28__198)
    *   [2.9 文本删除线](#29__216)
    *   [2.10 下划线](#210__232)
    *   [2.11 文本高亮](#211__246)
    *   [2.12 文本居中](#212__258)
    *   [2.13 段落缩进与段落空格](#213__282)
    *   [2.14 段落换行](#214__313)
*   [3. 特殊格式](#3_327)
*   *   [3.1 标题](#31__329)
*   [这是一级标题](#_348)
*   *   [这是二级标题](#_349)
    *   *   [这是三级标题](#_350)
        *   *   [这是四级标题](#_351)
            *   *   [这是五级标题](#_352)
                *   *   [这是六级标题](#_353)
    *   [3.2 目录](#32__355)
    *   [3.3 分割线](#33__371)
    *   [3.4 跳转语法](#34__387)
    *   *   [3.4.1 外部跳转](#341__389)
        *   [3.4.2 内部跳转](#342__403)
        *   [3.4.3 自动连接](#343__420)
    *   [3.5 字母上标和下标](#35__434)
    *   *   [3.5.1 设置：](#351__438)
        *   [3.5.2 上标](#352__444)
        *   [3.5.3 下标](#353__457)
        *   [3.5.4 LaTex 数学公式](#354_LaTex_470)
    *   [3.6 表格](#36__510)
    *   [3.7 引用](#37__534)
    *   [3.8 无序列表](#38__548)
    *   [3.9 有序列表](#39__569)
    *   [3.10 代码](#310__589)
    *   [3.11 图片](#311__612)
    *   *   [3.11.1 图片题注](#3111__650)
        *   *   [1. 直接下加标题](#1_654)
            *   [2. 封装型](#2_670)
        *   [3.11.2 调整大小](#3112__714)
        *   *   [方式 1：直接设置大小 (不推荐)](#1_716)
            *   [方式 2：按照比例进行缩放 (推荐)](#2_748)
            *   [方式 3：`<img src="路径">`（推荐）](#3img_src_777)
    *   [3.12 彩蛋](#312__808)
*   [4. 特殊符号](#4_821)
*   [5. 内置表情](#5_876)
*   *   [People](#People_898)
    *   [Nature](#Nature_963)
    *   [Object](#Object_1005)
    *   [Places](#Places_1096)
    *   [Symbols](#Symbols_1136)
*   [参考文献](#_1207)

0. 概述
-----

*   💧`Typora`是一款轻便简洁的 `Markdown` 编辑器，支持即时渲染技术，这也是与其他`Markdown`编辑器最显著的区别，将写作与预览窗口相结合，为用户呈现所见即所得的编辑模式，支持`Markdown`的各种基础语法，支持快捷键操作，是好用的一款`Markdown`编辑器。即时渲染功能使得你写`Markdown文件`就想是写`Word文档`一样流畅自如✅，不像其他编辑器的有编辑栏和显示栏。🍇`Typora`使用的是`GitHub` 风格的`Markdown` 语法，扩展了任务列表、表格、表情符号、数学公式、代码高亮等常用功能。
*   ☘️毛毛张在本篇博客中试图将`Typora`中的使用技巧进行一个详细的介绍，包括快捷键和语法，掌握这些技巧可以帮助我们更好更快的编写`markdown文档`。有些语法只有在购买的正版中才能适用，例如高亮、上下标和数学公式等
*   ✳毛毛张觉得这个软件比较好用，因此自己也去购买了一个正版的，不过也是因为价格不贵，所以才买的，买完之后发现用这个记笔记真的好用。💚不过在这里并没有带货和做广告的嫌疑，大家根据自己的需求，安装包毛毛张放在这里大家自行领取：[Typora 安装包](https://pan.baidu.com/s/1BnaGdPRtibsKMQhs9rgDOg?pwd=2024)
*   ⭐不仅如此，用`Typora`编辑的`markdown文件`还可以直接导入到`CSDN博客`中，学习了`Typora`的使用技巧之后写`CSDN博客`的时候很方便，直接导入就可以了👍

1.Typora 的快捷键
-------------

*   无序列表：`-` + 空格
*   有序列表：`1.` + 空格
*   引用：`>` + 空格
*   标题：`ctrl + 数字(1/2/3...)`
*   表格：`ctrl + t`
*   生成目录：`[TOC]` + 回车
*   选中一整行：`ctrl + l`
*   选中单词：`ctrl + d`
*   选中相同格式的文字：`ctrl + e`
*   跳转到文章开头：`ctrl + home`
*   跳转到文章结尾：`ctrl + end`
*   搜索：`ctrl+ f`
*   替换：`ctrl + h`
*   加粗：`ctrl+ b`
*   倾斜：`ctrl + i`
*   下划线：`ctrl + u`
*   删除线：`alt + shift+ 5`
*   插入图片：直接拖动到指定位置即可或者`ctrl + shift + i`
*   插入链接：`ctrl+ k`

2. 文本
-----

> 更多关于文本的设置可以学习`html`语法

### 2.1 文本颜色设置

**代码：**

**效果展示：**

1. 我是文本 红色 red  
2. 我是文本 蓝色  
3. 我是文本 粉红  
4. 我是文本 紫色  
5. 我是文本 黑色  
6. 我是文本 橙色  
7. 我是文本 灰色  
8. 我是文本 绿色  
8. 我是文本 红色 #FF0000

### 2.2 文本背景色

> **说明：**`typora`中并没有内容居中的选项，想要居中只能使用`html`语法

代码：

效果展示

<table><tbody><tr><td bgcolor="pink">这段文字的背景颜色是粉红色</td></tr></tbody></table>

<table><tbody><tr><td bgcolor="yellow" class="">这段文字的背景颜色是黄色</td></tr></tbody></table>

> 上面两个设置涉及到颜色的名称和颜色的十六进制表示，如果大家需要更多的颜色的的英文字母和颜色的十六进制表示可以进入毛毛张的这篇博客中转站进去查看：[颜色及其英文表示和十六进制表示](https://blog.csdn.net/weixin_48235955/article/details/139006735?csdn_share_tail=%7B%22type%22%3A%22blog%22%2C%22rType%22%3A%22article%22%2C%22rId%22%3A%22139006735%22%2C%22source%22%3A%22weixin_48235955%22%7D)

### 2.3 文本字号设置

> **说明：** `size`用来指定尺寸大小，数值从`1~ 6`的数字，浏览器默认值是`3`，小数也是允许的

**代码：**

**效果展示：**

这是字号 1  
这是字号 2  
这是字号 3（默认大小）  
这是字号 4  
这是字号 5  
这是字号 6  
**这是加粗文本**

### 2.4 文本字体设置

**代码：**

```
<font color = red>1.我是文本 红色red</font>
<font color = blue>2.我是文本 蓝色</font>
<font color = pink>3.我是文本 粉红</font>
<font color = purple>4.我是文本 紫色</font>
<font color = black>5.我是文本 黑色</font>
<font color = Orange>6.我是文本 橙色</font>
<font color = gray>7.我是文本 灰色</font>
<font color = green>8.我是文本 绿色</font>
<font color = #FF0000>9.我是文本 红色#FF0000</font>
```

**效果展示：**  
1. 这是楷体  
2. 这是黑体  
3. 这是微软雅黑  
4. 这是华文彩云  
5. 这是华文彩云  
6. 这是宋体  
7. 这是华文行楷  
8. 这是方正姚体  
9. 这是幼圆  
10. 这是隶书

### 2.5 实战演练

语法：`<font color=颜色 face=字体 size=字号大小> 需要显示的正文内容 </font>`

代码：

```
<table><tr><td bgcolor=pink> 这段文字的背景颜色是粉红色 </td></tr></table>
<table><tr><td bgcolor=yellow> 这段文字的背景颜色是黄色 </td></tr></table>
```

效果展示：

我是文本 楷体 5 号 红色

### 2.6 文字斜体

**快捷键：** `Ctrl + I`

**语法：** `*文本*`

**代码：**

```
<font size=1>这是字号1</font>
<font size=2>这是字号2</font>
<font size=3>这是字号3（默认大小）</font>
<font size=4>这是字号4</font>
<font size=5>这是字号5</font>
<font size=6>这是字号6</font>
<strong>这是加粗文本</strong>
```

**效果展示：**  
_字体斜体_

### 2.7 文字加粗

快捷键：`Ctrl + B`

语法： `**文本**`

代码：

```
<font face = "楷体">1.这是楷体</font>
<font face = "黑体">2.这是黑体</font>
<font face = "微软雅黑">3.这是微软雅黑</font>
<font face = "华文彩云">4.这是华文彩云</font>
<font face="STCAIYUN">5.这是华文彩云</font>
<font face="宋体">6.这是宋体</font>
<font face="华文行楷">7.这是华文行楷</font>
<font face="方正姚体">8.这是方正姚体</font>
<font face="幼圆">9.这是幼圆</font>
<font face="隶书">10.这是隶书</font>
```

效果展示：  
**这是粗体**

### 2.8 文本斜体 + 加粗

快捷键：加粗快捷键 + 斜体快捷键

快捷键：`Ctrl + B + Ctrl + I`

语法： `***文本***` 或者 `___文本___`(3 个星号或者下划短线)

```
<font color =red size = 5 face = "楷体">我是文本 楷体 5号 红色</font>
```

效果展示：

_**1. 这是一个斜体并加粗的文字**_  
_**2. 这是一个斜体并加粗的文字**_

### 2.9 文本删除线

快捷键：Alt + Shift + 5

语法：`~~文本~~`

代码：

```
*这是斜体*
```

效果展示：

~这段文字用于展示删除线的效果~

### 2.10 下划线

快捷键：`Ctrl + U`

语法：`<u>文字</u>`

```
**这是粗体**
```

效果展示：

这段文字用于展示下划线的效果

### 2.11 文本高亮

语法：`==高亮文本==`

```
***1.这是一个斜体并加粗的文字***
___2.这是一个斜体并加粗的文字___
```

效果展示：

这是一段高亮的文字

### 2.12 文本居中

> **说明：**`typora`中并没有内容居中的选项，想要居中只能使用`html`语法

语法：`<center> 居中文本 </center>`

代码：

```
~~这段文字用于展示删除线的效果~~
```

效果展示:

1. 这是一段居中显示的文本

2. 这是居中的蓝色文字

3. 这是居中的蓝色文字

> 注意：使用居中显示不能给文字添加其他效果

### 2.13 段落缩进与段落空格

语法：

*   `&emsp`：全角缩进，缩进 1 个汉字
*   `&ensp`：半角缩进，缩进 1 个英文标点
*   `&nbsp`：空格，缩进 1 个空格
*   注意：如需要多使用几个段落缩进与段落空格，就需要多打几个，并用分号`;`隔开

代码：

```
<u>这段文字用于展示下划线的效果</u>
```

实战演示：

  1. 全角缩进，相当于缩进 2 个汉字  
  2. 半角缩进，相当于缩进 2 个英文标点  
    3. 空格，缩进 4 个空格

> 下面这种方式属于 html 语言的缩进语法，在 CSDN 中不支持

  4. 这种缩进是属于 html 语言的缩进语法

### 2.14 段落换行

语法：`<br>`或`<br/>`

代码：

```
==这是一段高亮的文字==
```

效果展示：

这是第一行  
这是第二行  
这是第三行

3. 特殊格式
-------

### 3.1 标题

快捷键：`Ctrl + 数字`（数字是多少代表多少级标题，最小六级标题）

语法：`#+空格+标题名`（输入几个 #就代表几级标题，最小六级标题）

代码：如果没有显示，可以在输入完毕之后敲击一下回车键

```
<center> 1.这是一段居中显示的文本 </center>
# 下面中格式只能在Typora编辑器中支持，在CSDN编辑器中是不支持的
<p style="text-align: center; color: blue ;size:6;">2.这是居中的蓝色文字</p>
<div style="text-align: center; color: blue;">3.这是居中的蓝色文字</div>
```

效果展示：

> 这是一级标题
> ------
> 
> ### 这是二级标题
> 
> #### 这是三级标题
> 
> ##### 这是四级标题
> 
> ###### 这是五级标题
> 
> ###### 这是六级标题

### 3.2 目录

> 注意：一定要在行首输入才有效

语法：`[toc] 或者 [Toc] 或者 [TOC]`

代码：如果没有显示，可以在输入完毕之后敲击一下回车键

```
1.全角缩进，相当于缩进2个汉字
  2.半角缩进，相当于缩进2个英文标点
    3.空格，缩进4个空格
> 下面这种方式属于html语言的缩进语法，在CSDN中不支持
<p>  4.这种缩进是属于html语言的缩进语法</p>
```

效果展示：

> [toc]

### 3.3 分割线

语法：三个以上的`*`或`-`或

代码：如果没有显示，可以在输入完毕之后敲击一下回车键

```
这是第一行<br>这是第二行<br/>这是第三行
```

效果展示：

> * * *
> 
> * * *

### 3.4 跳转语法

#### 3.4.1 外部跳转

语法：`[链接跳转提示](链接网址)`

代码：`[]`中的内容可以自己重命名

```
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

效果展示：

> [百度一下](https://www.baidu.com/)

#### 3.4.2 内部跳转

> **说明：** 内部跳转即实现在文档内部，点击跳转到该标题下

语法：`[跳转提示](#要跳转的标题)`  
代码：`[]`中的内容可以自己重命名

```
@[toc]
```

效果展示：

> 需要按住 Ctrl 键再点击才能实现跳转：
> 
> [跳转语法部分标题](#3.4 跳转语法)

#### 3.4.3 自动连接

语法：<链接网址>

代码：

```
******************************
------------------------------
```

效果展示：

> [https://www.baidu.com](https://www.baidu.com/)

### 3.5 字母上标和下标

> 字母显示上标和下表需要与 Typora 的语法偏好中进行设置，并且只有正版才支持，破解版了设置了也不会显示

#### 3.5.1 设置：

*   文件→偏好设置→Markdown→Markdown 扩展语法→勾选下列选项

![](https://i-blog.csdnimg.cn/blog_migrate/1919bd0a573710a570324e484711d82e.png#pic_center)

#### 3.5.2 上标

**代码：**

```
[百度一下](https://www.baidu.com/)
```

**效果展示：**  
109  
10-1

#### 3.5.3 下标

**代码：**

```
[跳转语法部分标题](#3.4 跳转语法)
```

**效果展示：**  
MK  
H2O

#### 3.5.4 LaTex 数学公式

> 这种方式是通过数学公式的方式来显示，需要知道编辑数学公式的语法，毛毛张在这里给大家推荐一款在线公式识别网页：[simpletex](https://simpletex.cn/ai/latex_ocr)，在识别完公式之后选择复制成 LaTex 格式粘贴到 Typora 上，便可自动转化成公式。
> 
> 该软件可以对图片上的公式进行识别，并转化成你想要的格式，然后粘贴到 Typora 中。

语法：`$公式$`或`$$公式$$`，即用 1 个或者 2 个`$`进行包裹

代码：

```
<https://www.baidu.com>
```

输出显示:  
1 100 \frac {1} {100} 1001​  
M k e r n e l n M^n_{kernel} Mkerneln​

> 在数学公式中经常出现上下标，因此我们也可以通过 LaTex 数学公式来显示上下标
> 
> 语法：`$x^p_ {ij}$`
> 
> 说明：
> 
> （1）公式的编辑都在两个符号中间`$$`  
> （2）`^`符号后接的字符为上标  
> （3）`_`符号后接的字符为下标  
> （4）如果同时有两个下标，则需要使用`{}`来将符号括起来
> 
> 代码：
> 
> ```
> 10^9^
> 10^-1^
> ```
> 
> 效果展示：
> 
> x i j p x^p_{ij} xijp​

### 3.6 表格

> 在表格这一部分，毛毛张使用的不多，暂时还并没有很多使用心得，大家直接右键插入表格就感觉已经可以了，在这个里面使用表格感觉确实不是很方便

语法：`|Name | Age|`，每一列使用`|`进行隔开

设置对齐方式：`|:---: | ---:|` ，其中`:--------`表示左对齐；`:---------:`表示居中对齐；`----------:`表示右对齐

代码：

```
M~K~
H~2~O
```

效果展示：

> <table><thead><tr><th align="center">Name</th><th align="right">Age</th></tr></thead><tbody><tr><td align="center">Delta</td><td align="right">19</td></tr><tr><td align="center">Lisa</td><td align="right">21</td></tr></tbody></table>

### 3.7 引用

语法：`>+空格+引用的内容`

代码：

```
$\frac {1} {100}$
$M^n_{kernel}$
```

效果展示：

> 这是一个引用

### 3.8 无序列表

语法：`*+空格+内容`或`-+空格+内容`或`++空格+内容`

代码：

```
$x^p_{ij}$
```

效果展示：

*   这是第一种方式

*   这是第二种方式

*   这是第三种方式

> 注意：在输入上面三个符号之后需要敲击空格才会自动变成无须列表 (黑色原点)

### 3.9 有序列表

语法：`数字+.+空格`

代码：

```
|Name | Age|
|:---:| ---:|
|Delta| 19|
|Lisa | 21|
```

效果展示：

1.  数字加. 是有序列表
2.  数字的顺序不决定列表的顺序
3.  推荐 1 2 3 4 的顺序

> 注意：在输入数字加. 之后需要敲击空格才会自动变成有序列表

### 3.10 代码

快捷键：`Ctrl + Shift + K`

语法: ```` 编程语言 `

> 如果没有显示可以在输入编程语言之后敲击一下回车，如果不输入何种语言，就不用写编程语言，代码块的本质语法就是用 3 个 ` 将代码包裹，就会自动转化成对应的代码

代码：

```
> 这是一个引用
```

效果展示：

```
* 这是第一种方式
- 这是第二种方式
+ 这是第三种方式
```

> 下面就展示的是 python 代码块了，输入相应的代码，相关的关键词的颜色就会变

### 3.11 图片

语法：

*   方式 1：`![图片别名](图片地址或者图片本地存储的路径)` （Typora 默认格式）
    
*   方式 2： `<img src="图片地址或者图片本地存储的路径">`
    
    ```
    1. 数字加.是有序列表
    2. 数字的顺序不决定列表的顺序
    3. 推荐1 2 3 4 的顺序
    ```
    

> **方式 2 是使用的`html`语言，在`Typora`中是支持的，但是`CSDN`不支持完整的`html`语法，在`CSDN`中无法使用语法 2 对图片的大小进行缩放，只能对图片进行显示**

代码：这张图片的路径使用的是网络路径，大家可以直接粘贴到自己的文本上进行测试

```
```python
```

效果展示：

![](https://i-blog.csdnimg.cn/blog_migrate/7b85bfb4924d88eb5dbf9b73657dad55.jpeg)

typora 图标

![](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg)

typora 图标缩放成 30%

> 上面是图片的简单语法，下面来细说一下图片的其它相关设置

#### 3.11.1 图片题注

*   在`Typora`中没有给图片添加题注的快捷方式，只能通过人工的方式，这里毛毛张介绍两种方式

##### 1. 直接下加标题

实现：在图片下面单独添加一个居中的文本就是给图片添加题注

代码：

```
if i == 2:
    print("hello world!")
```

效果展示：图片没有居中，在下面会介绍如何居中

![](https://i-blog.csdnimg.cn/blog_migrate/ab705a83fbb8510004f09be0b5024915.jpeg)

typora 图标

##### 2. 封装型

语法：使用`html`语法

```
> 下面的图片语法在typora中全都支持的
> 语法1：
<img src="https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg"/>
> 语法2：这种语法是在typora中使用缩放快捷方式之后自动转变成的格式，但是这种格式在CSDN中进行缩放是不支持的，下面毛毛张将会介绍在CSDN中如何进行图片的缩放
<img src="https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg" alt="无法显示图片时显示的文字" style="zoom:这是写图片缩放的比例，比如:zoom:30%"/>
```

代码：

```
![typora](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg)
<center><p>typora图标</p></center>
<img src="https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg" alt="无法显示图片时显示的文字" style="zoom:30%">
<center><p>typora图标缩放成80%</p></center>
<img src="https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg" alt="无法显示图片时显示的文字" style="zoom:30%">
```

效果展示：

![](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg)  
typora 图标

> 方式 1 是简单粗暴的，直接在图片下加文字作标题；方式 2 是封装可拓展性强

#### 3.11.2 调整大小

##### 方式 1：直接设置大小 (不推荐)

**语法：在方式 1 插入图片的后面加上`#pic_center =400x100`**

```
![typora](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg)
<center><p>typora图标</p></center>
```

**注意：**

*   **这种设置只在 CSDN 博客中支持，在 Typora 中不支持**
*   **`#pic_center`表示居中，`#pic_left`表示居左，`#pic_right`表示居右，等号前面有一个空格**

代码：

```
<div>			<!--块级封装-->
    <center>	<!--将图片和文字居中-->
    <img src="图片路径放这里"
         alt="无法显示图片时显示的文字"
         style="zoom:这是写图片缩放的比例，比如:zoom:30%"/>
    <br>		<!--换行-->
    这里是图片的标题	<!--标题-->
    </center>
</div>
```

效果展示：

![](https://i-blog.csdnimg.cn/blog_migrate/90425361a107a304d1533f5f178be101.jpeg#pic_center)

typora 图标指定大小

> 这种方式不推荐，因为需要知道图片的原始大小，对于少量图片使用，但是大量图片就不适用了

##### 方式 2：按照比例进行缩放 (推荐)

**语法：在方式 1 插入图片的后面加上 `=50%x50%`**

```
<div>			<!--块级封装-->
    <center>	<!--将图片和文字居中-->
    <img src="https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg"
         alt="无法显示图片时显示的文字"
         style="zoom:30%"/>
    <br>		<!--换行-->
    typora图标	<!--标题-->
    </center>
</div>
```

**注意：**

*   **这种设置只在 CSDN 博客中支持，在 Typora 中不支持**
    
*   **等号前面有个空格，中间那个字母是英文字母`x`**
    
*   **缩放比例一样，可以忽略一部分，如 `=50%x`, 写法比较多**
    

代码：

```
图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png)
带尺寸的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png =50x50)
居中的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png#pic_center)
居中并且带尺寸的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png#pic_center =50x50)
居右的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png#pic_right)
```

效果展示：

![](https://i-blog.csdnimg.cn/blog_migrate/90425361a107a304d1533f5f178be101.jpeg#pic_center)

##### 方式 3：`<img src="路径">`（推荐）

语法：

*   **语法 1：其中 width 控制图片缩放百分比例，在 CSDN 和 Typora 中都支持**
    
    ```
    ![typora](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg#pic_center =400x200)
    <center><p>typora图标指定大小</p></center>
    ```
    
*   **语法 2：其中 zoom 控制图片缩放百分比例，仅在 Typora 中支持，Typora 的默认方式**
    
    ```
    ![图片](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg#pic_center =50%x50%)
    宽度确定高度等比例的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png =50x)(CSDN默认写法)
    宽度确定高度等比例的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png =50%x)
    高度确定宽度等比例的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png =x50)(CSDN默认写法)
    高度确定宽度等比例的图片: ![Alt](https://img-home.csdnimg.cn/images/20220524100510.png =x50%)
    ```
    

代码：

```
![typora](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg#pic_center =30%x30%)
```

效果展示：

![](https://i-blog.csdnimg.cn/blog_migrate/a07da9da460ec47b4c71281b6e37bf7f.jpeg#pic_center)

typora 图标缩放为 50%

### 3.12 彩蛋

我猜你们 `最想要` 的应该是这个吧：`对不对`

代码：

```
<img src="图片地址#pic_center" width="10%">
```

效果展示：  
`你们最想要的文字特效`

4. 特殊符号
-------

<table><thead><tr><th>符号</th><th>说明</th><th>编码</th></tr></thead><tbody><tr><td>“</td><td>双引号</td><td><code>&amp;quot;</code></td></tr><tr><td>&amp;</td><td>AND 符号</td><td><code>&amp;amp;</code></td></tr><tr><td>&lt;</td><td>小于符号</td><td><code>&amp;lt;</code></td></tr><tr><td>&gt;</td><td>大于符号</td><td><code>&amp;gt;</code></td></tr><tr><td></td><td>空格</td><td><code>&amp;nbsp;</code></td></tr><tr><td>¶</td><td>段落符号</td><td><code>&amp;para;</code></td></tr><tr><td>§</td><td>章节符号</td><td><code>&amp;sect;</code></td></tr><tr><td>©</td><td>版权所有符号</td><td><code>&amp;copy;</code></td></tr><tr><td>×</td><td>乘号</td><td><code>&amp;times;</code></td></tr><tr><td>÷</td><td>除号</td><td><code>&amp;divide;</code></td></tr><tr><td>±</td><td>正负符号</td><td><code>&amp;plusmn;</code></td></tr><tr><td>ƒ</td><td>function 符号</td><td><code>&amp;fnof;</code></td></tr><tr><td>√</td><td>根号</td><td><code>&amp;radic;</code></td></tr><tr><td>∞</td><td>无限大</td><td><code>&amp;infin;</code></td></tr><tr><td>∫</td><td>微积分符号</td><td><code>&amp;int;</code></td></tr><tr><td>≠</td><td>不等于符号</td><td><code>&amp;ne;</code></td></tr><tr><td>≡</td><td>相等符号</td><td><code>&amp;equiv;</code></td></tr><tr><td>≤</td><td>小于等于</td><td><code>&amp;le;</code></td></tr><tr><td>≥</td><td>大于等于</td><td><code>&amp;ge;</code></td></tr><tr><td>⊥</td><td>垂直符号</td><td><code>&amp;perp;</code></td></tr><tr><td>½</td><td>二分之一符号</td><td><code>&amp;frac12;</code></td></tr><tr><td>¼</td><td>四分之一符号</td><td><code>&amp;frac14;</code></td></tr><tr><td>¾</td><td>四分之三符号</td><td><code>&amp;frac34;</code></td></tr><tr><td>‰</td><td>百分符号</td><td><code>&amp;permil;</code></td></tr><tr><td>∴</td><td>所以符号</td><td><code>&amp;there4;</code></td></tr><tr><td>π</td><td>圆周率符号</td><td><code>&amp;pi;</code></td></tr><tr><td>¹</td><td>批注 1 符号</td><td><code>&amp;sup1;</code></td></tr><tr><td>²</td><td>批注 2 符号</td><td><code>&amp;sup2;</code></td></tr><tr><td>←</td><td>向左箭头</td><td><code>&amp;larr;</code></td></tr><tr><td>↑</td><td>向上箭头</td><td><code>&amp;uarr;</code></td></tr><tr><td>→</td><td>向右箭头</td><td><code>&amp;rarr;</code></td></tr><tr><td>↓</td><td>向下箭头</td><td><code>&amp;darr;</code></td></tr><tr><td>⇐</td><td>双线向左箭头</td><td><code>&amp;lArr;</code></td></tr><tr><td>⇑</td><td>双线向上箭头</td><td><code>&amp;uArr;</code></td></tr><tr><td>⇒</td><td>双线向右箭头</td><td><code>&amp;rArr;</code></td></tr><tr><td>⇓</td><td>双线向下箭头</td><td><code>&amp;dArr;</code></td></tr><tr><td>⇔</td><td>双线双向箭头</td><td><code>&amp;hArr;</code></td></tr><tr><td>♠</td><td>黑桃符号</td><td><code>&amp;spades;</code></td></tr><tr><td>♣</td><td>梅花符号</td><td><code>&amp;clubs;</code></td></tr><tr><td>♥</td><td>红心符号</td><td><code>&amp;hearts;</code></td></tr><tr><td>♦</td><td>方块符号</td><td><code>&amp;diams;</code></td></tr><tr><td>α</td><td>Alpha 符号</td><td><code>&amp;alpha;</code></td></tr><tr><td>β</td><td>Bata 符号</td><td><code>&amp;beta;</code></td></tr><tr><td>γ</td><td>Gamma 符号</td><td><code>&amp;gamma;</code></td></tr><tr><td>Δ</td><td>Delta 符号</td><td><code>&amp;Delta;</code></td></tr><tr><td>λ</td><td>Lambda 符号</td><td><code>&amp;lambda;</code></td></tr><tr><td>Σ</td><td>Sigma 符号</td><td><code>&amp;Sigma;</code></td></tr><tr><td>τ</td><td>Tau 符号</td><td><code>&amp;tau;</code></td></tr></tbody></table>

5. 内置表情
-------

> 注意：这种表情的语法比图在行首写才会起作用

**语法：**`:+表情英文名称+:`（英文冒号）

**代码：**

```
<img src="图片地址" alt="无法显示图片时显示的文字" style="zoom:30%"/>
```

效果展示：

😄

**说明：** 在使用 Typora 记笔记的过程中适当添加表情使得内容排版更加美观

![](https://i-blog.csdnimg.cn/blog_migrate/7f4541a8efcfd48259c062763d152928.png#pic_center)

> 下面列举了一些在 Typora 中可以输入的表情包，这个也是毛毛张在别的地方收录的。已经分门别类的给大家整理好了，大家可以根据自己的习惯记住一些常用的表情。

### People

<table><thead><tr><th>😄 <code>:smile:</code></th><th>😆 <code>:laughing:</code></th><th>😫 <code>:tired_face:</code></th></tr></thead><tbody><tr><td>😊 <code>:blush:</code></td><td>😃 <code>:smiley:</code></td><td>☺️ <code>:relaxed:</code></td></tr><tr><td>😏 <code>:smirk:</code></td><td>😍 <code>:heart_eyes:</code></td><td>😘 <code>:kissing_heart:</code></td></tr><tr><td>😚 <code>:kissing_closed_eyes:</code></td><td>😳 <code>:flushed:</code></td><td>😌 <code>:relieved:</code></td></tr><tr><td>😆 <code>:satisfied:</code></td><td>😁 <code>:grin:</code></td><td>😉 <code>:wink:</code></td></tr><tr><td>😜 <code>:stuck_out_tongue_winking_eye:</code></td><td>😝 <code>:stuck_out_tongue_closed_eyes:</code></td><td>😀 <code>:grinning:</code></td></tr><tr><td>😗 <code>:kissing:</code></td><td>😙 <code>:kissing_smiling_eyes:</code></td><td>😛 <code>:stuck_out_tongue:</code></td></tr><tr><td>😴 <code>:sleeping:</code></td><td>😟 <code>:worried:</code></td><td>😦 <code>:frowning:</code></td></tr><tr><td>😧 <code>:anguished:</code></td><td>😮 <code>:open_mouth:</code></td><td>😬 <code>:grimacing:</code></td></tr><tr><td>😕 <code>:confused:</code></td><td>😯 <code>:hushed:</code></td><td>😑 <code>:expressionless:</code></td></tr><tr><td>😒 <code>:unamused:</code></td><td>😅 <code>:sweat_smile:</code></td><td>😓 <code>:sweat:</code></td></tr><tr><td>😥 <code>:disappointed_relieved:</code></td><td>😩 <code>:weary:</code></td><td>😔 <code>:pensive:</code></td></tr><tr><td>😞 <code>:disappointed:</code></td><td>😖 <code>:confounded:</code></td><td>😨 <code>:fearful:</code></td></tr><tr><td>😰 <code>:cold_sweat:</code></td><td>😣 <code>:persevere:</code></td><td>😢 <code>:cry:</code></td></tr><tr><td>😭 <code>:sob:</code></td><td>😂 <code>:joy:</code></td><td>😲 <code>:astonished:</code></td></tr><tr><td>😱 <code>:scream:</code></td><td></td><td></td></tr><tr><td>😠 <code>:angry:</code></td><td>😡 <code>:rage:</code></td><td>😤 <code>:triumph:</code></td></tr><tr><td>😪 <code>:sleepy:</code></td><td>😋 <code>:yum:</code></td><td>😷 <code>:mask:</code></td></tr><tr><td>😎 <code>:sunglasses:</code></td><td>😵 <code>:dizzy_face:</code></td><td>👿 <code>:imp:</code></td></tr><tr><td>😈 <code>:smiling_imp:</code></td><td>😐 <code>:neutral_face:</code></td><td>😶 <code>:no_mouth:</code></td></tr><tr><td>😇 <code>:innocent:</code></td><td>👽 <code>:alien:</code></td><td>💛 <code>:yellow_heart:</code></td></tr><tr><td>💙 <code>:blue_heart:</code></td><td>💜 <code>:purple_heart:</code></td><td>❤️ <code>:heart:</code></td></tr><tr><td>💚 <code>:green_heart:</code></td><td>💔 <code>:broken_heart:</code></td><td>💓 <code>:heartbeat:</code></td></tr><tr><td>💗 <code>:heartpulse:</code></td><td>💕 <code>:two_hearts:</code></td><td>💞 <code>:revolving_hearts:</code></td></tr><tr><td>💘 <code>:cupid:</code></td><td>💖 <code>:sparkling_heart:</code></td><td>✨ <code>:sparkles:</code></td></tr><tr><td>⭐️ <code>:star:</code></td><td>🌟 <code>:star2:</code></td><td>💫 <code>:dizzy:</code></td></tr><tr><td>💥 <code>:boom:</code></td><td>💥 <code>:collision:</code></td><td>💢 <code>:anger:</code></td></tr><tr><td>❗️ <code>:exclamation:</code></td><td>❓ <code>:question:</code></td><td>❕ <code>:grey_exclamation:</code></td></tr><tr><td>❔ <code>:grey_question:</code></td><td>💤 <code>:zzz:</code></td><td>💨 <code>:dash:</code></td></tr><tr><td>💦 <code>:sweat_drops:</code></td><td>🎶 <code>:notes:</code></td><td>🎵 <code>:musical_note:</code></td></tr><tr><td>🔥 <code>:fire:</code></td><td>💩 <code>:hankey:</code></td><td>💩 <code>:poop:</code></td></tr><tr><td>💩 <code>:shit:</code></td><td>👍 <code>:+1:</code></td><td>👍 <code>:thumbsup:</code></td></tr><tr><td>👎 <code>:-1:</code></td><td>👎 <code>:thumbsdown:</code></td><td>👌 <code>:ok_hand:</code></td></tr><tr><td>👊 <code>:punch:</code></td><td>👊 <code>:facepunch:</code></td><td>✊ <code>:fist:</code></td></tr><tr><td>✌️ <code>:v:</code></td><td>👋 <code>:wave:</code></td><td>✋ <code>:hand:</code></td></tr><tr><td>✋ <code>:raised_hand:</code></td><td>👐 <code>:open_hands:</code></td><td>☝️ <code>:point_up:</code></td></tr><tr><td>👇 <code>:point_down:</code></td><td>👈 <code>:point_left:</code></td><td>👉 <code>:point_right:</code></td></tr><tr><td>🙌 <code>:raised_hands:</code></td><td>🙏 <code>:pray:</code></td><td>👆 <code>:point_up_2:</code></td></tr><tr><td>👏 <code>:clap:</code></td><td>💪 <code>:muscle:</code></td><td>🤘 <code>:metal:</code></td></tr><tr><td>🖕 <code>:fu:</code></td><td>🚶 <code>:walking:</code></td><td>🏃 <code>:runner:</code></td></tr><tr><td>🏃 <code>:running:</code></td><td>👫 <code>:couple:</code></td><td>👪 <code>:family:</code></td></tr><tr><td>👬 <code>:two_men_holding_hands:</code></td><td>👭 <code>:two_women_holding_hands:</code></td><td>💃 <code>:dancer:</code></td></tr><tr><td>👯 <code>:dancers:</code></td><td>🙆 <code>:ok_woman:</code></td><td>🙅 <code>:no_good:</code></td></tr><tr><td>💁 <code>:information_desk_person:</code></td><td>🙋 <code>:raising_hand:</code></td><td>👰 <code>:bride_with_veil:</code></td></tr><tr><td>🙎 <code>:person_with_pouting_face:</code></td><td>🙍 <code>:person_frowning:</code></td><td>🙇 <code>:bow:</code></td></tr><tr><td>:couplekiss: <code>:couplekiss:</code></td><td>💑 <code>:couple_with_heart:</code></td><td>💆 <code>:massage:</code></td></tr><tr><td>💇 <code>:haircut:</code></td><td>💅 <code>:nail_care:</code></td><td>👦 <code>:boy:</code></td></tr><tr><td>👧 <code>:girl:</code></td><td>👩 <code>:woman:</code></td><td>👨 <code>:man:</code></td></tr><tr><td>👶 <code>:baby:</code></td><td>👵 <code>:older_woman:</code></td><td>👴 <code>:older_man:</code></td></tr><tr><td>👱 <code>:person_with_blond_hair:</code></td><td>👲 <code>:man_with_gua_pi_mao:</code></td><td>👳 <code>:man_with_turban:</code></td></tr><tr><td>👷 <code>:construction_worker:</code></td><td>👮 <code>:cop:</code></td><td>👼 <code>:angel:</code></td></tr><tr><td>👸 <code>:princess:</code></td><td>😺 <code>:smiley_cat:</code></td><td>😸 <code>:smile_cat:</code></td></tr><tr><td>😻 <code>:heart_eyes_cat:</code></td><td>😽 <code>:kissing_cat:</code></td><td>😼 <code>:smirk_cat:</code></td></tr><tr><td>🙀 <code>:scream_cat:</code></td><td>😿 <code>:crying_cat_face:</code></td><td>😹 <code>:joy_cat:</code></td></tr><tr><td>😾 <code>:pouting_cat:</code></td><td>👹 <code>:japanese_ogre:</code></td><td>👺 <code>:japanese_goblin:</code></td></tr><tr><td>🙈 <code>:see_no_evil:</code></td><td>🙉 <code>:hear_no_evil:</code></td><td>🙊 <code>:speak_no_evil:</code></td></tr><tr><td>💂 <code>:guardsman:</code></td><td>💀 <code>:skull:</code></td><td>🐾 <code>:feet:</code></td></tr><tr><td>👄 <code>:lips:</code></td><td>💋 <code>:kiss:</code></td><td>💧 <code>:droplet:</code></td></tr><tr><td>👂 <code>:ear:</code></td><td>👀 <code>:eyes:</code></td><td>👃 <code>:nose:</code></td></tr><tr><td>👅 <code>:tongue:</code></td><td>💌 <code>:love_letter:</code></td><td>👤 <code>:bust_in_silhouette:</code></td></tr><tr><td>👥 <code>:busts_in_silhouette:</code></td><td>💬 <code>:speech_balloon:</code></td><td>💭 <code>:thought_balloon:</code></td></tr></tbody></table>

### Nature

<table><thead><tr><th>☀️ <code>:sunny:</code></th><th>☔️ <code>:umbrella:</code></th><th>☁️ <code>:cloud:</code></th></tr></thead><tbody><tr><td>❄️ <code>:snowflake:</code></td><td>⛄️ <code>:snowman:</code></td><td>⚡️ <code>:zap:</code></td></tr><tr><td>🌀 <code>:cyclone:</code></td><td>🌁 <code>:foggy:</code></td><td>🌊 <code>:ocean:</code></td></tr><tr><td>🐱 <code>:cat:</code></td><td>🐶 <code>:dog:</code></td><td>🐭 <code>:mouse:</code></td></tr><tr><td>🐹 <code>:hamster:</code></td><td>🐰 <code>:rabbit:</code></td><td>🐺 <code>:wolf:</code></td></tr><tr><td>🐸 <code>:frog:</code></td><td>🐯 <code>:tiger:</code></td><td>🐨 <code>:koala:</code></td></tr><tr><td>🐻 <code>:bear:</code></td><td>🐷 <code>:pig:</code></td><td>🐽 <code>:pig_nose:</code></td></tr><tr><td>🐮 <code>:cow:</code></td><td>🐗 <code>:boar:</code></td><td>🐵 <code>:monkey_face:</code></td></tr><tr><td>🐒 <code>:monkey:</code></td><td>🐴 <code>:horse:</code></td><td>🐎 <code>:racehorse:</code></td></tr><tr><td>🐫 <code>:camel:</code></td><td>🐑 <code>:sheep:</code></td><td>🐘 <code>:elephant:</code></td></tr><tr><td>🐼 <code>:panda_face:</code></td><td>🐍 <code>:snake:</code></td><td>🐦 <code>:bird:</code></td></tr><tr><td>🐤 <code>:baby_chick:</code></td><td>🐥 <code>:hatched_chick:</code></td><td>🐣 <code>:hatching_chick:</code></td></tr><tr><td>🐔 <code>:chicken:</code></td><td>🐧 <code>:penguin:</code></td><td>🐢 <code>:turtle:</code></td></tr><tr><td>🐛 <code>:bug:</code></td><td>🐝 <code>:honeybee:</code></td><td>🐜 <code>:ant:</code></td></tr><tr><td>🐞 <code>:beetle:</code></td><td>🐌 <code>:snail:</code></td><td>🐙 <code>:octopus:</code></td></tr><tr><td>🐠 <code>:tropical_fish:</code></td><td>🐟 <code>:fish:</code></td><td>🐳 <code>:whale:</code></td></tr><tr><td>🐋 <code>:whale2:</code></td><td>🐬 <code>:dolphin:</code></td><td>🐄 <code>:cow2:</code></td></tr><tr><td>🐏 <code>:ram:</code></td><td>🐀 <code>:rat:</code></td><td>🐃 <code>:water_buffalo:</code></td></tr><tr><td>🐅 <code>:tiger2:</code></td><td>🐇 <code>:rabbit2:</code></td><td>🐉 <code>:dragon:</code></td></tr><tr><td>🐐 <code>:goat:</code></td><td>🐓 <code>:rooster:</code></td><td>🐕 <code>:dog2:</code></td></tr><tr><td>🐖 <code>:pig2:</code></td><td>🐁 <code>:mouse2:</code></td><td>🐂 <code>:ox:</code></td></tr><tr><td>🐲 <code>:dragon_face:</code></td><td>🐡 <code>:blowfish:</code></td><td>🐊 <code>:crocodile:</code></td></tr><tr><td>🐪 <code>:dromedary_camel:</code></td><td>🐆 <code>:leopard:</code></td><td>🐈 <code>:cat2:</code></td></tr><tr><td>🐩 <code>:poodle:</code></td><td>🐾 <code>:paw_prints:</code></td><td>💐 <code>:bouquet:</code></td></tr><tr><td>🌸 <code>:cherry_blossom:</code></td><td>🌷 <code>:tulip:</code></td><td>🍀 <code>:four_leaf_clover:</code></td></tr><tr><td>🌹 <code>:rose:</code></td><td>🌻 <code>:sunflower:</code></td><td>🌺 <code>:hibiscus:</code></td></tr><tr><td>🍁 <code>:maple_leaf:</code></td><td>🍃 <code>:leaves:</code></td><td>🍂 <code>:fallen_leaf:</code></td></tr><tr><td>🌿 <code>:herb:</code></td><td>🍄 <code>:mushroom:</code></td><td>🌵 <code>:cactus:</code></td></tr><tr><td>🌴 <code>:palm_tree:</code></td><td>🌲 <code>:evergreen_tree:</code></td><td>🌳 <code>:deciduous_tree:</code></td></tr><tr><td>🌰 <code>:chestnut:</code></td><td>🌱 <code>:seedling:</code></td><td>🌼 <code>:blossom:</code></td></tr><tr><td>🌾 <code>:ear_of_rice:</code></td><td>🐚 <code>:shell:</code></td><td>🌐 <code>:globe_with_meridians:</code></td></tr><tr><td>🌞 <code>:sun_with_face:</code></td><td>🌝 <code>:full_moon_with_face:</code></td><td>🌚 <code>:new_moon_with_face:</code></td></tr><tr><td>🌑 <code>:new_moon:</code></td><td>🌒 <code>:waxing_crescent_moon:</code></td><td>🌓 <code>:first_quarter_moon:</code></td></tr><tr><td>🌔 <code>:waxing_gibbous_moon:</code></td><td>🌕 <code>:full_moon:</code></td><td>🌖 <code>:waning_gibbous_moon:</code></td></tr><tr><td>🌗 <code>:last_quarter_moon:</code></td><td>🌘 <code>:waning_crescent_moon:</code></td><td>🌜 <code>:last_quarter_moon_with_face:</code></td></tr><tr><td>🌛 <code>:first_quarter_moon_with_face:</code></td><td>🌔 <code>:moon:</code></td><td>🌍 <code>:earth_africa:</code></td></tr><tr><td>🌎 <code>:earth_americas:</code></td><td>🌏 <code>:earth_asia:</code></td><td>🌋 <code>:volcano:</code></td></tr><tr><td>🌌 <code>:milky_way:</code></td><td>⛅️ <code>:partly_sunny:</code></td><td></td></tr></tbody></table>

### Object

<table><thead><tr><th>🎍 <code>:bamboo:</code></th><th>💝 <code>:gift_heart:</code></th><th>🎎 <code>:dolls:</code></th></tr></thead><tbody><tr><td>🎒 <code>:school_satchel:</code></td><td>🎓 <code>:mortar_board:</code></td><td>🎏 <code>:flags:</code></td></tr><tr><td>🎆 <code>:fireworks:</code></td><td>🎇 <code>:sparkler:</code></td><td>🎐 <code>:wind_chime:</code></td></tr><tr><td>🎑 <code>:rice_scene:</code></td><td>🎃 <code>:jack_o_lantern:</code></td><td>👻 <code>:ghost:</code></td></tr><tr><td>🎅 <code>:santa:</code></td><td>🎄 <code>:christmas_tree:</code></td><td>🎁 <code>:gift:</code></td></tr><tr><td>🔔 <code>:bell:</code></td><td>🔕 <code>:no_bell:</code></td><td>🎋 <code>:tanabata_tree:</code></td></tr><tr><td>🎉 <code>:tada:</code></td><td>🎊 <code>:confetti_ball:</code></td><td>🎈 <code>:balloon:</code></td></tr><tr><td>🔮 <code>:crystal_ball:</code></td><td>💿 <code>:cd:</code></td><td>📀 <code>:dvd:</code></td></tr><tr><td>💾 <code>:floppy_disk:</code></td><td>📷 <code>:camera:</code></td><td>📹 <code>:video_camera:</code></td></tr><tr><td>🎥 <code>:movie_camera:</code></td><td>💻 <code>:computer:</code></td><td>📺 <code>:tv:</code></td></tr><tr><td>📱 <code>:iphone:</code></td><td>☎️ <code>:phone:</code></td><td>☎️ <code>:telephone:</code></td></tr><tr><td>📞 <code>:telephone_receiver:</code></td><td>📟 <code>:pager:</code></td><td>📠 <code>:fax:</code></td></tr><tr><td>💽 <code>:minidisc:</code></td><td>📼 <code>:vhs:</code></td><td>🔉 <code>:sound:</code></td></tr><tr><td>🔈 <code>:speaker:</code></td><td>🔇 <code>:mute:</code></td><td>📢 <code>:loudspeaker:</code></td></tr><tr><td>📣 <code>:mega:</code></td><td>⌛️ <code>:hourglass:</code></td><td>⏳ <code>:hourglass_flowing_sand:</code></td></tr><tr><td>⏰ <code>:alarm_clock:</code></td><td>⌚️ <code>:watch:</code></td><td>📻 <code>:radio:</code></td></tr><tr><td>📡 <code>:satellite:</code></td><td>➿ <code>:loop:</code></td><td>🔍 <code>:mag:</code></td></tr><tr><td>🔎 <code>:mag_right:</code></td><td>🔓 <code>:unlock:</code></td><td>🔒 <code>:lock:</code></td></tr><tr><td>🔏 <code>:lock_with_ink_pen:</code></td><td>🔐 <code>:closed_lock_with_key:</code></td><td>🔑 <code>:key:</code></td></tr><tr><td>💡 <code>:bulb:</code></td><td>🔦 <code>:flashlight:</code></td><td>🔆 <code>:high_brightness:</code></td></tr><tr><td>🔅 <code>:low_brightness:</code></td><td>🔌 <code>:electric_plug:</code></td><td>🔋 <code>:battery:</code></td></tr><tr><td>📲 <code>:calling:</code></td><td>✉️ <code>:email:</code></td><td>📫 <code>:mailbox:</code></td></tr><tr><td>📮 <code>:postbox:</code></td><td>🛀 <code>:bath:</code></td><td>🛁 <code>:bathtub:</code></td></tr><tr><td>🚿 <code>:shower:</code></td><td>🚽 <code>:toilet:</code></td><td>🔧 <code>:wrench:</code></td></tr><tr><td>🔩 <code>:nut_and_bolt:</code></td><td>🔨 <code>:hammer:</code></td><td>💺 <code>:seat:</code></td></tr><tr><td>💰 <code>:moneybag:</code></td><td>💴 <code>:yen:</code></td><td>💵 <code>:dollar:</code></td></tr><tr><td>💷 <code>:pound:</code></td><td>💶 <code>:euro:</code></td><td>💳 <code>:credit_card:</code></td></tr><tr><td>💸 <code>:money_with_wings:</code></td><td>📧 <code>:e-mail:</code></td><td>📥 <code>:inbox_tray:</code></td></tr><tr><td>📤 <code>:outbox_tray:</code></td><td>✉️ <code>:envelope:</code></td><td>📨 <code>:incoming_envelope:</code></td></tr><tr><td>📯 <code>:postal_horn:</code></td><td>📪 <code>:mailbox_closed:</code></td><td>📬 <code>:mailbox_with_mail:</code></td></tr><tr><td>📭 <code>:mailbox_with_no_mail:</code></td><td>🚪 <code>:door:</code></td><td>🚬 <code>:smoking:</code></td></tr><tr><td>💣 <code>:bomb:</code></td><td>🔫 <code>:gun:</code></td><td>🔪 <code>:hocho:</code></td></tr><tr><td>💊 <code>:pill:</code></td><td>💉 <code>:syringe:</code></td><td>📄 <code>:page_facing_up:</code></td></tr><tr><td>📃 <code>:page_with_curl:</code></td><td>📑 <code>:bookmark_tabs:</code></td><td>📊 <code>:bar_chart:</code></td></tr><tr><td>📈 <code>:chart_with_upwards_trend:</code></td><td>📉 <code>:chart_with_downwards_trend:</code></td><td>📜 <code>:scroll:</code></td></tr><tr><td>📋 <code>:clipboard:</code></td><td>📆 <code>:calendar:</code></td><td>📅 <code>:date:</code></td></tr><tr><td>📇 <code>:card_index:</code></td><td>📁 <code>:file_folder:</code></td><td>📂 <code>:open_file_folder:</code></td></tr><tr><td>✂️ <code>:scissors:</code></td><td>📌 <code>:pushpin:</code></td><td>📎 <code>:paperclip:</code></td></tr><tr><td>✒️ <code>:black_nib:</code></td><td>✏️ <code>:pencil2:</code></td><td>📏 <code>:straight_ruler:</code></td></tr><tr><td>📐 <code>:triangular_ruler:</code></td><td>📕 <code>:closed_book:</code></td><td>📗 <code>:green_book:</code></td></tr><tr><td>📘 <code>:blue_book:</code></td><td>📙 <code>:orange_book:</code></td><td>📓 <code>:notebook:</code></td></tr><tr><td>📔 <code>:notebook_with_decorative_cover:</code></td><td>📒 <code>:ledger:</code></td><td>📚 <code>:books:</code></td></tr><tr><td>🔖 <code>:bookmark:</code></td><td>📛 <code>:name_badge:</code></td><td>🔬 <code>:microscope:</code></td></tr><tr><td>🔭 <code>:telescope:</code></td><td>📰 <code>:newspaper:</code></td><td>🏈 <code>:football:</code></td></tr><tr><td>🏀 <code>:basketball:</code></td><td>⚽️ <code>:soccer:</code></td><td>⚾️ <code>:baseball:</code></td></tr><tr><td>🎾 <code>:tennis:</code></td><td>🎱 <code>:8ball:</code></td><td>🏉 <code>:rugby_football:</code></td></tr><tr><td>🎳 <code>:bowling:</code></td><td>⛳️ <code>:golf:</code></td><td>🚵 <code>:mountain_bicyclist:</code></td></tr><tr><td>🚴 <code>:bicyclist:</code></td><td>🏇 <code>:horse_racing:</code></td><td>🏂 <code>:snowboarder:</code></td></tr><tr><td>🏊 <code>:swimmer:</code></td><td>🏄 <code>:surfer:</code></td><td>🎿 <code>:ski:</code></td></tr><tr><td>♠️ <code>:spades:</code></td><td>♥️ <code>:hearts:</code></td><td>♣️ <code>:clubs:</code></td></tr><tr><td>♦️ <code>:diamonds:</code></td><td>💎 <code>:gem:</code></td><td>💍 <code>:ring:</code></td></tr><tr><td>🏆 <code>:trophy:</code></td><td>🎼 <code>:musical_score:</code></td><td>🎹 <code>:musical_keyboard:</code></td></tr><tr><td>🎻 <code>:violin:</code></td><td>👾 <code>:space_invader:</code></td><td>🎮 <code>:video_game:</code></td></tr><tr><td>🃏 <code>:black_joker:</code></td><td>🎴 <code>:flower_playing_cards:</code></td><td>🎲 <code>:game_die:</code></td></tr><tr><td>🎯 <code>:dart:</code></td><td>🀄️ <code>:mahjong:</code></td><td>🎬 <code>:clapper:</code></td></tr><tr><td>📝 <code>:memo:</code></td><td>📝 <code>:pencil:</code></td><td>📖 <code>:book:</code></td></tr><tr><td>🎨 <code>:art:</code></td><td>🎤 <code>:microphone:</code></td><td>🎧 <code>:headphones:</code></td></tr><tr><td>🎺 <code>:trumpet:</code></td><td>🎷 <code>:saxophone:</code></td><td>🎸 <code>:guitar:</code></td></tr><tr><td>👞 <code>:shoe:</code></td><td>👡 <code>:sandal:</code></td><td>👠 <code>:high_heel:</code></td></tr><tr><td>💄 <code>:lipstick:</code></td><td>👢 <code>:boot:</code></td><td>👕 <code>:shirt:</code></td></tr><tr><td>👕 <code>:tshirt:</code></td><td>👔 <code>:necktie:</code></td><td>👚 <code>:womans_clothes:</code></td></tr><tr><td>👗 <code>:dress:</code></td><td>🎽 <code>:running_shirt_with_sash:</code></td><td>👖 <code>:jeans:</code></td></tr><tr><td>👘 <code>:kimono:</code></td><td>👙 <code>:bikini:</code></td><td>🎀 <code>:ribbon:</code></td></tr><tr><td>🎩 <code>:tophat:</code></td><td>👑 <code>:crown:</code></td><td>👒 <code>:womans_hat:</code></td></tr><tr><td>👞 <code>:mans_shoe:</code></td><td>🌂 <code>:closed_umbrella:</code></td><td>💼 <code>:briefcase:</code></td></tr><tr><td>👜 <code>:handbag:</code></td><td>👝 <code>:pouch:</code></td><td>👛 <code>:purse:</code></td></tr><tr><td>👓 <code>:eyeglasses:</code></td><td>🎣 <code>:fishing_pole_and_fish:</code></td><td>☕️ <code>:coffee:</code></td></tr><tr><td>🍵 <code>:tea:</code></td><td>🍶 <code>:sake:</code></td><td>🍼 <code>:baby_bottle:</code></td></tr><tr><td>🍺 <code>:beer:</code></td><td>🍻 <code>:beers:</code></td><td>🍸 <code>:cocktail:</code></td></tr><tr><td>🍹 <code>:tropical_drink:</code></td><td>🍷 <code>:wine_glass:</code></td><td>🍴 <code>:fork_and_knife:</code></td></tr><tr><td>🍕 <code>:pizza:</code></td><td>🍔 <code>:hamburger:</code></td><td>🍟 <code>:fries:</code></td></tr><tr><td>🍗 <code>:poultry_leg:</code></td><td>🍖 <code>:meat_on_bone:</code></td><td>🍝 <code>:spaghetti:</code></td></tr><tr><td>🍛 <code>:curry:</code></td><td>🍤 <code>:fried_shrimp:</code></td><td>🍱 <code>:bento:</code></td></tr><tr><td>🍣 <code>:sushi:</code></td><td>🍥 <code>:fish_cake:</code></td><td>🍙 <code>:rice_ball:</code></td></tr><tr><td>🍘 <code>:rice_cracker:</code></td><td>🍚 <code>:rice:</code></td><td>🍜 <code>:ramen:</code></td></tr><tr><td>🍲 <code>:stew:</code></td><td>🍢 <code>:oden:</code></td><td>🍡 <code>:dango:</code></td></tr><tr><td>🥚 <code>:egg:</code></td><td>🍞 <code>:bread:</code></td><td>🍩 <code>:doughnut:</code></td></tr><tr><td>🍮 <code>:custard:</code></td><td>🍦 <code>:icecream:</code></td><td>🍨 <code>:ice_cream:</code></td></tr><tr><td>🍧 <code>:shaved_ice:</code></td><td>🎂 <code>:birthday:</code></td><td>🍰 <code>:cake:</code></td></tr><tr><td>🍪 <code>:cookie:</code></td><td>🍫 <code>:chocolate_bar:</code></td><td>🍬 <code>:candy:</code></td></tr><tr><td>🍭 <code>:lollipop:</code></td><td>🍯 <code>:honey_pot:</code></td><td>🍎 <code>:apple:</code></td></tr><tr><td>🍏 <code>:green_apple:</code></td><td>🍊 <code>:tangerine:</code></td><td>🍋 <code>:lemon:</code></td></tr><tr><td>🍒 <code>:cherries:</code></td><td>🍇 <code>:grapes:</code></td><td>🍉 <code>:watermelon:</code></td></tr><tr><td>🍓 <code>:strawberry:</code></td><td>🍑 <code>:peach:</code></td><td>🍈 <code>:melon:</code></td></tr><tr><td>🍌 <code>:banana:</code></td><td>🍐 <code>:pear:</code></td><td>🍍 <code>:pineapple:</code></td></tr><tr><td>🍠 <code>:sweet_potato:</code></td><td>🍆 <code>:eggplant:</code></td><td>🍅 <code>:tomato:</code></td></tr><tr><td>🌽 <code>:corn:</code></td><td></td><td></td></tr></tbody></table>

### Places

<table><thead><tr><th>🏠 <code>:house:</code></th><th>🏡 <code>:house_with_garden:</code></th><th>🏫 <code>:school:</code></th></tr></thead><tbody><tr><td>🏢 <code>:office:</code></td><td>🏣 <code>:post_office:</code></td><td>🏥 <code>:hospital:</code></td></tr><tr><td>🏦 <code>:bank:</code></td><td>🏪 <code>:convenience_store:</code></td><td>🏩 <code>:love_hotel:</code></td></tr><tr><td>🏨 <code>:hotel:</code></td><td>💒 <code>:wedding:</code></td><td>⛪️ <code>:church:</code></td></tr><tr><td>🏬 <code>:department_store:</code></td><td>🏤 <code>:european_post_office:</code></td><td>🌇 <code>:city_sunrise:</code></td></tr><tr><td>🌆 <code>:city_sunset:</code></td><td>🏯 <code>:japanese_castle:</code></td><td>🏰 <code>:european_castle:</code></td></tr><tr><td>⛺️ <code>:tent:</code></td><td>🏭 <code>:factory:</code></td><td>🗼 <code>:tokyo_tower:</code></td></tr><tr><td>🗾 <code>:japan:</code></td><td>🗻 <code>:mount_fuji:</code></td><td>🌄 <code>:sunrise_over_mountains:</code></td></tr><tr><td>🌅 <code>:sunrise:</code></td><td>🌠 <code>:stars:</code></td><td>🗽 <code>:statue_of_liberty:</code></td></tr><tr><td>🌉 <code>:bridge_at_night:</code></td><td>🎠 <code>:carousel_horse:</code></td><td>🌈 <code>:rainbow:</code></td></tr><tr><td>🎡 <code>:ferris_wheel:</code></td><td>⛲️ <code>:fountain:</code></td><td>🎢 <code>:roller_coaster:</code></td></tr><tr><td>🚢 <code>:ship:</code></td><td>🚤 <code>:speedboat:</code></td><td>⛵️ <code>:boat:</code></td></tr><tr><td>⛵️ <code>:sailboat:</code></td><td>🚣 <code>:rowboat:</code></td><td>⚓️ <code>:anchor:</code></td></tr><tr><td>🚀 <code>:rocket:</code></td><td>✈️ <code>:airplane:</code></td><td>🚁 <code>:helicopter:</code></td></tr><tr><td>🚂 <code>:steam_locomotive:</code></td><td>🚊 <code>:tram:</code></td><td>🚞 <code>:mountain_railway:</code></td></tr><tr><td>🚲 <code>:bike:</code></td><td>🚡 <code>:aerial_tramway:</code></td><td>🚟 <code>:suspension_railway:</code></td></tr><tr><td>🚠 <code>:mountain_cableway:</code></td><td>🚜 <code>:tractor:</code></td><td>🚙 <code>:blue_car:</code></td></tr><tr><td>🚘 <code>:oncoming_automobile:</code></td><td>🚗 <code>:car:</code></td><td>🚗 <code>:red_car:</code></td></tr><tr><td>🚕 <code>:taxi:</code></td><td>🚖 <code>:oncoming_taxi:</code></td><td>🚛 <code>:articulated_lorry:</code></td></tr><tr><td>🚌 <code>:bus:</code></td><td>🚍 <code>:oncoming_bus:</code></td><td>🚨 <code>:rotating_light:</code></td></tr><tr><td>🚓 <code>:police_car:</code></td><td>🚔 <code>:oncoming_police_car:</code></td><td>🚒 <code>:fire_engine:</code></td></tr><tr><td>🚑 <code>:ambulance:</code></td><td>🚐 <code>:minibus:</code></td><td>🚚 <code>:truck:</code></td></tr><tr><td>🚋 <code>:train:</code></td><td>🚉 <code>:station:</code></td><td>🚆 <code>:train2:</code></td></tr><tr><td>🚅 <code>:bullettrain_front:</code></td><td>🚄 <code>:bullettrain_side:</code></td><td>🚈 <code>:light_rail:</code></td></tr><tr><td>🚝 <code>:monorail:</code></td><td>🚃 <code>:railway_car:</code></td><td>🚎 <code>:trolleybus:</code></td></tr><tr><td>🎫 <code>:ticket:</code></td><td>⛽️ <code>:fuelpump:</code></td><td>🚦 <code>:vertical_traffic_light:</code></td></tr><tr><td>🚥 <code>:traffic_light:</code></td><td>⚠️ <code>:warning:</code></td><td>🚧 <code>:construction:</code></td></tr><tr><td>🔰 <code>:beginner:</code></td><td>🏧 <code>:atm:</code></td><td>🎰 <code>:slot_machine:</code></td></tr><tr><td>🚏 <code>:busstop:</code></td><td>💈 <code>:barber:</code></td><td>♨️ <code>:hotsprings:</code></td></tr><tr><td>🏁 <code>:checkered_flag:</code></td><td>🎌 <code>:crossed_flags:</code></td><td>🏮 <code>:izakaya_lantern:</code></td></tr><tr><td>🗿 <code>:moyai:</code></td><td>🎪 <code>:circus_tent:</code></td><td>🎭 <code>:performing_arts:</code></td></tr><tr><td>📍 <code>:round_pushpin:</code></td><td>🚩 <code>:triangular_flag_on_post:</code></td><td>🇯🇵 <code>:jp:</code></td></tr><tr><td>🇰🇷 <code>:kr:</code></td><td>🇨🇳 <code>:cn:</code></td><td>🇺🇸 <code>:us:</code></td></tr><tr><td>🇫🇷 <code>:fr:</code></td><td>🇪🇸 <code>:es:</code></td><td>🇮🇹 <code>:it:</code></td></tr><tr><td>🇷🇺 <code>:ru:</code></td><td>🇬🇧 <code>:gb:</code></td><td>🇬🇧 <code>:uk:</code></td></tr><tr><td>🇩🇪 <code>:de:</code></td><td></td><td></td></tr></tbody></table>

### Symbols

<table><thead><tr><th>1️⃣ <code>:one:</code></th><th>2️⃣ <code>:two:</code></th><th>3️⃣ <code>:three:</code></th></tr></thead><tbody><tr><td>4️⃣ <code>:four:</code></td><td>5️⃣ <code>:five:</code></td><td>6️⃣ <code>:six:</code></td></tr><tr><td>7️⃣ <code>:seven:</code></td><td>8️⃣ <code>:eight:</code></td><td>9️⃣ <code>:nine:</code></td></tr><tr><td>🔟 <code>:keycap_ten:</code></td><td>🔢 <code>:1234:</code></td><td>0️⃣ <code>:zero:</code></td></tr><tr><td>#️⃣ <code>:hash:</code></td><td>🔣 <code>:symbols:</code></td><td>◀️ <code>:arrow_backward:</code></td></tr><tr><td>⬇️ <code>:arrow_down:</code></td><td>▶️ <code>:arrow_forward:</code></td><td>⬅️ <code>:arrow_left:</code></td></tr><tr><td>🔠 <code>:capital_abcd:</code></td><td>🔡 <code>:abcd:</code></td><td>🔤 <code>:abc:</code></td></tr><tr><td>↙️ <code>:arrow_lower_left:</code></td><td>↘️ <code>:arrow_lower_right:</code></td><td>➡️ <code>:arrow_right:</code></td></tr><tr><td>⬆️ <code>:arrow_up:</code></td><td>↖️ <code>:arrow_upper_left:</code></td><td>↗️ <code>:arrow_upper_right:</code></td></tr><tr><td>⏬ <code>:arrow_double_down:</code></td><td>⏫ <code>:arrow_double_up:</code></td><td>🔽 <code>:arrow_down_small:</code></td></tr><tr><td>⤵️ <code>:arrow_heading_down:</code></td><td>⤴️ <code>:arrow_heading_up:</code></td><td>↩️<code>:leftwards_arrow_with_hook:</code></td></tr><tr><td>↪️ <code>:arrow_right_hook:</code></td><td>↔️ <code>:left_right_arrow:</code></td><td>↕️ <code>:arrow_up_down:</code></td></tr><tr><td>🔼 <code>:arrow_up_small:</code></td><td>🔃 <code>:arrows_clockwise:</code></td><td>🔄 <code>:arrows_counterclockwise:</code></td></tr><tr><td>⏪ <code>:rewind:</code></td><td>⏩ <code>:fast_forward:</code></td><td>ℹ️ <code>:information_source:</code></td></tr><tr><td>🆗 <code>:ok:</code></td><td>🔀 <code>:twisted_rightwards_arrows:</code></td><td>🔁 <code>:repeat:</code></td></tr><tr><td>🔂 <code>:repeat_one:</code></td><td>🆕 <code>:new:</code></td><td>🔝 <code>:top:</code></td></tr><tr><td>🆙 <code>:up:</code></td><td>🆒 <code>:cool:</code></td><td>🆓 <code>:free:</code></td></tr><tr><td>🆖 <code>:ng:</code></td><td>🎦 <code>:cinema:</code></td><td>🈁 <code>:koko:</code></td></tr><tr><td>📶 <code>:signal_strength:</code></td><td>🈹 <code>:u5272:</code></td><td>🈴 <code>:u5408:</code></td></tr><tr><td>🈺 <code>:u55b6:</code></td><td>🈯️ <code>:u6307:</code></td><td>🈷️ <code>:u6708:</code></td></tr><tr><td>🈶 <code>:u6709:</code></td><td>🈵 <code>:u6e80:</code></td><td>🈚️ <code>:u7121:</code></td></tr><tr><td>🈸 <code>:u7533:</code></td><td>🈳 <code>:u7a7a:</code></td><td>🈲 <code>:u7981:</code></td></tr><tr><td>🈂️ <code>:sa:</code></td><td>🚻 <code>:restroom:</code></td><td>🚹 <code>:mens:</code></td></tr><tr><td>🚺 <code>:womens:</code></td><td>🚼 <code>:baby_symbol:</code></td><td>🚭 <code>:no_smoking:</code></td></tr><tr><td>🅿️ <code>:parking:</code></td><td>♿️ <code>:wheelchair:</code></td><td>🚇 <code>:metro:</code></td></tr><tr><td>🛄 <code>:baggage_claim:</code></td><td>🉑 <code>:accept:</code></td><td>🚾 <code>:wc:</code></td></tr><tr><td>🚰 <code>:potable_water:</code></td><td>🚮 <code>:put_litter_in_its_place:</code></td><td>㊙️ <code>:secret:</code></td></tr><tr><td>㊗️ <code>:congratulations:</code></td><td>Ⓜ️ <code>:m:</code></td><td>🛂 <code>:passport_control:</code></td></tr><tr><td>🛅 <code>:left_luggage:</code></td><td>🛃 <code>:customs:</code></td><td>🉐 <code>:ideograph_advantage:</code></td></tr><tr><td>🆑 <code>:cl:</code></td><td>🆘 <code>:sos:</code></td><td>🆔 <code>:id:</code></td></tr><tr><td>🚫 <code>:no_entry_sign:</code></td><td>🔞 <code>:underage:</code></td><td>📵 <code>:no_mobile_phones:</code></td></tr><tr><td>🚯 <code>:do_not_litter:</code></td><td>🚱 <code>:non-potable_water:</code></td><td>🚳 <code>:no_bicycles:</code></td></tr><tr><td>🚷 <code>:no_pedestrians:</code></td><td>🚸 <code>:children_crossing:</code></td><td>⛔️ <code>:no_entry:</code></td></tr><tr><td>✳️ <code>:eight_spoked_asterisk:</code></td><td>✴️ <code>:eight_pointed_black_star:</code></td><td>💟 <code>:heart_decoration:</code></td></tr><tr><td>🆚 <code>:vs:</code></td><td>📳 <code>:vibration_mode:</code></td><td>📴 <code>:mobile_phone_off:</code></td></tr><tr><td>💹 <code>:chart:</code></td><td>💱 <code>:currency_exchange:</code></td><td>♈️ <code>:aries:</code></td></tr><tr><td>♉️ <code>:taurus:</code></td><td>♊️ <code>:gemini:</code></td><td>♋️ <code>:cancer:</code></td></tr><tr><td>♌️ <code>:leo:</code></td><td>♍️ <code>:virgo:</code></td><td>♎️ <code>:libra:</code></td></tr><tr><td>♏️ <code>:scorpius:</code></td><td>♐️ <code>:sagittarius:</code></td><td>♑️ <code>:capricorn:</code></td></tr><tr><td>♒️ <code>:aquarius:</code></td><td>♓️ <code>:pisces:</code></td><td>⛎ <code>:ophiuchus:</code></td></tr><tr><td>🔯 <code>:six_pointed_star:</code></td><td>❎<code>:negative_squared_cross_mark:</code></td><td>🅰️ <code>:a:</code></td></tr><tr><td>🅱️ <code>:b:</code></td><td>🆎 <code>:ab:</code></td><td>🅾️ <code>:o2:</code></td></tr><tr><td>💠<code>:diamond_shape_with_a_dot_inside:</code></td><td>♻️ <code>:recycle:</code></td><td>🔚 <code>:end:</code></td></tr><tr><td>🔛 <code>:on:</code></td><td>🔜 <code>:soon:</code></td><td>🕐 <code>:clock1:</code></td></tr><tr><td>🕜 <code>:clock130:</code></td><td>🕙 <code>:clock10:</code></td><td>🕥 <code>:clock1030:</code></td></tr><tr><td>🕚 <code>:clock11:</code></td><td>🕦 <code>:clock1130:</code></td><td>🕛 <code>:clock12:</code></td></tr><tr><td>🕧 <code>:clock1230:</code></td><td>🕑 <code>:clock2:</code></td><td>🕝 <code>:clock230:</code></td></tr><tr><td>🕒 <code>:clock3:</code></td><td>🕞 <code>:clock330:</code></td><td>🕓 <code>:clock4:</code></td></tr><tr><td>🕟 <code>:clock430:</code></td><td>🕔 <code>:clock5:</code></td><td>🕠 <code>:clock530:</code></td></tr><tr><td>🕕 <code>:clock6:</code></td><td>🕡 <code>:clock630:</code></td><td>🕖 <code>:clock7:</code></td></tr><tr><td>🕢 <code>:clock730:</code></td><td>🕗 <code>:clock8:</code></td><td>🕣 <code>:clock830:</code></td></tr><tr><td>🕘 <code>:clock9:</code></td><td>🕤 <code>:clock930:</code></td><td>💲 <code>:heavy_dollar_sign:</code></td></tr><tr><td>©️ <code>:copyright:</code></td><td>®️ <code>:registered:</code></td><td>™️ <code>:tm:</code></td></tr><tr><td>❌ <code>:x:</code></td><td>❗️ <code>:heavy_exclamation_mark:</code></td><td>‼️ <code>:bangbang:</code></td></tr><tr><td>⁉️ <code>:interrobang:</code></td><td>⭕️ <code>:o:</code></td><td>✖️ <code>:heavy_multiplication_x:</code></td></tr><tr><td>➕ <code>:heavy_plus_sign:</code></td><td>➖ <code>:heavy_minus_sign:</code></td><td>➗ <code>:heavy_division_sign:</code></td></tr><tr><td>💮 <code>:white_flower:</code></td><td>💯 <code>:100:</code></td><td>✔️ <code>:heavy_check_mark:</code></td></tr><tr><td>☑️ <code>:ballot_box_with_check:</code></td><td>🔘 <code>:radio_button:</code></td><td>🔗 <code>:link:</code></td></tr><tr><td>➰ <code>:curly_loop:</code></td><td>〰️ <code>:wavy_dash:</code></td><td>〽️ <code>:part_alternation_mark:</code></td></tr><tr><td>🔱 <code>:trident:</code></td><td>:black_square: <code>:black_square:</code></td><td>:white_square: <code>:white_square:</code></td></tr><tr><td>✅ <code>:white_check_mark:</code></td><td>🔲 <code>:black_square_button:</code></td><td>🔳 <code>:white_square_button:</code></td></tr><tr><td>⚫️ <code>:black_circle:</code></td><td>⚪️ <code>:white_circle:</code></td><td>🔴 <code>:red_circle:</code></td></tr><tr><td>🔵 <code>:large_blue_circle:</code></td><td>🔷 <code>:large_blue_diamond:</code></td><td>🔶 <code>:large_orange_diamond:</code></td></tr><tr><td>🔹 <code>:small_blue_diamond:</code></td><td>🔸 <code>:small_orange_diamond:</code></td><td>🔺 <code>:small_red_triangle:</code></td></tr><tr><td>🔻 <code>:small_red_triangle_down:</code></td><td></td><td></td></tr></tbody></table>

参考文献
----

*   [CSDN 博客的文字颜色、字体和字号设置](https://blog.csdn.net/weixin_42079409/article/details/120533764)
*   [CSDN 格式字体颜色入门](https://blog.csdn.net/wo919191/article/details/84249531)
*   [CSDN 中排版技巧](https://blog.csdn.net/Yong_Qi2015/article/details/79928180)
*   [CSDN 排版之颜色、字体、字号、空格、换行及背景色](https://blog.csdn.net/Xminyang/article/details/80341707)
*   [CSDN 写博客常用排版 超全超详细，最后还有一个小彩蛋 ~](https://blog.csdn.net/weixin_45084253/article/details/122280534)
*   [CSDN 文字字体、大小、颜色、加粗、居中、斜体设置](https://blog.csdn.net/qq_42224089/article/details/128785136)
*   [https://blog.csdn.net/yexiangCSDN/article/details/116525571](https://blog.csdn.net/yexiangCSDN/article/details/116525571)
*   [https://blog.csdn.net/weixin_42395140/article/details/111642339](https://blog.csdn.net/weixin_42395140/article/details/111642339)
*   [https://blog.csdn.net/qq_35091353/article/details/124277017](https://blog.csdn.net/qq_35091353/article/details/124277017)
*   [https://blog.csdn.net/qq_43827595/article/details/102298686](https://blog.csdn.net/qq_43827595/article/details/102298686)