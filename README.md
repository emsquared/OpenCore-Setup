# OpenCore Setup

This is my personal configuration for running a Hackintosh using [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg/releases).

![Setup Screenshot](https://raw.githubusercontent.com/emsquared/OpenCore-Setup/master/Images/Setup.png)

![Case Photo](https://raw.githubusercontent.com/emsquared/OpenCore-Setup/master/Images/Case.png)

I am uploading this as a public repository for two purposes:
1. Allow myself to keep track of changes I make and back them up.
2. Allow others with similar hardware to find a _possibly_ suitable configuration.

# Hardware

* **Case**: [Fractal Design Define R6](https://www.amazon.com/gp/product/B07HQKF7F2/)
* **Power**: [EVGA SuperNOVA 1000 G2](https://www.amazon.com/gp/product/B00CGYCNG2/)
* **Motherboard**: [MSI MPG Z390 GAMING PLUS](https://www.amazon.com/MSI-MPG-Z390-LGA1151-Motherboard/dp/B07HMG1XP7/)
* **Processor**: [Intel 9900K**F**](https://www.amazon.com/gp/product/B07MGBZWDZ/)
* **Graphics**: [XFX Radeon VII 16GB](https://www.amazon.com/gp/product/B07NFGDZWQ/)
* **Memory**: [HyperX Fury 32GB (2 x 16GB) 3200MHz DDR4](https://www.amazon.com/gp/product/B07WJJJ5M6/)
* **Primary Storage**: [Samsung SSD 850 EVO 500GB](https://www.amazon.com/gp/product/B00OBRE5UE/)
* **Bootcamp Storage**: [Samsung SSD 860 EVO 1TB](https://www.amazon.com/gp/product/B078DPCY3T/) (larger space for games)
* **Secondary Storage**: 4TB hard disk storage (7200rpm)
* **Display**: [Nixeus EDG 27" 1440p IPS display (NX-EDG27S v2)](https://www.amazon.com/gp/product/B07N4DL9F7/)

None of this hardware is overclocked.

_Note: My CPU comes without integrated graphics because it was cheaper and I have a dedicated GPU. **I therefore do not know if this configuration will work with integrated graphics.**_

Wifi and Bluetooth work with zero configuration, out of the box, thanks to [this card](https://www.amazon.com/gp/product/B012LOT512/r).

# What Doesn't Work

* `NVRAM` doesn't work. I could emulate it but I do not like the current solution. It is very hacked together. Lack of `NVMRAM` hasn't presented an inconvinence.
* Onboard audio doesn't work. My speakers are plugged in through my monitor and my headset is USB so I did not take the time to setup `AppleALC` or other patches.

# Disclaimer

I am a novice when it comes to building a hackintosh. I do not understand a lot of what happens behind the scenes. This configuration is a combination of the helpful [vanilla guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/) and [reading the entire docuemtnation](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf).

**I DO NOT provide any guarantees for this setup outside of my own use case.**
