# OpenCore Setup

This is my personal configuration for running a Hackintosh using [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg/releases).

![Setup Screenshot](Images/Setup.png)

![Case Photo](Images/Case.png)

I am uploading this as a public repository for two purposes:
1. Allow myself to keep track of changes I make and back them up.
2. Allow others with similar hardware to find a _possibly_ suitable configuration.

# Target

This configuration last tested on macOS 12.0 Beta (21A5268h).

Previous configurations:

* [macOS Catalina](https://github.com/emsquared/OpenCore-Setup/releases/tag/macOS-Catalina)
* [macOS Big Sur](https://github.com/emsquared/OpenCore-Setup/releases/tag/macOS-Big-Sur)

# Hardware

* **Case**: [Fractal Design Define R6](https://www.amazon.com/gp/product/B07HQKF7F2/)
* **Power**: [EVGA SuperNOVA 1000 G2](https://www.amazon.com/gp/product/B00CGYCNG2/)
* **Motherboard**: [Gigabyte Z390 AORUS PRO](https://www.amazon.com/gp/product/B07HRZRBRJ/)
* **Processor**: [Intel 9900K**F**](https://www.amazon.com/gp/product/B07MGBZWDZ/)
* **Graphics**: [MSI AMD Radeon RX 6800 GAMING X TRIO 16GB](https://www.microcenter.com/product/632560/msi-amd-radeon-rx-6800-gaming-x-trio-overclocked-triple-fan-16gb-gddr6-pcie-40-graphics-card)
* **Memory**: [HyperX Fury 32GB (2 x 16GB) 3200MHz DDR4](https://www.amazon.com/gp/product/B07WJJJ5M6/)
* **Primary Storage**: [Samsung SSD 850 EVO 500GB](https://www.amazon.com/gp/product/B00OBRE5UE/)
* **Bootcamp Storage**: [Samsung SSD 860 EVO 1TB](https://www.amazon.com/gp/product/B078DPCY3T/) (larger space for games)
* **Secondary Storage**: 4TB hard disk storage (7200rpm)
* **Display**: [Nixeus EDG 27" 1440p IPS display (NX-EDG27S v2)](https://www.amazon.com/gp/product/B07N4DL9F7/)

None of this hardware is overclocked.

_Note: My CPU comes without integrated graphics because it was cheaper and I have a dedicated GPU. **I therefore do not know if this configuration will work with integrated graphics.**_

Wifi and Bluetooth work with zero configuration, out of the box, using [this card](https://www.amazon.com/gp/product/B012LOT512/r).

# Water cooling 

## Frequently Asked Questions

### Why don't you water cool your GPU?

My former GPU was water cooled. That's why there is an extension in the middle of one of the tubes. When that GPU failed, there weren't many options on the market for a new one. I had to settle for one that does not have a water block for sale. I will swap it out for a more favorable GPU when the market is in better shape.

## Components 

| Product | Quantity |
| --- | --- |
| [EK-Velocity - Nickel + Acetal](https://www.ekwb.com/shop/ek-velocity-nickel-acetal) | 1 |
| [EK-XRES 140 Revo D5 PWM - Glass](https://www.ekwb.com/shop/ek-xres-140-glass-revo-d5-pwm-incl-pump) | 1 |
| [EK-UNI Pump Bracket (140mm FAN) Vertical](https://www.ekwb.com/shop/ek-uni-pump-bracket-140mm-fan-vertical) | 1 |
| [EK-CoolStream SE 360 (Slim Triple)](https://www.ekwb.com/shop/ek-coolstream-se-360-slim-triple) | 1 |
| [EK-Meltemi 120ER Black](https://www.ekwb.com/shop/ek-meltemi-120er-black-500-1800rpm) | 3 |
| [EK-Cable Y-Splitter 3-Fan PWM (10cm)](https://www.amazon.com/EKWB-EK-Cable-Y-Splitter-3-Fan-2-Pack/dp/B078G53932) | 1 |
| [EK-Tube ZMT Matte Black 16,1/11,1mm 3M](https://www.ekwb.com/shop/ek-tube-zmt-matte-black-16-1-11-1mm-3m-retail) | 1 |
| [EK-CryoFuel Clear (Premix 1000mL)](https://www.ekwb.com/shop/ek-cryofuel-clear-premix-1000ml) | 1 |
| [EK-Torque STC-12/16 - Black](https://www.ekwb.com/shop/ek-torque-stc-12-16-black) | 8 |
| [EK-Torque Angled 90° - Black](https://www.ekwb.com/shop/ek-torque-angled-90-black) | 3 |
| [EK-AF Angled 90° G1/4 Black](https://www.ekwb.com/shop/ek-af-angled-90-g1-4-black) | 2 |
| [EK-AF Angled 45° G1/4 Black](https://www.ekwb.com/shop/ek-af-angled-45-g1-4-black) | 1 |
| [EK-AF Ball Valve (10mm) G1/4 - Black](https://www.ekwb.com/shop/ek-af-ball-valve-10mm-g1-4-black) | 1 |
| [EK-AF T-Splitter 3F G1/4 - Black](https://www.ekwb.com/shop/ek-af-t-splitter-3f-g1-4-black) | 1 |
| [EK-AF Extender 6mm M-M G1/4 - Black](https://www.ekwb.com/shop/ek-af-extender-6mm-m-m-black) | 2 |
| [EK-AF Extender 30mm M-F G1/4 - Black](https://www.ekwb.com/shop/ek-af-ball-valve-10mm-g1-4-black) | 4 |
| [EK-AF Extender Rotary M-F G1/4 - Black](https://www.ekwb.com/shop/ek-af-extender-rotary-m-f-g1-4-black) | 3 |

# Disclaimer

I am a novice when it comes to building a hackintosh. I do not understand a lot of what happens behind the scenes. This configuration is a combination of the helpful [vanilla guide](https://dortania.github.io/OpenCore-Install-Guide/) and [reading the entire docuemtnation](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf).

**I DO NOT provide any guarantees for this setup outside of my own use case.**
