# EDF-Scheduler-on-FreeRTOS

This project delves into the implementation of the Earliest Deadline First (EDF) Scheduling policy on FreeRTOS, an open-source Real-Time Operating System (RTOS) designed for various microcontrollers. Real-time systems, characterized by hard timing deadlines, demand precise scheduling to prevent catastrophic failures in hard real-time systems and avoid system failures in soft real-time systems. EDF is a scheduling policy that prioritizes tasks based on their absolute deadlines, ensuring the scheduling of tasks with the earliest deadlines first.

## Project Objective:
The primary goal of this project is to integrate the EDF scheduling policy into FreeRTOS, enhancing the real-time capabilities of the operating system. By considering the absolute deadlines of tasks, EDF minimizes the occurrence of deadline misses, providing a predictable and reliable behavior for the entire system.
