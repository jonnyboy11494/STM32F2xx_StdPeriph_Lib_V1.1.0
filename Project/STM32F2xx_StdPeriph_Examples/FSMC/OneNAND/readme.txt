/**
  @page FSMC_OneNAND How to configure the FSMC to drive the OneNAND memory
  
  @verbatim
  ******************** (C) COPYRIGHT 2012 STMicroelectronics *******************
  * @file    FSMC/OneNAND/readme.txt 
  * @author  MCD Application Team
  * @version V1.1.0
  * @date    13-April-2012
  * @brief   Description of the FSMC OneNAND example.
  ******************************************************************************
  *
  * Licensed under MCD-ST Liberty SW License Agreement V2, (the "License");
  * You may not use this file except in compliance with the License.
  * You may obtain a copy of the License at:
  *
  *        http://www.st.com/software_license_agreement_liberty_v2
  *
  * Unless required by applicable law or agreed to in writing, software 
  * distributed under the License is distributed on an "AS IS" BASIS, 
  * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  * See the License for the specific language governing permissions and
  * limitations under the License.
  *
  ******************************************************************************
   @endverbatim

@par Example Description 

This example shows how to configure the FSMC to drive the KFG1216U2A/B-DIB6 OneNAND
memory mounted on STM322xG-EVAL evaluation board(MB786) RevA.

@note This memory is not available on STM322xG-EVAL board RevB.

In this example a basic example of how to use the FSMC firmware library and
an associate driver to perform read/write operations on the KFG1216U2A OneNAND
memory.


@par Directory contents

  - FSMC/OneNAND/system_stm32f2xx.c   STM32F2xx system clock configuration file 
  - FSMC/OneNAND/stm32f2xx_conf.h     Library Configuration file
  - FSMC/OneNAND/stm32f2xx_it.c       Interrupt handlers
  - FSMC/OneNAND/stm32f2xx_it.h       Header for stm32f2xx_it.c
  - FSMC/OneNAND/main.c               Main program

@note The "system_stm32f2xx.c" is generated by an automatic clock configuration 
      tool and can be easily customized to your own configuration. 
      To select different clock setup, use the "STM32F2xx_Clock_Configuration_V1.0.0.xls" 
      provided with the AN3362 package available on <a href="http://www.st.com/internet/mcu/family/141.jsp">  ST Microcontrollers </a> 

      
@par Hardware and Software environment 

  - This example runs on STM32F2xx Devices.
  
  - This example has been tested with STM322xG-EVAL RevB and can be easily tailored
    to any other development board.

    @note The STM322xG-EVAL board RevA was wrongly named STM3220F-EVAL


@par How to use it ? 

In order to make the program work, you must do the following :
 - Copy all source files from this example folder to the template folder under
   Project\STM32F2xx_StdPeriph_Template
 - Open your preferred toolchain 
 - Add the "stm322xg_eval_fsmc_onenand.c" file (under Utilities\STM32_EVAL\STM322xG_EVAL) 
   to the project source list  
 - Rebuild all files and load your image into target memory
 - Run the example

 * <h3><center>&copy; COPYRIGHT STMicroelectronics</center></h3>
 */


