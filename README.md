# BlueMicro833

### What is BlueMicro833?

BlueMicro833 is a nRF52833 breakout board with the form factor of an Arcuino Pro Micro


### Hardware License

Design of BlueMicro833 is licensed under **CERN Open Hardware Licence Version 2 - Weakly Reciprocal**

See license.txt for more details. See this [FAQ](https://ohwr.org/project/cernohl/wikis/faq#q-copyright-does-not-cover-hardware-how-do-you-implement-strongly-reciprocal-licensing-in-cern-ohl-s) for more information on this license.


### Licenses from reference material and libraries

|  Item  | Description | Source  | License  |
|----|----      | :-----  | :-------- |
| kicad libraries | Core libraries from Kicad | [link](https://www.kicad.org/libraries/license/) | CC-BY-SA 4.0 (with exception)|
| kicad libraries | switch symbols and footprints | [link](https://github.com/sszczep/kicad-libraries)| MIT | 


### openmoko-usb-oui application details

[USB PID Request](https://github.com/openmoko/openmoko-usb-oui)

1. (done) Have a README[.txt|.md] file describing which part is under which license this will help to quickly identify the project's license, particularly when several licenses are combined, or your are using libraries under other licenses. Also make sure the combination is allowed by the individual licenses.
2. (done) Include all full text licenses in a LICENSE[.txt] file
3. (done) Include a copyright notice in the schematic sheet(s), including author and date this will determine who the copyright holder is, and when the copyright will expire.
4. (done) Include the license name in the schematic sheet(s) this becomes important when different license are combined, and parts of the project, or libraries, are under different licenses
5. () Include all schematic symbols and board footprint libraries in the project without that the project can't be seen as complete. Also ensure their license is compatible.
66. (done) Export the schematic capture as pdf, and board layout as gerber+NC drill [and other fabrication output] files - not every user can, or wants, to install the EDA suite you are using. This is even more important if in the future this suite stops supporting the current format. If you don't want to mix the fabrication output with the source files, have a general project page pointing to the source files and fabrication output.