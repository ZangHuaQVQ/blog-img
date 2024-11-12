> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/LostSpeed/article/details/124080794)

### 前言

如果是规则板框 (长方形)，在 cadence SPB17.4 的板框层中直接画线就行。  
如果板框复杂 (异形)，可以在 autoCAD 中画形状，然后另存为.[DXF](https://so.csdn.net/so/search?q=DXF&spm=1001.2101.3001.7020) 文件给 SPB17.4 导入板框用。

试了一下，在 autoCAD2022 中，画了一个正方形当作板框，导出后的.DXF 文件可以给 SPB17.4 正常用。

记录一下在 autoCAD2022 中，画板框和导出的流程。

### 笔记

### autoCAD2022 操作流程

### 确定长度单位

![](https://i-blog.csdnimg.cn/blog_migrate/c11d9dc2970902bf276a9d8e91ea14ac.png)  
![](https://i-blog.csdnimg.cn/blog_migrate/a2b513c3d35c5930a7d87d6b054231aa.png)  
这里的参数是 mm, 没改，装完的默认参数。  
因为这里是 mm 单位，等导入 SPB17.4 时，也要选 mm 为单位。因为在 autoCAD 中画线时，只是给数值，而没有给单位。没给单位的值的单位，就是全局设置这里的 mm 单位。

### 设置图纸原点

默认的图纸原点在左下角 (0,0), 将原点向图纸中间设置一下 (e.g. 100, 100)  
![](https://i-blog.csdnimg.cn/blog_migrate/f7cb7da9c2df8199ed34360c6ff274f3.png)  
![](https://i-blog.csdnimg.cn/blog_migrate/e66b18a27536a3d933b41dc20f0d90f0.png)  
在输入过程中，看到原点坐标格式为 x,y, 角度。  
每输入一项后，如果有下一项要输入，就按 TAB 键。  
如果都输入完了，没有下一项要输入，就按回车。  
设置完的原点样子如下  
![](https://i-blog.csdnimg.cn/blog_migrate/acd997d08bf8ef87a49feae0f5132b81.png)

### 新建图层

新建图层的目的是将板框相关的图形，都画到新建的图层中，这样导入的时候方便些。防止原有默认图层（图层的名字叫做 0）中有其他东西。  
![](https://i-blog.csdnimg.cn/blog_migrate/8cd33284a29c5adb55b469fa4b3bb647.png)  
![](https://i-blog.csdnimg.cn/blog_migrate/76ca6187992a964701f58c5a0a38f436.png)  
将当前图层切到自己新加的图层上。  
![](https://i-blog.csdnimg.cn/blog_migrate/103198a4774756ce5a26fba46a73b20c.png)  
以后画的所有的板框图形，都在自己新加的图层上画。

左击自己要选的形状 (e.g. 直线)，然后就可以画了。  
![](https://i-blog.csdnimg.cn/blog_migrate/daec2da559f43a3737f3f101764c3a9b.png)  
画 4 条直线闭合，形成一个长方形板框。

根据要画的具体形状，需要输入不同的参数，输入完后回车，如果还需要输入，根据提示输入参数，输入完就回车。  
![](https://i-blog.csdnimg.cn/blog_migrate/686d9719a3aa0df0cab9ba9dcb0fa7b7.png)  
![](https://i-blog.csdnimg.cn/blog_migrate/6c1f7ee0d580273fc5b85a280ea45423.png)  
如果要输入的方式和软件给的不一样 (e.g. 直线默认是起点 + 角度)，输入完起点后，按下, 号，就会换成 2 点输入。也可以输入完一点后，用鼠标来导航到下一点（用鼠标给个角度，然后再输入一个长度就好）。如果都输入完了，根据提示或右键菜单选择操作结束。

### 核对测量距离

等画完后，想核对画的是否正确。就需要测量一下。  
![](https://i-blog.csdnimg.cn/blog_migrate/2e44e527e4d6f04e68a4267de5fb67a1.png)  
![](https://i-blog.csdnimg.cn/blog_migrate/2602a65115cc0b834c194b85e7f11934.png)  
测量距离是选择 2 点，用鼠标移动到线的 2 端，可以自动捕获，左击确定，选下一个点。

可以看到板框长度是 200mm, 我想画的是 100mm.  
如果要改，简单的做法就是重新画，直到搞对为止。  
正常做法，是修改这个错误的图形。  
对于这条线来说，左击选中，然后拖拽左端点向右移动，这时，可以看到当前线长度，用键盘输入 100，然后回车就好。  
![](https://i-blog.csdnimg.cn/blog_migrate/993680f05aefba663ba3b82eb725327a.png)  
将上下 2 条线调成 100， 然后用鼠标选中左边的宽度线，选择移动，会先选择一个拷贝原点（选择上端点），然后再单击改好的上边长度线的左端点，点击一下。4 条线就都摆好了，正好是 100mm x 80mm 的长方形板框。

autoCAD2022 的交互性做的非常好，即使第一次上手，只要经常用其他软件，试试 (观察交互的提示信息) 就能画出一张图。

做了一个操作后，如果按下鼠标，还是会做上次一样的动作。如果想回空闲状态，可以按 ESC.

### 加板框尺寸标注

![](https://i-blog.csdnimg.cn/blog_migrate/6a25a5a6d6cd9c7a4ab8b255d3723537.png)  
线性标注是选 2 个端点，然后向空白处拉一个合适距离，左击确定就好。  
![](https://i-blog.csdnimg.cn/blog_migrate/2562b8534a0830d92c634023b26f8aa3.png)  
从尺寸标注上能看出，板框是 100mm x 80mm.

### 导出. DXF 文件

![](https://i-blog.csdnimg.cn/blog_migrate/a5d2d81e71ff9ab05ee3cb1b391f2ccb.png)  
![](https://i-blog.csdnimg.cn/blog_migrate/67fb2cc65588f440dd5217f8195126cc.png)

### END

导出的. DXF 文件可以导入 SPB17.4 的 PCB Editor 的 Board Geometry/outline.  
![](https://i-blog.csdnimg.cn/blog_migrate/82ccc627bfea5cf4bc8dc232fde8d291.png)  
然后再 change 到 Board Geometry/Design_Outline, 就完成了板框层的定义。  
![](https://i-blog.csdnimg.cn/blog_migrate/a72ba3343ea2f18ae1f28d705bfc90a0.png)

### 补充 - 2022_0411_0718

昨天将. dxf 导入 SPB17.4 时，将板框导入板框层时，需要将板框的线一条一条线的选中，最后选成一个封闭图形时，才能加入板框层。很麻烦。  
想起来，画完 autoCAD 板框后，需要加一步操作。将全部板框元素合并为一个图形后，再导出. dxf 文件。  
![](https://i-blog.csdnimg.cn/blog_migrate/269a4cbb0a24a2aac1b84108bbd64990.png)

理解错误了，将所有元素作为一个组，保存成. dxf 文件后，在用 autoCAD 打开（.dxf），所有元素又散开了 (还是一个元素一个元素的可以点击)。应该将这些元素  
变成一个块才行。

先打开. dwg, 选择元素，建立新块  
![](https://i-blog.csdnimg.cn/blog_migrate/df48a12a2636415658d2c3c8f60ed71f.png)  
给出块名称，建立新块。  
![](https://i-blog.csdnimg.cn/blog_migrate/e872fe289639689d74dd87aaeb737e0d.png)

将所有板框元素合并成一个组合图形（块）后，保存成. dxf 后，在 SPB17.4 中导入时，只需要选一下，就可以导入板框层。而不用一个元素一个元素的点击，最后形成封闭图形了，才导入板框层，提高了效率。