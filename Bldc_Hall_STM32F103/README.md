 ## 基于STM32F103的三相电机控制程序，霍尔传感器版本
 
 本文件是基于**STM32F103RBT6**通过使用六路互补PWM输出控制bldc电机，其中包括ADC+DMA三路相电流采集、SPI仪表显示电机参数、按键长短按调节不同模式、PID调节（速度反馈通过计算电机反电势电压间隔来计算）等多个小功能！