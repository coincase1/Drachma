30% Left-Handed Hall Effect Keypad

![alt text](https://github.com/coincase1/Drachma/blob/main/Drachma_Keyboard.jpg)

Based on / Inspired by [Peppapigh's HE60](https://github.com/peppapighs/HE60).

This keyboard is a PCB swap of the [Kisnt 34 Key Numpad](https://www.amazon.com/gp/product/B0C1H8V52D?smid=A1QSA46GV4FLI2&psc=1). With modifications to the top of the case using a hobby saw, this PCB fits inside of that case. The Drachma PCB connects to the Kisnt USB daughterboard using the provided Flat Conductor Cable. It also features a connection for a Pico-EZmate connector featured on Unified Daughterboards.

For anyone looking at this design at a later date, please be mindful of the Analog-to-Digital pins on the STM32F446 microcontroller. These can be verified on Sheets 46-56 of the STM32F446T MC Manual.

For HE switches, my recommendation are either OH49E-S or SS39ET from Honeywell. The OH49E-S are clones of these switches and these are featured in a number of big box HE board builds.

All Kicad and Firmware represents the latest (V3) Drachma build.
