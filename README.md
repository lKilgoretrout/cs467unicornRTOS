# cs467unicornRTOS
Minimal Real Time Operating System for ARM Cortex 4m chipset

The eventual goal of this project is to have a priority scheduler and an OS mechanism to dynamically allocate RAM
(up to the 32K that the Tiva-C can handle anyhow).
Right now, it works with a round robin scheduler that causes a context switch based Systic then PendSV interrupts.
