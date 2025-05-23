> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/2301_80005369/article/details/136340007)

> 文章浏览阅读1.8k次，点赞31次，收藏45次。首先在铜层上贴上一层干膜（紫外线敏感的感光材料），根据设计图印出光掩膜，将光掩膜覆盖在干膜上，用紫外线照射，光掩膜镂空部分的透明干膜就会发生聚合反应而固化，以防止被蚀刻，接着使用显影溶液，未固化部分的干膜会被溶解，暴露出下面的铜层，接着进行蚀刻，将电路板放进蚀刻溶液中，将暴露出的铜溶解，剩下的就是被干膜包裹的铜迹线，再洗掉干膜，最终留下的就是我们设计好的电路了，刷上阻焊层再刷上字之后进行测试就制作完成了。这是一个电路板顶层结构，就是一张二进制的画（只有红和黑），黑色表示镂空的，而红色的地方是不透光的。_pcb csdn

1.PCB 的结构
---------

### 1.1. 铜层

PCB 是一个三明治结构，他的上层和底层都是铜层，中间有一层叫 FR-4。

### 1.2. 阻焊

铜板上有一层油漆叫做阻焊层，作用是保护我们的铜线不受空气的氧化，如果线路或焊盘发生氧化，就没有办法焊接了，另外除了焊盘，其他不需要焊锡的地方都盖上油，这样的话焊锡就上不去了，所以叫做阻焊层。起到保护电路板和隔离焊盘的作用。

![](https://i-blog.csdnimg.cn/blog_migrate/c45072a7a6c1e8c746134c09a5b81e26.jpg)

 有阻焊层的铜线

![](https://i-blog.csdnimg.cn/blog_migrate/5bbce1e31beb0b42d4c5ee356a097067.png)

阻焊层失效后发生氧化的电路板

### 1.3. 丝印

在阻焊层上面还有一层叫做丝印层，丝印层上面印着字，我们称之为位号

比如 C33，C 就是电容 Capacitor，C33 就是编号为 33 的电容；R48 就是编号为 48 的电阻。一般 U 表示集成芯片，J 表示接插件，B 表示[蜂鸣器](https://so.csdn.net/so/search?q=%E8%9C%82%E9%B8%A3%E5%99%A8&spm=1001.2101.3001.7020)，D 表示二极管，F 表示保险丝，J 表示跳线，L 表示电感，Q 表示三极管，RT 表示热敏电阻，T 表示变压器…

![](https://i-blog.csdnimg.cn/blog_migrate/68dfca6c3e9e55bd4c1945244cab3d83.png)

也有字母加三位数字组合，首字母表示元器件，第二位表示电路功能编号（1 表示主板电路，2 表示电源电路），第三、四位表示该器件在该电路板上同类器件的序号

如 C105 代表主板上的电容，序号为 05。

### 1.4. 本质（PCB 画电路板到底在画什么）

![](https://i-blog.csdnimg.cn/blog_migrate/e69bff99a1b131e7b4f2192e2f03b7d8.png)

这是一个电路板顶层结构，就是一张二进制的画（只有红和黑），黑色表示镂空的，而红色的地方是不透光的。将这张画交给生产厂，生产厂就会做出胶片（光掩膜），生产出胶片就可以做电路板了。

首先在铜层上贴上一层干膜（紫外线敏感的感光材料），根据设计图印出光掩膜，将光掩膜覆盖在干膜上，用紫外线照射，光掩膜镂空部分的透明干膜就会发生聚合反应而固化，以防止被蚀刻，接着使用显影溶液，未固化部分的干膜会被溶解，暴露出下面的铜层，接着进行蚀刻，将电路板放进蚀刻溶液中，将暴露出的铜溶解，剩下的就是被干膜包裹的铜迹线，再洗掉干膜，最终留下的就是我们设计好的电路了，刷上阻焊层再刷上字之后进行测试就制作完成了

### 1.5. 基础工艺指标

![](https://i-blog.csdnimg.cn/blog_migrate/5a793e581a2dfc4b4d5e0cd8ccdb6a23.png)

这里说的是常规工艺

1.  板厚：板厚是指整个 PCB 的厚度，标准 PCB 厚度为 1.6mm，这一厚度能够满足大多数电子设备的需要，同时也提供了必要的机械强度和散热性能。较厚的板厚如超过 3.0mm 的超厚板，常用于工业和军事设备；而小于 0.8mm 的板厚被称为超薄板，这类 PCB 板多用于小型或轻薄型电子产品。
    
2.  走线间距与走线宽度一般是一样的
    
3.  铜厚就是电路板顶层和底层铜皮的厚度，常规一盎司铜
    
4.  丝印参数就是丝印的大小，常见 1mm，0.8mm，不影响电路板的电气特性
    

感谢观看，希望对各位能有帮助。如有错误请在评论区中指正或补充

下期预告：2.PCB 图中的元素（元件，布局布线，叠层设计）

                   3.PCB 的设计依据（原理图，原理图元件库）

                   4. PCB 的流程设计——总结