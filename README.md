# Learn Electronics and IoT

Hey! I'm assembling a list of useful skills and tutorials for designing Electronics/IoT devices for the non-Engineer. **[Learn]** links identify places to pick up these skills. Some of these are resources that have served me well over the past few years. In some cases, links are temporary (result of the first skill on the list) as I continue to identify best resources for some topics.

Have a better suggestion? Feel free to open an issue or PR. 

Skill List:

* How to Google. [Seriously](https://www.pcmag.com/how-to/23-google-search-tips-youll-want-to-learn). You can also check out FreeCodeCamp's [Read-Search-Ask methodology](https://www.freecodecamp.org/news/read-search-dont-be-afraid-to-ask-743a23c411b4/). The amount of information available at our fingertips is wild, and knowing how to find it will get you far.

* Circuits and Breadboarding ([Learn](https://www.smraza.com/pages/toturial))
  * We use the [Smraza S32](https://www.smraza.com/products/smraza-basic-starter-kit-for-arduino-uno-r3-project-with-tutorial-breadboard-jumper-wires-resistors-led-lcd-1602-sensors-s32) kit at [MakerspaceCT](https://makerspacect.com) and [Spark Makerspace](https://sparkmakerspace.org). It's not perfect, but it is adequate and inexpensive and it includes the T-Cobbler board for breaking out the Raspberry Pi GPIO pins. As of 12/7/2021, not currently available on Amazon.

* File management and revision history: git with github lfs. ([Learn](https://dangitgit.com/en))

* Arduino Fundamentals ([Learn](https://github.com/makerspacect/arduino_intro))

* MicroPython or CircuitPython Fundamentals

* Raspberry Pi Fundamentals ([Learn](https://github.com/makerspacect/raspberry_pi_intro))

* MQTT with WiFi ([Learn](https://codetober.com/temperature-and-humidity-with-esp32/))

* Helium Packets ([Learn](https://github.com/MakerspaceCT/ttgo_esp32_helium))

* MQTT with Helium, LoRaWAN ([Learn](https://www.hackster.io/uFire/helium-water-quality-monitor-075e6d)) - AWS IoT Core is AWS's MQTT broker. You could also use [Mosquitto](https://pimylifeup.com/raspberry-pi-mosquitto-mqtt-server/) if you're looking for a self-hosted solution.

* AWS IoT Core ([Learn](https://aws.amazon.com/blogs/compute/building-an-aws-iot-core-device-using-aws-serverless-and-an-esp32/))

* Sensors!

  * [Adafruit Generic](https://github.com/adafruit/Adafruit_Sensor)

  * [Split Core Current](https://github.com/maxux/current-arduino)

* Sourcing components (DigiKey, Mouser, LCSC, Amazon, AliExpress, Banggood)

* PCB Design with KiCAD ([Learn](https://wiki.ai03.com/books/pcb-design/chapter/pcb-designer-guide))

* Design Rule Checking, Gerbers, and PCB sourcing ([JLCPCB Capabilities](https://jlcpcb.com/capabilities/Capabilities))

* CAD and Additive Fundamentals for enclosure design. (but first: will one of [these](https://www.homedepot.com/p/Carlon-4-in-x-4-in-x-2-in-PVC-Junction-Box-Gray-E989NNJ-CAR/100404097) work?)

* PCB validation and revision

* Soldering and circuit assembly. ( [Learn THT](https://learn.adafruit.com/adafruit-guide-excellent-soldering) / [Learn SMD](https://www.sparkfun.com/tutorials/category/2) ) *There are [T-962](https://github.com/UnifiedEngineering/T-962-improvements) reflow ovens available at both MakerspaceCT and Spark Makerspace for surface-mount (SMD) soldering.*

* Data aggregation and visualization ([Learn](https://support.machineq.com/s/article/MQTT-Tutorial), not sure this is best tutorial)

* IoT Industry, Past, Present, and Future.

* Assembling a Portfolio


## Development Boards worth knowing about
The term 'development' is used loosely here. Depending on the project, this might well be the development and 'release' board or controller. Next to each board it's processor/microcontroller is listed in (parentheses).
### Arduino-compatible:
* Arduino Uno (Atmega328P)
* Sparkfun Pro Micro (Atmega32u4)
* ESP32 (and ESP8266, ESP32 preferred)
* Seeedstudio XIAO (SAMD21)
### RP2040-based
Raspberry Pi Pico (RP2040)
Seeedstudio XIAO RP2040 (RP2040)
SparkFun Pro Micro - RP2040 (RP2040)

### Raspberry Pi (full Linux OS)
* Raspberry Pi 4 Model B
* Raspberry Pi Compute Module 4
* Raspberry Pi Zero 2
