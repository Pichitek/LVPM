# Low Voltage Power Measurement
Premise of the project for this class was to implement any sensor into working device. Our group decided that we would like to make power measurement device based on widely available Hall sensors.

![schemat_blokowy](https://github.com/Pichitek/LVPM/assets/106306917/fb8c170d-0f07-4d91-8fa9-1c7a552d8043)

As seen on this block diagram, this project can serve as standalone device. It is capable of measuring current and voltage, acquiring data on STM32F0 microcontroller and transmitting this data over UART. Design provides two isolation barriers to make sure that any device which is connected to the LVMP will not be damaged.

This project consists of:
- PCB and schematic of LVPM
- firmware for the microcontoller
- desktop app for data visualization (https://github.com/arkadiuszrapacz/HalSensorApp)
- project presentations and report (written in polish)

![zmonotwana_plyka](https://github.com/Pichitek/LVPM/assets/106306917/76cd73e1-cf08-4342-9ac1-0332a71ab79d)