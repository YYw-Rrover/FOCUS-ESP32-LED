本项目用于记录基于 ESP32-S3 和 ESP-IDF v5.4 的硬件控制任务。
## 项目简介

本项目基于 ESP32 开发板和 ESP-IDF 框架，实现了一个 LED 智能灯控制系统。  
主要完成了 GPIO 控灯、PWM 呼吸灯、BLE 控制和状态机整合等功能。

---

## 开发环境

- 开发板：ESP32（N16R8）
- 开发框架：ESP-IDF 5.4
- 开发工具：VS Code
- 系统环境：Linux 虚拟机

---

## 硬件连接

LED 连接在 GPIO18 引脚，连接方式如下：

GPIO18 -> 电阻 -> LED -> GND
