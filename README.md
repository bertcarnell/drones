# drones
Notes on the Development of Autonomous Drones for Christmas

## Brown University - [CS1951R - Introduction to Robotics](https://cs.brown.edu/courses/cs1951r/website_2017/#page-top) - Stefanie Tellex

Our first attempt was to recreate the development of this [drone]() from Brown University.

### [Parts List](https://cs.brown.edu/courses/cs1951r/website_2017/projects/build/parts.html)
I tried to get all the parts on the list, but had to find some alternatives.  Here is exactly what I bought:

- [Amazon](https://www.amazon.com/)
  - (x1) Micro USB Cable, CableCreation Short USB 2.0 to Micro USB Cable, High-Speed A Male to Micro B, Triple Shielded Cable, 15CM /Black Color
  - (x1) RipaFire 5V 3A UBEC-3A DC-DC Buck Module Step Down Converter for FPV TUZ UBEC285
  - (x1) Arducam 5 Megapixels 1080p Sensor OV5647 Mini Camera Video Module for Raspberry Pi Model A/B/B+, Pi 2 and Raspberry Pi 3,3B+
  - (x1) Samsung 32GB 95MB/s (U1) MicroSD EVO Select Memory Card with Adapter (MB-ME32GA/AM)
  - (x1) Raspberry Pi 3 Model B Motherboard
  - (4x) EMAX 4X SimonK 12A Brushless ESC Speed Controller for FPV QAV250 200 Multi-Rotor
  - (1x) CanaKit 5V 2.5A Raspberry Pi 3 B+ Power Supply / Adapter (UL Listed)
- [HobbyKing](https://hobbyking.com/)
  - (x2) DYS SE1806-2550KV RACE EDITION BRUSHLESS MOTOR 3~4S (CCW)	206000131-0
  - (x2) DYS SE1806-2550KV RACE EDITION BRUSHLESS MOTOR 3~4S (CW)	206000130-0
  - (x2) DIATONE POLYCARBONATE 3-BLADE PROPELLERS 5040 (CW/CCW) (ORANGE) (2 PAIRS)	366000203-0
  - (x2) TURNIGY 1500MAH 3S 20C LIPO PACK	T1500.3S.20
  - (x1) 4MM BANANA PLUG TO 6 X MALE XT60 IN PARALLEL	PC-XT60
  - (x1) HOBBYKING FPV250 V4 GREEN GHOST EDITION LED NIGHT FLYER FPV DRONE (GREEN) (KIT)	366000034-0
  - (x1) SKYLINE32 ACRO FLIGHT CONTROLLER W/BASEFLIGHT & CLEANFLIGHT	045000040-0
- [DigiKey](https://www.digikey.com/)
  - (x1) SHARP 2Y0A21YK0F IR DIST SENS
  - (x1) EVAL BOARD ADS1015 12-BIT ADC

### Missing Parts List
These parts are mentioned in the directions, but were not on the parts list:

- solder + soldering iron for electonic components
- [3mm shrink wrap + heat gun](https://www.amazon.com/uxcell-Polyolefin-Insulation-Shrink-Tubing/dp/B008DFW8JA)
- [double sided foam tape](https://www.amazon.com/3M-Natural-Polyurethane-Double-Coated/dp/B00P2B9QC0/ref=sr_1_20?s=industrial&ie=UTF8&qid=1545785189&sr=1-20&keywords=double+sided+foam+tape)
- Y, Gr, Bl 24 AWG stranded wire
- [2x6 female header](https://www.amazon.com/Adafruit-GPIO-Header-Raspberry-Pi/dp/B01BMRCPZW/ref=sr_1_fkmr1_2?s=industrial&ie=UTF8&qid=1545785250&sr=1-2-fkmr1&keywords=2x6+female+header+gpio) (to connect to the GPIO pins on the Raspberry Pi)
- [3 pin IR camera connector](https://abra-electronics.com/sensors/sensor-cables/805-28995-sharp-ir-sensor-to-servo-cable-805-28995.html) (one did not come with the IR camera)
- [USB Afro ESC flashing tool](https://abra-electronics.com/sensors/sensor-cables/805-28995-sharp-ir-sensor-to-servo-cable-805-28995.html) (to flash the firmware on the ESCs)
- [Raspberry Pi heat sinks](https://www.amazon.com/Raspberry-Heatsink-Lanpu-Performance-conductive/dp/B07D15MDXH/ref=sr_1_2_sspa?s=industrial&ie=UTF8&qid=1545785782&sr=1-2-spons&keywords=raspberry+pi+heatsink&psc=1)
- [Turnigy LiPo charger](https://www.amazon.com/Multi-function-Battery-Digital-Balance-Charger/dp/B07H2YFX6V/ref=sr_1_6?s=industrial&ie=UTF8&qid=1545785888&sr=1-6&keywords=lipo+charger) (to charge the batteries)

## CrazyFlie

### Parts List

- BitCraze
  - STEM drone bundle

