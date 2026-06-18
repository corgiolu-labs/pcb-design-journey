# 🛠️ PCB Design Journey — from etched boards to professional EDA

A ~20-year progression as a PCB designer, in three stages: a **self-taught hobbyist** (home photo-etching + PAD2PAD) → **KiCad** for my own engineering projects → professional **CADSTAR** at Leonardo. This repo shows the early hobby work and the path that followed.

<p align="center">
  <img src="docs/images/eda-journey.svg" width="860"><br>
  <em>Three stages, growing complexity and rigor — from DIY etching to enterprise EDA.</em>
</p>

## Stage 1 — Self-taught roots: photo-etching + PAD2PAD

Long before any professional tool, I designed and built PCBs at home — **photo-etching** and toner-transfer, single- and double-sided — laying the boards out in **PAD2PAD**. Over the years that became **470+ board designs**: RF (FM transmitters, VFO+PLL, receivers, radio-control), oscillators (Colpitts, Hartley), and test instruments (frequency meters, LC meters, power supplies, transistor testers).

This is where the fundamentals were learned *by doing* — routing, ground management, footprints, and designing for the constraints of home fabrication.

<p align="center">
  <img src="docs/images/pad2pad-gallery.jpg" width="900"><br>
  <em>A dozen of the 470+ boards — RF, oscillators, instruments and power supplies (PAD2PAD layouts). Individual layouts in <a href="docs/images/boards">docs/images/boards</a>.</em>
</p>

## Stage 2 — KiCad: my own engineering projects

I moved to **KiCad** (open-source professional EDA) for my own embedded projects — schematic capture, multilayer layout and Gerber output, with proper design-rule and footprint discipline.

A worked example is the **[UAV LoRa transponder](https://github.com/corgiolu-labs/uav-lora-transponder)** — an 868 MHz LoRa safety transponder for civil drones (ESP32 / Arduino Nano + EByte E220 + GPS), whose boards were designed in KiCad (schematics and wiring are in that repo).

## Stage 3 — CADSTAR: professional, at Leonardo

At **Leonardo** I design PCBs professionally in **Zuken CADSTAR** — enterprise EDA for **multilayer, RF / high-speed, high-reliability** boards: formal design rules, design-for-manufacturability, and the full cycle from schematic to **integration and validation** of radar subsystems.

> *This stage is shown by skills, not artifacts — those designs are the company's and are not reproduced here. The journey is the point: the same instincts learned etching boards at home now apply on enterprise tooling.*

## Skills across the journey

Schematic capture · multilayer PCB layout · RF / analog · ground planes & impedance · DFM · photo-etching & home fabrication · Gerbers · **EDA tools: PAD2PAD · KiCad · CADSTAR** · from prototype to production.

## Author

**Alessandro Corgiolu** — System / Embedded Integration & Validation Engineer
GitHub [@corgiolu-labs](https://github.com/corgiolu-labs) · part of a hardware portfolio that includes [JONNY5](https://github.com/corgiolu-labs/jonny5), the [UAV LoRa transponder](https://github.com/corgiolu-labs/uav-lora-transponder), the [DED powder-flow sensor](https://github.com/corgiolu-labs/ded-powder-flow-sensor), the [ESP32 radar](https://github.com/corgiolu-labs/esp32-radar-tracking) and [RASPYNVERTER](https://github.com/corgiolu-labs/raspinverter).
