<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

![Freertos](images/freeRTOS.png)

# ATmega4809 Curiosity Nano Getting Started With FreeRTOS™

This is an example of how to get started with FreeRTOS™ on the AVR architecture with ATmega4809 Curiosity Nano. FreeRTOS™ is a real-time operative system kernel which allows the MCU to operate with different tasks simultaneously. This is accomplished with mutexes, semaphores and software timers. [AN3007](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en610121) describes in detail how the FreeRTOS™ is being used to control the AVR.

## Related Documentation

- [AN3007 - Getting Started with FreeRTOS on megaAVR® 0-series](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en610121)
- [ATmega4809 Device Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [FreeRTOS™ Homepage](https://www.freertos.org/index.html)

## Software Used

- [Atmel Studio 7.0.2397 or later](https://www.microchip.com/mplab/avr-support/atmel-studio-7)
- Data Visualizer
    - [MPLAB Data Visualizer](https://gallery.microchip.com/packages/MPLAB-Data-Visualizer-Standalone(Windows)/)
    - [Studio Data visualizer](https://www.microchip.com/mplab/avr-support/data-visualizer)
- ATmega_DFP 1.4.351 or later
- AVR/GNU C Compiler 5.4.0 (built into studio)

## Hardware Used

- [ATmega4809 Curiosity Nano](https://www.microchip.com/developmenttools/ProductDetails/DM320115)
- [Curiosity Nano Base for Click boards™](https://www.microchip.com/developmenttools/ProductDetails/AC164162)
- [OLED1 Xplained Pro Extension Kit](https://www.microchip.com/developmenttools/ProductDetails/ATOLED1-XPRO)

## Setup

* Connect the OLED1 Xplained Pro Extension Kit into the **EXT1** port on your Curiosity Nano Base.

## Operation

1. Download the zip file or clone the example to get the source code.
2. Open `atmega4809-cnano-getting-started-with-freertos-studio.atsln` in Atmel Studio.
3. Connect the ATmega4809 Curiosity Nano with the Curiosity Nano Base to your computer with a micro usb cable.
4. In your menu bar in Atmel Studio go to `Debug->Start Without Debugging` or press `CTRL + ALT + F5`.
5. Open your favorite terminal application or Data visualizer and open the serial port associated with the cnano.

## Conclusion

We have here shown that it is possible to run FreeRTOS™ on an ATmega4809 and what advantages this might bring to your project. As mentioned in the appnote [AN3007](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en610121) you can see the different tasks running and interact with them using the virtual com port on your ATmega4809 Curiosity Nano or using the on board buttons. 