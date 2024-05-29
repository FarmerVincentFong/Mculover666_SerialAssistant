# FWQ研究此串口助手项目的小结
### 一开始是在博客园看到这篇串口助手教程，写的挺详细，但是只有前四篇文章。其他文章在CSDN，要收费几十块钱，（CSDN涉及上位机的都非常贵），还好开源了，直接撸项目源码。

### [博客园-C#上位机开发（四）—— SerialAssistant功能完善](https://www.cnblogs.com/Mculover666/p/9132847.html)
### [CSDN-C#上位机开发（五）——SerialAssistant界面升级（WinForm界面布局进阶）](https://mculover666.blog.csdn.net/article/details/116483736)
### [SerialAssistant 项目GitHub地址](https://github.com/FarmerVincentFong/Mculover666_SerialAssistant)
---
### 看了源码，这个串口助手还算功能完善，能 ：发送、接收、十六进制、加时间戳、定时发送、记录日志、导入导出已接收消息等。

### 我看一遍代码，总体不算复杂，没什么非常高级写法。主要操作 SerialPort 类，如Open()、Close()、Write()、Read()、配置串口参数等。

