
# real time lcd

## 简介

FireBeetle 2 ESP32-S3可以使用Arduino IDE、ESP-IDF、MicroPython进行编程，C语言、python都可以轻松的操纵硬件。我选择以vscode为主，插件platformio，需要安装python3.
Purple Pi开发板通过J12排针提供了丰富的GPIO接口，包括UART、SPI、I2C、GPIO等（还包括DC5V、DC3.3V、GND）。

## 引脚概述

- GPIO：常规引脚
- Analog：模拟输入引脚
- ADC：模数转换
- TOUCH：触摸引脚
- SPI：SPI接口
- I2C：I2C接口
- UART：UART接口
- USB：USB接口
- JTAG：调试接口
- 3V3：3.3V稳压电源输出
- VCC：电源输入/输出
- 输入：5V DC输入为FireBeetle供电（无法为锂电池充电）
- 输出：5V-USB 供电时输出USB电压，3.7V-锂电池供电时输出锂电池电压
- GND：公共地引脚

## 引脚示意图

![引脚示意图](https://img.dfrobot.com.cn/wiki/5d57611a3416442fa39bffca/a96b4c6cf0ffba8491af4ddd24442e87.jpg)

## 引脚关系图

| board   | extend      |
| ------- | ----------- |
| IO1/SDA | SSD1306-SDA |
| IO2/SCL | SSD1306-SCK |
| IO7/D5  | DS1302-SCK  |
| IO38/D3 | DS1302-DO   |
| IO3/D2  | DS1302-RST  |

如下图：  

## 
