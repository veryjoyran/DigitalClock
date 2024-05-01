# DigitalClock
东北大学电子积木大作业<br>

在课堂上与杜老师讨论后，决定将此次大作业分为三个部分来做。<br>
## 1.arduino
考虑到毕竟课程主要是以arduino开发版为基础的，所以使用arduino的开发版进行仿真完成了基本要求以及一些额外扩展功能（星期、闹钟报警、模式显示等）。<br>

## 2.stm32
然后使用CT117E_M4(STM32G431RBT6芯片)以及在参加第十五届蓝桥杯嵌入式比赛的部分代码模块，再整合了arduino中的代码，实现了较为全面的功能。（额外实现长按短按、秒表、通过串口通信设置时间、闹钟报警并使对应LED灯亮起）。<br>

## 3.Holo_Cubic
将数字钟拓展为桌面时钟，复刻稚辉君的Holo_Cubic开源项目，并且自行建模并3d打印了外壳。

## 说明
在文件夹中，arduino文件夹包含了 ino源码以及proteus仿真文件，stm32文件夹则为整个工程文件，holo_cubic文件夹为固件库以及.stl文件。<br>
演示视频的百度网盘链接为：链接：https://pan.baidu.com/s/15DNL0zQxUYICYWlIzqVlDA?pwd=ep06 
提取码：ep06
