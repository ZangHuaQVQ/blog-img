> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/sym_robot/article/details/114500229)

一、串口通信接口标准简介
------------

串行[数据通信](https://so.csdn.net/so/search?q=%E6%95%B0%E6%8D%AE%E9%80%9A%E4%BF%A1&spm=1001.2101.3001.7020)接口标准主要有 RS-232、RS-422 与 RS-485，最初都是由电子工业协会（EIA）制订并发布的。

RS-232 在 1970 年发布，命名为 EIA-232-E，作为工业标准，以保证不同厂家产品之间的兼容。

RS-232、RS-422 与 RS-485 标准只对接口的电气特性（电压，阻抗）做出规定，而不涉及接插件、电缆或协议，在此基础上用户可以建立自己的高层通信协议。

二、RS-232 串行通信接口标准
-----------------

RS-232-C 是美国电子工业协会 EIA（Electronic Industry AssociaTIon）制定的一种串行物理接口标准。RS 是英文 “推荐标准” 的缩写，232 为标识号，C 表示修改次数。它的全名是“ 数据终端设备（DTE）和数据通讯设备（DCE）之间串行二进制数据交换接口技术标准”。

传统的 RS-232-C 总线标准采用标准 25 芯 D 型插头座（DB25），包含了两个信号通道，即主通道和副通道。利用 RS- 232 总线可以实现全双工通信，在多数情况下主要使用主通道。在一般应用中，使用 3 条～9 条信号线就可以实现全双工通信，如采用三条信号线（接收线、发送线和信号地）能实现简单的全双工通信过程。

后来使用简化为 9 芯 D 型插座（DB9）现在应用中 25 芯插头座已很少采用。

为了保证码元畸变小于 4% 的要求，按 RS-232-C 标准规定，驱动器的负载电容应小于 2500pF。驱动器允许有 2500pF 的电容负载，通信距离将受此电容限制，例如，采用 150pF/m 的通信电缆时，最大通信距离为 15m（50 英尺）；若每米电缆的电容量减小，通信距离可以增加。传输距离短的另一原因是 RS-232 属单端信号传送，存在共地噪声和不能抑制共模干扰等问题，因此一般用于 20m 以内的通信。

RS-232 采取不平衡传输方式，即所谓单端通讯。由于其发送电平与接收电平的差仅为 2V 至 3V 左右，所以其共模抑制能力差，再加上双绞线上的分布电容，其传送距离最大为约 15 米，最高速率为 20kb/s。RS-232 是为点对点（即只用一对收、发设备）通讯而设计的，其驱动器负载为 3～7kΩ。所以 RS-232 适合本地设备之间的通信。  
目前 RS-232 是 PC 机与通信工业中应用最广泛的一种串行接口。RS-232 被定义为一种在低速率串行通讯中增加通讯距离的单端标准。

收、发两端的数据信号是相对于信号地，如从 DTE 设备发出的数据在使用 DB25 连接器时是 2 脚相对 7 脚（信号地）的电平。典型的 RS-232 信号在正负电平之间摆动，在发送数据时，发送端驱动器输出正电平在 + 5～+15V，负电平在 - 5～-15V 电平。当无数据传输时，线上为 TTL，从开始传送数据到结束，线上电平从 TTL 电平到 RS-232 电平再返回 TTL 电平。接收器典型的工作电平在 + 3～+12V 与 - 3～-12V。由于发送电平与接收电平的差仅为 2V 至 3V 左右，所以其共模抑制能力差，再加上双绞线上的分布电容，其传送距离最大为约 15 米，最高速率为 20Kbps。RS-232 是为点对点（即只用一对收、发设备）通讯而设计的，其驱动器负载为 3～7kΩ。所以 RS-232 适合本地设备之间的通信。

### 1 电气特性

RS-232C 对电气特性、逻辑电平和各种信号功能都做了规定，如下：

在 TXD 和 RXD 数据线上：

（1）逻辑 1 的电平为 - 3V~-15V

（2）逻辑 0 的电平为 + 3~+15V 的电压

在 RTS、CTS、DSR、DTR 和 DCD 等控制线上：

（1）信号有效（接通，ON 状态）为 + 3~+15V 的电压

（2）信号无效（断开，OFF 状态）为 - 3~-15V 的电压

规定逻辑 “1” 的电平为 - 5V~-15 V，逻辑 “0” 的电平为 + 5 V～+15 V。选用该电气标准的目的在于提高抗干扰能力，增大通信距离。RS -232 的噪声容限为 2V，接收器将能识别高至 + 3V 的信号作为逻辑“0”，将低到 - 3 V 的信号作为逻辑“1

以上规定说明 RS-232C 是用正负电压来表示逻辑状态。对于数据 (信息码)，逻辑 1(传号) 的电平低于 - 3V，逻辑 0(空号)的电平高于 + 3V；对于控制信号，接通状态 (ON) 即信号有效的电平高于 3V，断开状态 (OFF) 即信号无效的电平低于 - 3V。  
　  
也就是说，当传输电平的绝对值大于 3V 时，电路可以有效地检查出来，介于 - 3～+3V 之间的电压无意义，低于 - 15V 或高于 + 15V 的电压也认为无意义，因此，实际工作时，应保证电平在 ± (3～15) V 之间。

### 2 机械特性

常用的串口接头有两种，一种是 9 针串口（简称 DB-9），一种是 25 针串口（简称 DB-25）。  
RS-232C 标准接口有 25 条线，其中，4 条数据线、11 条控制线、3 条定时线以及 7 条备用和未定义线。那么，这些信号线在 9 针串口和 25 针串口的管脚上是如何分配的呢？9 针串口和 25 针串口信号线分配下图所示。  
![](https://i-blog.csdnimg.cn/blog_migrate/68beb1cfdefc9ddd536bb9e36d3ec0ab.png)  
每种接头都有公头和母头之分，其中带针状的接头是公头，而带孔状的接头是母头。9 针串口的外观如下图所示。  
![](https://i-blog.csdnimg.cn/blog_migrate/8f31d2afbc255bc620bbd8c643ce4c7f.png)  
可以看出，在 9 针串口接头中，公头和母头的管脚定义顺序是不一样，这一点需要特别注意。那么，这些管脚都有什么作用呢？9 针串口和 25 针串口常用的 9 根管脚的功能说明如下图所示。  
![](https://i-blog.csdnimg.cn/blog_migrate/39c98bdd1deddb9f03527d090a235de1.png)  
RS232 标准采用的接口常用的一般是 9 针 D 型插头。

<table><thead><tr><th>编号</th><th>信号方向</th><th>缩写</th><th>名称描述</th></tr></thead><tbody><tr><td>1</td><td>调制解调器</td><td>DCD(又名 CD)</td><td>载波检测</td></tr><tr><td>2</td><td>调制解调器</td><td>RXD</td><td>接收数据</td></tr><tr><td>3</td><td>PC</td><td>TXD</td><td>发送数据</td></tr><tr><td>4</td><td>PC</td><td>DTR</td><td>数据终端准备</td></tr><tr><td>5</td><td></td><td>GND</td><td>信号地线</td></tr><tr><td>6</td><td>调制解调器</td><td>DSR</td><td>通讯设备准备好</td></tr><tr><td>7</td><td>PC</td><td>RTS</td><td>请求发送</td></tr><tr><td>8</td><td>调制解调器</td><td>CTS</td><td>允许发送（发送清除）</td></tr><tr><td>9</td><td>调制解调器</td><td>RI</td><td>响（振）铃指示器</td></tr></tbody></table>

(1)数据载波检出 (Data Carrier detection，DCD)——用来表示数据通信设备（DCE）已接通通信链路，告知数据终端设备（DTE）准备接收数据：当本地的 MODEM 收到由通信链路另一端(远地) 的 MODEM 送来的载波信号时，使 RLSD 信号有效，通知终端准备接收，并且由 MODEM 将接收下来的载波信号解调成数字数据后，沿接收数据线 RXD 送到终端。此线也叫作接收线信号检出 ( Received Line Signal Detection，RSD) 线。

(2) 接收数据 ( Received data，RXD)——通过 RXD 线终端接收从 MODEM 发来的串行数据 (DCE→DTE)。  
接收信号（RXD），数据终端设备（DTE）通过该信号线接收从数据通信设备（DCE）发来的串行数据。

(3) 发送数据 ( Transmitted data，TXD)——通过 TXD 终端将串行数据发送到 MODEM(DTE→DCE)。  
发送数据（TXD），数据终端设备（DTE）通过该信号线将串行数据发送到数据通信设备（DCE）。

(4)数据终端准备好 ( Data Terminal Ready，DTR)——有效时(ON) 状态，表明数据终端可以使用。  
数据终端准备好（DTR），有效状态（ON）表示数据终端设备处于可以使用状态。

(5) 地线 - GND。  
地线（SG、PG），分别表示信号地和保护地信号线。

(6) 数据装置准备好 ( Data Set ready，DSR)——有效状态 (ON)，表明通信设备处于可以使用的状态。

(7) 请求发送 ( Request to Send，RTS)——用来表示数据终端设备（DTE）请求数据通信设备（DCE）发送数据，即当终端要发送数据时，使该信号有效 (ON 状态)，向 MODEM 请求发送。它用来控制 MODEM 是否要进入发送状态。

(8) 清除发送 ( Clear to Send，CTS)―用来表示 DCE 准备好接收 DTE 发来的数据，是对请求发送信号 RTS 的响应信号。当 MODEM 已准备好接收终端传来的数据并向前发送时，使该信号有效，通知终端开始沿发送数据线 TXD 发送数据。  
允许发送（CTS），用来表示数据通信设备（DCE）已经准备好了数据，可以向数据终端设备（DTE）发送数据，是对请求发送信号 RTS 的响应。

(9) 振铃指示 ( Ringing，R)——当 MODEM 收到交换台送来的振铃呼叫信号时，使该信号有效 (ON 状态)，通知终端，已被呼叫。  
振铃指示（RI），当数据通信设备收到交换台送来的振铃呼叫信号时，使该信号有效（ON），通知终端，已被呼叫。

**RS422 与 RS485 放在下一章《串口通信接口标准学习（四）——RS422、RS485》继续了解。**

参考：  
【1】https://baike.baidu.com/item/RS-232/2022036?fromtitle=rs232&fromid=3555506&fr=aladdin  
【2】https://blog.csdn.net/bekars/article/details/1392586  
【3】http://m.elecfans.com/article/663969.html