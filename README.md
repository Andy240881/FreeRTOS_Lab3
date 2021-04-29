# FreeRTOS_Lab3
* Porting FreeRTOS & USART Tx.
* Use STM32CubeIDE debug mode, print Task List.
* Create Taskmonitor API in task.c
    * step1. Create four tasks
        * Red LED blink. priority = 1;
        * Green LED blink. priority = 1;
        * TaskMonitor. priority = 2;
        * Delay Task.  priority = 14;
    * step2. Task Monitor periodicity execute the Taskmonitor API.


