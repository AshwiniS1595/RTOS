# Implementation of EDF and LST algorithm in FreeRTOS

- cd EDF_and_LST

### EDF Scheduling
  - set ```configUSE_EDF_SCHEDULER = 1 and configUSE_LST_SCHEDULER = 0``` in Project/FreeRTOSConfig.h
  - ```$ make clean```
  - ```$ make```
  - ```$ ./FreeRTOS-Sim```

### LST Scheduling
  - set ```configUSE_EDF_SCHEDULER = 0 and configUSE_LST_SCHEDULER = 1``` in Project/FreeRTOSConfig.h
  - ```$ make clean```
  - ```$ make```
  - ```$ ./FreeRTOS-Sim```

##### Note: Uncomment the respective task creation code lines in Project/main.c
