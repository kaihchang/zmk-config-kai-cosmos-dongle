# Kai Cosmos, now with dongle!

![PXL_20250728_055040921~2](https://github.com/user-attachments/assets/8fa0792a-99ce-4186-a578-757c4baacf57)

What's good about ZMK dongles?<br/>
- Almost immediate connection and wake-up from sleep mode.<br/>
- No more dependent from less stable Bluetooth connections.<br/>
- Extended battery life for both splits/peripherals.<br/>
- "Wireless" support for ZMK studio, able to change keymaps on the fly.<br/>

Surely there's something bad?<br/>
- Extra cost for a spare MCU, seeeduino nrf52840 sense in my case here.<br/>
- Takes up an extra USB slot on your device.

Recommend setting CONFIG_PMW3610_REPORT_INTERVAL_MIN to only 8 if MCU is using chip antennae (125Hz) instead of PCB antennae (250Hz).