# RS41_ARDF
ARDF (fox hunt) firmware for RS41 radiosondes migrated from COIDE to SystemWorkbench

* Project forked from: https://github.com/SQ7FJB/RS41_ARDF
* STM32 configuration environment: STM32CubeMX (https://www.st.com/en/development-tools/stm32cubemx.html)
* Project build environment: SystemWorkbench for STM32 (http://www.openstm32.org)

# Configuration
All configs in ```config.h```




* ```APRS_CALLSIGN``` APRS callsign
* ```APRS COMMENT```  APRS comment

* ``` No_FOX``` How much Foxes in the cycle. If 1 -> without APRS, ACW all time
* ```Fox```   0- MOE, 1- MOI, 2- MOS, 3- MOH, 4- MO5 -(with APRS) 
* ```Fox```   5-  MO (without APRS), 
* ```Fox```   6..17 Hunters - only APRS
* ```APRS_FREQUENCY``` APRS frequency in MHz
* ```ACW_FREQUENCY```Fox MOE..MO5 frequency in MHz
* ```ACW_FREQUENCY``` Fox MO Mhz middle frequency
* ```Smoc``` Power 0-7, where 7 means 42.95 mW@434.150 MHz measured on E4406A
* ```ALLOW_DISABLE_BY_BUTTON``` Allow disabling device using button
