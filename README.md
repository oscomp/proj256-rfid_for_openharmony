# proj256-rfid_for_openharmony

# 9.驱动RFID读卡模块

## 项目描述

RFID（Radio Frequency Identification）即无线射频识别，是一种自动识别技术。 该技术通过无线射频信号进行非接触的双向数据通信，可以利用无线射频信号对记录媒体（如电子标签或射频卡）进行读写，从而达到识别目标和数据交换的目的。

一套完整的RFID系统， 是由读写器(Reader)、电子标签(Tag)、应用软件三部分组成，其工作原理是读写器在一个区域内发射特定频率的无线电波形成电磁场；在该区域内的电子标签被触发和驱动，将其中存储的数据送出，或者根据读写器的指令修改其中的数据；应用软件则根据用户的需要控制读写器对电子标签进行读或写操作，并对读取的数据进行处理。

## 源码

- https://gitee.com/openharmony
- https://gitee.com/HiSpark/hi3861_hdu_iot_application
- https://gitee.com/hihope_iot

## 项目导师

- 连志安 [https://gitee.com/lianzhian](https://gitee.com/lianzhian) 
- email [lian_zhian@runkaihong.com.cn](mailto:lian_zhian@runkaihong.com.cn)

## 难度

中等

## 文档

在gitee仓库了解OpenHarmony开源项目：https://gitee.com/openharmony

## License

Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

在wifiiot_hispark_pegasus(Hi3861)智能家居开发套件中开发应用软件(包含读写器驱动程序)，实现RFID读写器的驱动和读写电子标签的功能。

## **选择该赛题的支持**

开发套件支持：提供给参赛队伍开发套件，此开发板采用海思Hi3861芯片，它集成了 32位高能效的 RISC-V 指令集架构的 CPU，内置了 SRAM 和 Flash，可以独立运行程序，它的外设接口也比较丰富，包括：15个通用输入/输出（General Purpose Input/Output，GPIO）接口；支持7路模数转换器（Analog to Digital Converter，ADC）输入；支持6路脉宽调制（Pulse Width Modulation，PWM）输出；支持3个通用异步收发器（Universal Asynchronous Receiver & Transmitter，UART）接口；支持2个串行外设接口（Synchronous Peripheral Interface，SPI）；集成了两个内部集成电路（The Inter Integrated Circuit，I2C）接口；另外，它还具备一个内部集成电路音频（Inter-IC Sound，I2S）接口和一个安全数字输入输出（Secure Digital Input/Output，SDIO）从机接口。

技术答疑指导：针对OpenHarmony操作系统及本赛题技术要点，资深研发工程师提供专业的技术支持、指导，全程辅导技术方案的实现。

技术资料：提供相关技术资料和对应索引，指导赛题方向。

