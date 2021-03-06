# Unibody FPV quad

![Quad photo](docs/3-4_photo_800x600.jpg)

A size class 400 FPV quadcopter assembled over a single piece FDM printable body, designed for long range freestyle FPV. Some highlights:

* Good FPV flight performances for its class due to high frame rigidity (comparable to frames made from single carbon fiber sheets) and relatively low inertia moment
* servo-operated tiltable FPV CCD camera mount with 180� mechanical range integrated in the unibody frame.
* Frame has dedicated fixing points for video TX, ESC, cables, antenna,...
* Fully documented: [BOM and exploded diagram](https://github.com/rb1205/unibody_fpv_quad/raw/master/docs/assembly.pdf) of the project with all components and screws located, for easy assembly. [Wiring diagram](https://github.com/rb1205/unibody_fpv_quad/raw/master/docs/wiring_diagram.pdf) is provided, too.
* Printable & easly replaceable landing gears

## Stats

* Made for 9" props
* Typical flight time is ~15-20 minutes with a 3300 mAh 4s battery. 
* Weight is 200g for the frame alone, ~700g for the assembled quad without battery and ~1000g with a 3300 mAh 4s lipo battery
* Inertia moments around CoG are around 1, 1 and 2 Kg/dm^2 (pitch,roll,yaw)
* Battery bay size=50x38x120 mm

Due to the frame size, you'll need a bigger-than-average printer with a minimum build envelope of 320x300x50mm to print the body.

CAD files are included in the project, software used is PTC Creo V.2. 

![Quad CAD model](docs/cad.png)

Here's a [Video](https://www.youtube.com/watch?v=QMW7MYOoSNg) with a (shitty) test flight.

## Documentation

[Modal analysis](docs/modal_analysis.md)

[Print instructions](docs/print_instructions.md)

[Exploded diagram with BOM](https://github.com/rb1205/unibody_fpv_quad/raw/master/docs/assembly.pdf)

[Wiring diagram](https://github.com/rb1205/unibody_fpv_quad/raw/master/docs/wiring_diagram.pdf)

[Reference flight controller settings for iNav](config_files) (valid only for the powertrain configuration listed in the BOM)

---

This project is released under the terms of [Creative Commons Attribution-NonCommercial license](https://creativecommons.org/licenses/by-nc/4.0/)

Please contact us at riccardo.belloli@inova-soluzioni.it to discuss commercial usage of this project.
