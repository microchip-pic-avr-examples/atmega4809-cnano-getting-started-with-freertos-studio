<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

![Freertos](images/freeRTOS.png)

# ATmega4809 Curiosity Nano Getting Started With FreeRTOS™

This is an example of how to get started with FreeRTOS™ on the AVR architecture with ATmega4809 Curiosity Nano. FreeRTOS™ is a real-time operative system kernel which allows the MCU to operate with different tasks simultaneously. This is accomplished with mutexes, semaphores and software timers. [AN3007](#Related-Documentation) describes in detail how the 

## Related Documentation

- [AN3007 - Getting Started with FreeRTOS on megaAVR® 0-series](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en610121)
- [ATmega4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATmega4809 Family Product Page](https://www.microchip.com/design-centers/8-bit/avr-mcus/device-selection/atmega4809)
- [FreeRTOS™ Homepage](https://www.freertos.org/index.html)

## Software Used

- [Atmel Studio 7.0 or later](https://www.microchip.com/mplab/avr-support/atmel-studio-7)
- ATmega_DFP 1.4.351 or later

## Hardware Used

- [ATmega4809 Curiosity Nano](https://www.microchip.com/developmenttools/ProductDetails/DM320115)
- [Curiosity Nano Base for Click boards™](https://www.microchip.com/developmenttools/ProductDetails/AC164162)
- [OLED1 Xplained Pro Extension Kit](https://www.microchip.com/developmenttools/ProductDetails/ATOLED1-XPRO)

## Setup

* Connect the OLED1 Xplained Pro Extension Kit into the **EXT1** port on your Curiosity Nano Base.
* Connect the ATmega4809 Curiosity Nano with the Curiosity Nano Base to your computer with a micro usb cable.

## Operation

1. Open `ATmega4809FreeRTOSExample.atsln` in Atmel Studio
2. In your menu bar in Atmel Studio go to `Debug->Start Without Debugging` or press `CTRL + ALT + F5`
3. Open data visualizer under `Tools->Data Visualizer` to interact with the virtual comport on the devkit

## Conclusion

We have here shown that it is possible to run FreeRTOS™ on an ATmega4809 and what advantages this might bring to your project. As mentioned in the appnote [AN3007](#Related-Documentation) you can see the different tasks running and interact with them using the virtual com port on your ATmega4809 Curiosity Nano or using the on board buttons. 