# helium-pronto-heater-pcb
PCB for Project "Pronto Heater": A Helium-based LoRaWAN temperature sensor reporting system

## Core Plan
* LoRaWAN Module: LLCC68 or similar
	* Cheap from China and comparable to other systems (like SX1276)
	* Control Library: https://github.com/xreef/EByte_LoRa_E220_Series_Library
	* Alternative Control Library: https://github.com/chandrawi/LoRaRF-Arduino
	* Purchase Link 1: https://www.aliexpress.com/item/1005002752596602.html (maybe)

* Microcontroller: ESP32
* Power: single 18650 with buck-boost
