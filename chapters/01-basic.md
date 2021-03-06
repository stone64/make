基础篇
===

Arduino vs ESP8266 vs Raspberry Pi
---

在这一系列的文章里，我们使用三个主要的开发板：

 - Arduino。
 - ESP8266。
 - Raspberry Pi。

这三个硬件分别代表着，三种不同类型的硬件爱好者的开发板。

### Arduino

> Arduino，是一个开放源代码的单片机微控制器，它使用了Atmel AVR单片机，采用了开放源代码的软硬件平台，建构于简易输出/输入（simple I/O）接口板，并且具有使用类似Java、C语言的Processing/Wiring开发环境。[^wiki_arduino]

[^wiki_arduino]: 源自维基百科，https://zh.wikipedia.org/wiki/Arduino

其包含了以下的特性[^wiki_arduino]:

 - 基于知识共享开放源代码的电路图设计。
 - 免费下载，也可依需求自己修改，但需遵照姓名标示。您必须按照作者或授权人所指定的方式，表彰其姓名。
 - 依相同方式分享，若您改变或转变著作，当散布该派生著作时，您需采用与本著作相同或类似的授权条款。
 - Arduino 可使用 ICSP 在线烧入器，将 Bootloader 烧入新的 IC 芯片。
 - 可依据 Arduino 官方网站，获取硬件的设计档，加以调整电路板及组件，以匹配自己实际设计的需求
 - 可简单地与感测器，各式各样的电子组件连接，如红外线、超音波、热敏电阻、光敏电阻、伺服马达…等。
 - 支持多样的交互程序，如Adobe Flash, Max/MSP, VVVV, Pure Data, C, Processing…等。
 - 使用低价格的微处理控制器（Atmel AVR）（ATMEGA 8,168,328等）。
 - USB接口，不需外接电源。另外有提供直流（DC）电源输入。

当然，其最大的特色是，**完善的社区及生态系统**。几乎我们能想到的 Arduino
相关的创意，都可以在网上找到。如果没有的话，那么可能是你的创意不适合用于
Arduino。

Arduino
已然有一系列的相关硬件，就目前而言，最广泛的开发板，或者说是标准开发板是
Arduino UNO。

TODO: 相关 Arduino 硬件介绍

Arduino
最吸引人的是开创性的引入电子积木的概念，即开发板的扩展板可以直接叠加在开发板上使用，而无需额外的硬件。

TODO: 扩展板介绍。

Arduion IDE 基于 Processing 开发环境而开发的。

概念
---

引脚

模电

数电

电流、电阻、电压

etc..

PCB
---

为了更好的向读者展示硬件连线，我们将使用 Fritzing 汇制硬件电路图。

### Fritzing

> Fritzing 是一个开源的硬件计划（initiative），它可以使电子元件变成任何人的创意素材。Fritzing 提供一个软件工具、一个社区网站，以及本着 Processing 和 Arduino 精神的服务，培养创造性的生态系统，允许用户记录他们的原型，与他人分享、用于课堂上的电子相关教学，以及布局和制造专业的pcb。

Fritzing 的官网是：[http://fritzing.org/](http://fritzing.org/)。

因此，在开始之前我们需要在 Fritzing 的官网下载
Fritzing。当前它可以支持主流的操作系统：Windows、Linux、macOS，当然如果你想自己从源码编译一个
Fritzing，那也是可以的。除了中文和英语外，它还支持其它 17 种语言。

在其官网，除了能下载到该软件，还可以看到其它用户上传、汇制的
Fritzing 电路图等，它们可以免费下载，并引用到你的项目中。

LCEDA


硬件
---

Nokia 5110

温度、红外、距离、土壤


MCU vs CPU
---

Input -> MCU -> Output


通讯
---

蓝牙、有线、

专用协议，blabla
