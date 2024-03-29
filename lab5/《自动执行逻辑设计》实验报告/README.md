**一、实验目的**

掌握能够自动运行加法运算的程序存储计算机（冯诺依曼体系结构)。

**二、实验内容**

（1）根据手摇式计算机的手摇原理，改为使用RS触发器进行手动计算。

（2）实现硬布线计算机。

（3）掌握存储器的使用，实现一个简单的冯诺依曼体系结构的程序存储计算机。

（具体实验内容见实验视频指导）

3. **实验步骤（图文方式叙述）**

使用RS触发器进行手动计算

在之前实验3做的手摇式计算机的基础上，用RS寄存器替换原本的控制端口。




![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.002.png)实现硬布线计算机

根据冯哥视频中讲解，调用4转16模块，将四位数字通过分线器转换成16位的数字脉冲。替代了原来手动去点控制端口的操作，实现了自动化。

冯诺依曼体系结构的程序存储计算机。 

![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.003.png)

![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.004.png)

![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.005.png)![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.006.png)

**四、实验结果（<a name="_hlk42375346"></a>遇到的问题与解决）**

`	`建议截图最好配以文字说明，同时遇到的问题与解决可以使用文字表述。

![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.007.png)

![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.008.png)

![](Aspose.Words.7a87af31-d75d-4296-8380-ef75cd53025f.009.png)

采用冯诺依曼体系结构构建了能够自动运行的加法运算计算机。引入了ROM，通过改变ROM中的数值来实现计算机自动计算的功能。ROM存储器，断电不易失，在电路中加入后，比硬布线效率更高。

**五、实验体会**

通过学习RS触发器进行手动计算，再到硬布线计算，最后到实现带有存储器的冯诺依曼体系结构的计算机。让我了解了计算机的发展过程，先前的人们也是在慢慢的摸索中逐渐让计算机越来越自动化，直到冯诺依曼体系结构的计算机设计成功，并加入了存储器，让硬件与程序相结合，人们通过编写程序，大大提升了硬件执行的效率。
