# FOCUS-ESP32-LED

基于 ESP32-S3 和 ESP-IDF v5.4 的 LED 控制项目。

## 项目内容

本项目完成了以下任务：

- **Task1**：GPIO 点灯与闪烁
- **Task2**：PWM 呼吸灯
- **Task3**：串口控制 LED 亮度与开关
- **Task4**：BLE 无线控制 LED
- **Task5**：状态机整合 BLE 与灯效控制
- **Task6**：INMP441 音频输入与低频检测触发 LED

## 最终整合版

最终整合版工程位于：

- `main/app_main.c`

该版本以**状态机**为核心，整合了：
- BLE 输入
- 音频输入
- LED 模式控制
- 多线程任务处理

## 目录说明

- `main/`：最终整合版工程代码
- `demo_videos/`：演示视频
- 其他 Task 文件夹：各任务阶段性的测试与实现代码

## 开发环境

- 开发板：ESP32-S3
- 开发框架：ESP-IDF v5.4
- LED 引脚：GPIO18
- 麦克风模块：INMP441

## 功能说明

最终整合版支持以下功能：

- BLE 控制 LED 开关
- BLE 控制呼吸灯、闪烁、亮度调节
- 音频低频检测触发 LED 闪烁
- 状态机统一管理 LED 状态切换
- FreeRTOS 多任务实现 BLE、音频和灯效并发运行

## 演示视频

演示视频见：

- `demo_videos/`
