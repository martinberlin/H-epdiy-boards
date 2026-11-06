## H-epdiy-boards

An alternative epdiy hardware repository with variations of the original project


### epdiy-model-F

What it provides:

- A 40 pin connector for 16 bit Eink displays like ED103TC2 or ED103MC2
- A 34 pin connector for 8 bit Kindle like Eink displays (All the ED060***)
- Double USB-C connector w/built in USB only (no UART)
- A single BOOT / USER button (IO 0)
- An IR receiver TSOP341 (LCSC: C118303)
- Switchable QWIIC power so you can switch on a peripheral and cut it's power completely
- TP4056 battery charger

The IR is meant so you can make a simple Firmware and change the display content with  your TV remote.

How it looks like:

![Board preview](assets/epd_model_f.png)

Some features like RTC and IR receiver:

![Schematics detail](assets/rv3032_ir.png)

[Full schematics PDF](epdiy-v7-model-F/v7-model-f_1.0.pdf)