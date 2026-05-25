# 🚀 RTOS on STM32F446RE

> Hands-on Embedded Systems and FreeRTOS experiments using the STM32F446RE Cortex-M4 microcontroller.

![STM32](https://img.shields.io/badge/MCU-STM32F446RE-blue)
![RTOS](https://img.shields.io/badge/RTOS-FreeRTOS-green)
![IDE](https://img.shields.io/badge/IDE-STM32CubeIDE-orange)
![Platform](https://img.shields.io/badge/Platform-ARM_Cortex_M4-red)

---

## 📖 Overview

This repository contains a collection of embedded systems and FreeRTOS experiments performed on the **STM32F446RET6** microcontroller using **STM32CubeIDE** and **FreeRTOS** middleware.

The project demonstrates the transition from:
- Bare-metal embedded programming
- Peripheral interfacing
- Timer and PWM applications
- RTOS-based multitasking
- Synchronization primitives
- Inter-task communication

The experiments are designed for:
- Embedded systems learning
- RTOS fundamentals
- STM32 peripheral programming
- Academic lab work
- Interview preparation

---

## 🧠 Skills Demonstrated

- STM32 HAL Programming
- GPIO Configuration
- Timer & PWM Configuration
- USART Communication
- RTOS Task Scheduling
- Queue-Based IPC
- Binary & Counting Semaphores
- Interrupt Handling
- Deferred Interrupt Processing
- SWV ITM Debugging
- CMSIS-RTOS V2 API
- Preemptive Scheduling

---

# 🛠️ Hardware & Tools

| Item | Details |
|------|---------|
| MCU | STM32F446RET6 |
| Core | ARM Cortex-M4 @ 180 MHz |
| Flash | 512 KB |
| RAM | 128 KB |
| RTOS | FreeRTOS |
| IDE | STM32CubeIDE |
| Framework | STM32 HAL |
| Board | Nucleo-F446RE |

---

# 📂 Repository Structure

```text
RTOS-ON-STM32F446RE/
│
├── 01_GPIO_LED_Blink/
├── 02_Button_LED_Toggle/
├── 03_HCSR04_USART/
├── 04_PWM_LED_Control/
├── 05_FreeRTOS_Single_Task/
├── 06_FreeRTOS_Task_Priority/
├── 07_FreeRTOS_SWV_ITM_Tracing/
├── 08_FreeRTOS_Binary_Semaphore/
├── 09_Queue/
├── 10_Counting_Semaphore/
│
└── README.md
