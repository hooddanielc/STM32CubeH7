# STM32CubeH7 MCU Firmware Package

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio. It includes a comprehensive embedded software platform (this repo), delivered for each series (such as the STM32CubeH7 for the STM32H7 series).
   * The CMSIS modules (core and device) corresponding to the ARM-tm core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio 
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series 
   * A consistent set of middlewares components such as RTOS, USB, FatFS, LwIP, Graphics ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series
   
The **STM32CubeH7 MCU Package** projects are directly running on the STM32H7 series boards. You can find in each Projects/*Board name* directories a set of software projects (Applications/Demonstration/Examples) 

In this FW Package, the modules **Middlewares/ST/TouchGFX** **Middlewares/ST/STemWin** **Middlewares/ST/STM32_Audio** are not directly accessible. They must be downloaded from a ST server, the respective URL are available in a readme.txt file inside each module.

## Boards available
  * STM32H7 
    * [STM32H743I-EVAL](https://www.st.com/en/evaluation-tools/stm32h743i-eval.html)
    * [STM32H745I-DISCO] 
    * [STM32H747I-DISCO]
	* [STM32H747I-EVAL]
	* [STM32H750B-DK]
	* [NUCLEO-H743ZI](https://www.st.com/en/evaluation-tools/nucleo-h743zi.html)
	* [NUCLEO-H745ZI-Q]
 	
## Troubleshooting

**Caution** : The **Issues** requests are strictly limited to submit problems or suggestions related to the software delivered in this repo 

**For any other question** related to the STM32H7 product, the hardware performance, the hardware characteristics, the tools, the environment, you can submit a topic on the [ST Community/STM32 MCUs forum](https://community.st.com/s/group/0F90X000000AXsASAW/stm32-mcus)
