Riscflight is flight controller software (firmware) used to fly multi-rotor craft and fixed wing craft. It is a fork of Betaflight to the Risc-V processor family, initial development is using the K210 SOC on Seeed Maix boards.

The first milestone is to get it to the point that I can get a quad in the air, and hopefully some people crazy enough to test how it flys. I plan on keeping version numbering in parity with Betaflight.

## Alpha 1 - Roadmap (Initial Port)

- 4.2-K210-M1 - Getting it building in 32 bit mode
- 4.2-K210-M2 - IO and PID loop/Gyro on different cores
- 4.2-K210-M3 - ESC communication working
- 4.2-K210-M4 - Full IMU support
- 4.2-K210-M5 - Receiver Support
- 4.2-K210-M6 - VTX/DJI Support
- 4.2-K210-M7 - Publishing how to DIY your own setup

If it's working well enough at this point, I may request merging the port back into upstream and leave the work below for it's own branch in upstream.

- 4.2-K210-M8 - Riscflight Configurator Port
- 4.2-K210-A1 - Alpha 1 Release



## Alpha 2 - Roadmap (64 bit mode)

- 4.2-K210-64-M1 - 64 bit building
- 4.2-K210-64-M2 - IO and PID loop/Gyro - 64 bit
- 4.2-K210-64-M3 - ESC communication - 64 bit
- 4.2-K210-64-M4 - Full IMU support - 64 bit
- 4.2-K210-64-M5 - Receiver Support - 64 bit
- 4.2-K210-64-M6 - VTX/DJI Support - 64 bit
- 4.2-K210-64-A2 - Alpha 2 Release

## Alpha 3 - K210 - Neural Core Filtering


## Betaflight (Upstream project)

https://github.com/betaflight/betaflight/releases

## Open Source / Contributors

Riscflight is software that is **open source** and is available free of charge without warranty to all users.

Riscflight is forked from Betaflight, so thanks goes to all those whom have contributed to Betaflight and its origins.

Origins for this fork (Thanks!):
* **Alexinparis** (for MultiWii),
* **timecop** (for Baseflight),
* **Dominic Clifton** (for Cleanflight),
* **borisbstyle** (for Betaflight), and
* **Sambas** (for the original STM32F4 port).

The Riscflight Configurator is forked from Betaflight Configurator and its origins.

Origins for Betaflight Configurator:
* **Dominic Clifton** (for Cleanflight configurator), and
* **ctn** (for the original Configurator).

Big thanks to current and past contributors:
* Budden, Martin (martinbudden)
* Bardwell, Joshua (joshuabardwell)
* Blackman, Jason (blckmn)
* ctzsnooze
* Höglund, Anders (andershoglund)
* Ledvina, Petr (ledvinap) - **IO code awesomeness!**
* kc10kevin
* Keeble, Gary (MadmanK)
* Keller, Michael (mikeller) - **Configurator brilliance**
* Kravcov, Albert (skaman82) - **Configurator brilliance**
* MJ666
* Nathan (nathantsoi)
* ravnav
* sambas - **bringing us the F4**
* savaga
* Stålheim, Anton (KiteAnton)

And many many others who haven't been mentioned....
