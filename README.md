# IS4320: I2C Modbus RTU Master Stack
Function Codes 1, 2, 3, 4, 15 and 16

## General Description
The **IS4320** is an integrated circuit with a built-in **Modbus RTU Master Stack**, offering a standalone Modbus Master solution accessible through an **I2C interface** for simple microcontroller integration.

The IS4320 features two communication buses: a **TTL UART** for Modbus transceiver (**RS485, RS422, RS232, etc.**) and an **I2C-Serial Interface** for the microcontroller.

The aim of the IS4320 is to save engineering time and costs associated with implementing and testing the **Modbus RTU communication protocol**, providing a reliable solution that reduces the **time-to-market (TTM)** of your product.

The IS4320 also brings benefits to your microcontroller: it utilizes **I2C**, eliminating the need for dedicated pins since I2C can be shared with other peripherals. Additionally, it eliminates the need for timers and **decreases the CPU load** on the microcontroller.

The device operates at **3.3V**, and its I/O pins are **5V tolerant**, allowing the use of either 3.3V or 5V transceivers. It is available in two temperature ranges: **Industrial** (-40°C to +85°C) and **Extended** (-40°C to +125°C) in an easy-to-solder **SO8N package**.

## Applications
* PLCs
* Process Control
* IIoT (Industrial Internet of Things)
* Precision Agriculture
* Building Automation
* Communications between PCBs

## Modbus Stack Characteristics
* Implemented Function Codes:
    * **FC 1** – Read Coils
    * **FC 2** – Read Discrete Inputs
    * **FC 3** – Read Holding Registers
    * **FC 4** – Read Input Registers
    * **FC 15** – Write Multiple Coils
    * **FC 16** – Write Multiple Holding Registers
* Available baud rates: **1200, 2400, 9600, 19200, 57600, and 115200 bps**.

## Main Advantages
* Eliminates engineering time and costs for protocol implementation and testing.
* Simple and easy to use solution.
* Reduces product **time-to-market (TTM)**.
* Reduces microcontroller **CPU load**.
* Reduces impact on microcontroller peripherals (no need for timers or UARTs).
* Saves microcontroller pins with a shared **I2C**.
* Features a small, easy-to-solder **SO8N package**.
* Provides a low-cost solution.
* Makes the **Modbus protocol transparent**.
* I2C Speeds: **100kHz, 400kHz, and 1MHz**.

---

<img width="1852" height="1261" alt="IS4320 Modbus RTU Master diagram" src="https://github.com/user-attachments/assets/bda3ec65-c608-4cc3-946c-d10b274ca281" />
