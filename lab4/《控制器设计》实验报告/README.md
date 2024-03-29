**一、实验目的**

了解微程序控制器结构，掌握微程序的设计与实现。

**二、实验内容**

（1）将指令转换为微程序。

（2）实现带指令系统的简单计算机。

（具体实验内容见实验视频指导）

3. **实验步骤（图文方式叙述）**

列表-获得指令

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.002.png)

设置两个输入，一个输出，可以运算加法，减法。

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.003.png)

在原有基础上再加个ROM,使输出能实现自动化控制，使电路能完成计算两数之和的目的。



![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.004.png)



微指令：

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.005.png)


输入微程序指令如下

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.006.png)

**四、实验结果（<a name="_hlk42375346"></a>遇到的问题与解决）**



![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.007.png)

通过微指令让计算机在不改变硬件条件的基础上，现自动计算。

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.008.png)

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.009.png)

![](Aspose.Words.fd9206c4-1f92-4bce-986b-669017e31fd3.010.png)

完成计算：45+54=99

**五、实验体会**

学习微指令计算机后，感觉传统通过改变硬件实现的计算机效率太低了，而通过微指令，用户只要从ROM下手，将指令写入ROM 就可以解决拆机改电路的麻烦，效率大大的提升了。

