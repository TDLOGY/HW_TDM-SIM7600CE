---
__Advertisement  __
#### Order easy online at:
- __[TDM-SIM7600CE-M1S](https://linhkienthuduc.com/module-4g-3g-2g-gps-simcom-sim7600ce-m1s-lte-cat-4-ra-chan)__ - 2G/3G/4G LTE CAT 4 GPS BREAKOUT MODULE
- __[TDM-A7600C-L1](https://linhkienthuduc.com/module-4g-3g-2g-simcom-a7600c-l1-lte-cat-1-ra-chan)__ - 2G/3G/4G LTE CAT 1 BREAKOUT MODULE.
----
This repo will provide you all data for these module!
These module can replaces SIM800L module with complete pinout board & power converter, IO level shifter for your design

---

### TDM-SIM7600CE Module Specifications:

+ General data::
  - Supply voltage range on VCC PIN: 4.8V ~ 16V
  - Control Via AT Commands
  - Operation temperature: -40℃ to +85℃
  - Weight: : 5.7 ± 0.2g
  - GNSS:GPS/GLONASS/BeiDou
  - Frequency:
    * LTE-FDD B1/B3/B5/B8
    * UMTS/HSDPA/HSPA+ B1/B8
    * GSM/GPRS/EDGE 900/1800MHz
---
### TDM-A7600C-L1 Module Specifications:

+ General data::
  - Supply voltage range on VCC PIN: 4.8V ~ 16V
  - Control Via AT Commands
  - Operation temperature: -40℃ to +85℃
  - Weight: : 5.7 ± 0.2g

  - Frequency:
    * LTE-FDD B1/B3/B5/B8
    * UMTS/HSDPA/HSPA+ B1/B8
    * GSM/GPRS/EDGE 900/1800MHz

---
## AT Command Test GUI:

[AT Command Test SIMCOM Module: ](https://linhkienthuduc.com/at-command-test-cho-cac-dong-module-sim)

[DOWNLOAD HERE](https://github.com/TDLOGY/ATCommand_Test)

See more our product at  [www.tdmaker.space](https://tdmaker.space)

---

## Pin Tables
| Name| Description |
| ------ | ----------- |
| VIN | Input power for module, input range from 4.8-16V, average supply current should be above 1A (at 12V)|
| GND| GND power |
| PEN| Power Enable signal control, default is pull high (active module), pull down by external npn transistor or IO to turn off the module completely |
| RTS| RTS signal for Uart flow control|
| RXD| Uart receive data|
| TXD| Uart transmit dataa|
| CTS| CTS signal for Uart flow control|
| DTR| DTR signal for Uart flow control|
| PCM-OUT| PCM signal |
| PCM-IN | PCM signal |
| PCM-SYNK|PCM signal|
| PCM-CLK| PCM signal|
| ADC2| ADC2 input signal|
| ADC1| ADC1 input signal|
| RI| RI signal |
| NET| Net light signal (displayed by LED onboard) |
| FLYMODE| Flymode|
| RESET| Reset pin for sim module|
| POWER KEY| PWR KEY Pin, default pulled down by **0 Ohm** (**R10**), to using it, please remove R10|
### Pin logic level
- These pin supported to connect direct with other MCU with higher logic level (example: 3.3V, 5V, 12V..) as below:

| Name| Description |
| ------ | ----------- |
| 3.3V or 5V logic level | TX, RX, DTR, RTS, CTS, RI|
- ### Pin  Out Diagram

![Pinout](https://github.com/TDLOGY/TDM-SIM7600CE/blob/main/TDM-SIM7600CE-pinout.PNG)

- ### Module Dimension

![Pinout](https://github.com/TDLOGY/TDM-SIM7600CE/blob/main/TDM-SIM7600CE-M1S%20Dimension.PNG)




