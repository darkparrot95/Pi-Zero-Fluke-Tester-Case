# Raspberry Pi Fluke Tester Case

## Overview

This repository contains the 3D printable files and project assets for a custom-designed case built for a Raspberry Pi–based Fluke tester project.

The goal of this case is to provide a clean, functional, and portable enclosure that securely houses the Raspberry Pi and supporting components while maintaining accessibility and usability for testing and field use.

This case was specifically designed around an existing Fluke tester project created by another developer. Full credit for the original electronics and concept goes to them https://github.com/MKWB (see below).

---

## Original Project Credit

This case is designed to support and complement the original project:

**Original Fluke Tester Project:**
👉 (https://github.com/MKWB/RaspberryFluke)

All software, wiring design, and core functionality belong to the original creator. This repository only contains the physical enclosure design and related print files.

---

## What's Included

### STL Files

These are ready-to-print files for your 3D printer:

* **Main Case Body** File name: Pi Zero POE Case.stl
  The primary enclosure that houses the Raspberry Pi and internal components.

* **Lid / Cover**  File name: Pi POE Top.stl
  The top section that encloses and protects the internals
  
* **Plug Caps / Interface Parts** File name: Pi Zero POE Plugs.stl
  Any external component designed to protect the unused I/O ports. These are friction fit, they hold themselves in, but can easily be popped out for access to ports or sd card.

* **Project & GCODE Files**
  Project and GCODE files can be opened directly inside of Bambu Studio.
  -File name: Pi Zero POE Gcode_Bambu_P1S_PLA_2h51m.gcode - Presliced GCODE file for PLA ! .16 High Quality - Print time right under 3 hours - Supports added as well and they break off clean if pulled when hot.
  -File name: Pi Zero POE Project Bambu.3mf - The project File that can just be opened in Bambu Studio with all the STL's on one plate - Use Split funtion if multiple parts are combined and you want to print in different colors
  -File name: Pi Zero POE Sliced Plate File.gcode.3mf - A sliced plate file exported from Bambu

---

### Bambu Studio Files (.3mf / project files)

These files are configured for use with Bambu Lab printers and include:

* Pre-configured print settings
* Orientation optimized for strength and print quality
* Supports (if required)
* Material and profile tuning

These are recommended if you're using a Bambu printer, as they remove most of the setup work.

---

## Assembly Notes

* Ensure proper alignment of ports before fully securing components
* Use appropriate screws for Raspberry Pi mounting - It should accomadate the screws that come with the POE case combo mentioned in his parts list
* Modify or sand slightly if your printer tolerances differ

---

## Purpose

This case was created to:

* Provide physical protection for components
* Improve usability with a clean and functional case
* Offer a printable solution for others building the same project

---

## Disclaimer

This enclosure is provided as-is. Minor adjustments may be required depending on your printer, hardware revisions, or tolerances.
This was printed on a Bambu Labs P1S and should work if you use my code

---

## Acknowledgments

Huge thanks to the (https://github.com/MKWB) for designing and sharing the Fluke tester project that made this build possible.

---
