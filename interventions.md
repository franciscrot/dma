---
layout: default
title: Interventions
---

# Interventions

## Security and IOT {#security-IOT}

<details><summary>How do the objects around us communicate with each other and with bigger systems?</summary>

- We are surrounded by invisible conversations between objects. Doors, phones, cars, printers, tills, and routers are constantly exchanging information.
Information must travel through something physical. It moves through wires (USB, Ethernet), light (a TV remote’s infrared flashes), or radio waves (Wi-Fi, Bluetooth, car key fobs).
- The **Flipper Zero** is an example of a device for experimenting with these signals. It can read and generate infrared, RFID, NFC, and certain sub-GHz radio signals, helping make invisible systems visible.
- **Security research** is learning how these layers, signals, and infrastructures fit together, then testing them safely and legally. You observe, measure, document, and question assumptions — usually on your own devices or with permission.
- A **signal** is simply timed changes — flashes of light, pulses of voltage, bursts of radio. Meaning comes from the pattern.
- To understand each other, devices follow agreed rules called **protocols**. If both sides use the same format and timing rules, a pattern becomes a message like “unlock” or “pay £3.50.”
- **RFID** (Radio-Frequency Identification) is a way for small tags to communicate using radio waves. A card or sticker has a tiny chip and antenna; a reader powers it - wirelessly and reads its data. Bus passes, library books, and warehouse tags use RFID.
- Different wireless systems use **different parts of the radio spectrum**. Wi-Fi and Bluetooth often use 2.4 GHz; many garage or car fobs use lower frequencies like 433 MHz. They don’t clash because they’re in different “lanes.”
- Many everyday systems rely on tokens and identity. A contactless card, hotel key, or building pass may present a serial number — sometimes with strong cryptography, sometimes not.
- Some signals can be replayed, whereas others are designed not to be. A basic infrared remote often works if copied. Many car fobs use rolling codes so that yesterday’s signal will not work today.
- Every system has layers. Hardware (chips and antennas), firmware (device code), software (apps), and backend servers. Each of these layers may have security vulnerabilities.
- Infrastructure often joins small devices to larger systems. For example, the BEEP! of a badge reader may connect to a building controller, which then connects to a database that decides who can enter.
- NFC (Near Field Communication) is a short-range form of RFID. It works at 13.56 MHz and only over a few centimetres, which is why you have to tap your bank card or phone close to the reader.
- An SDR (Software-Defined Radio) is a radio you control with software. Instead of being built for one purpose like a Wi-Fi chip, it lets you tune across frequencies and visualise signals — like turning the air into something you can see on a screen.
- IoT (Internet of Things) refers to everyday objects connected to the internet. Smart plugs, thermostats, doorbells, and lightbulbs all contain small computers that send and receive data.
- IoT devices combine physical sensors with networks. A smart thermostat measures temperature, sends that data over Wi-Fi, and receives instructions from an app or cloud service.

</details>

<details><summary>Resources</summary>

- Flipper Zero: [Flipper Zero Official Documentation](https://docs.flipper.net/zero) Comprehensive guide to the device’s features, interfaces, and basic operation, ideal for beginners starting hands-on exploration.
- Flipper Zero: [Flipper Zero NFC Documentation](https://docs.flipper.net/zero/nfc) Clear introduction to how NFC works on the device, including tag types, data structures, and safe experimentation.
- Flipper Zero: [Flipper Zero Infrared Documentation](https://docs.flipper.net/zero/infrared) Explains how infrared remotes work and how to capture, analyse, and replay IR signals.
- Flipper Zero: [Flipper Zero GPIO & Modules Guide](https://docs.flipper.net/zero/gpio-and-modules) Introduces hardware interfacing, pins, and serial communication for understanding lower-level device signals.
- [RTL-SDR Quick Start Guide](https://www.rtl-sdr.com/rtl-sdr-quick-start-guide/) Beginner-friendly introduction to Software-Defined Radio and visualising radio signals across frequencies.
- [Software Defined Radio with HackRF – Lesson 1](https://greatscottgadgets.com/sdr/1/) Foundational tutorial on how radio works and how SDR tools let you observe and experiment with signals.
- Proxmark3: [ Getting Started](https://github.com/Proxmark/proxmark3/wiki/Getting-Started) Practical guide to advanced RFID/NFC research workflows beyond entry-level tools.

- Adafruit: [PN532 RFID/NFC Guide](https://learn.adafruit.com/adafruit-pn532-rfid-nfc)  Explanation of how RFID and NFC hardware operate, with diagrams and examples.

- Ubertooth: [Getting Started Guide](https://ubertooth.readthedocs.io/en/latest/getting_started.html) Introduction to Bluetooth packet capture and wireless protocol analysis.

- [OWASP Vulnerability Disclosure Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html) Clear guidance on responsible disclosure, reporting vulnerabilities safely and ethically.


</details>


## Cryptography and cybersecurity {#cryptography-cybersecurity}

## Off-grid {#off-grid}

## Media archaeology {#media-archaeology}

## Bioacoustics {#bioacoustics}

## 3D Printing {#three-D-printing}

## Hackathons and Makerspaces {#hackathons-makerspaces}
