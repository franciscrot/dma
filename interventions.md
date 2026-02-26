---
layout: default
title: Interventions
---

# Interventions

## Divestment and digital sovereignty {#digital-sovereignty}

<details markdown="1"><summary>Who owns and controls our everyday digital tools?</summary>

- Alphabet (Google) — Android; Google Play (app store); Chrome/Chromium (web standards); Google Search & Maps (discoverability); reCAPTCHA; Google Analytics; Google Cloud
- Apple — iOS; App Store; WebKit (browser engine); Apple Pay; Secure Enclave & firmware signing
- Microsoft — Windows; Microsoft 365 & Teams (workplace tools); Azure (cloud); GitHub + npm (software supply chain); Active Directory / Entra ID
- Amazon — AWS (cloud); Amazon Marketplace (SME dependence); Ring (home surveillance); Alexa; Twitch (live media infrastructure)
- Meta — Facebook & Instagram, WhatsApp (civic messaging); Meta Ads
- NVIDIA — GPUs & AI accelerators (compute bottleneck for AI, research, and defence)
- Taiwan Semiconductor Manufacturing Company — manufacturing choke point for Apple, NVIDIA, AMD, Qualcomm
- Tencent — WeChat & WeChat Pay (messaging + payments + mini-apps); Tencent Cloud
- Alibaba Group — Alibaba Cloud; Alipay (payments)
- Huawei — telecoms equipment (4G/5G/6G); network hardware
- Palantir - extensively used by governments

</details>

<details markdown="1"><summary>Resources</summary>

- add resources on digital sovereignty, US tech dominance, open source alternatives to major tools and systems, how to divest from using FANG systems, etc.
- [Authoritarian Stack](https://www.authoritarian-stack.info/)
- European Commission: [Shaping Europe’s Digital Future – Digital Sovereignty](https://digital-strategy.ec.europa.eu/en/policies/digital-sovereignty) 
- Free Software Foundation: [Free Software Directory](https://directory.fsf.org/wiki/Main_Page) 
- Switching Software: [Ethical and Open Source Alternatives](https://switching.software/) 
- [Briar Project](https://briarproject.org/) Secure messaging.
- [Prism Break](https://prism-break.org/en/) - anti-surveillance alternatives
- [King Avriel](https://www.instagram.com/kingavriel?igsh=MWIzbHV2Y3YwN2d0OQ==) Videos about de-Googlifying everyday life and other topics

</details>

## Security and IOT {#security-IOT}

<details markdown="1"><summary>How do the objects around us communicate with each other and with bigger systems?</summary>

- We are surrounded by invisible conversations between objects. Doors, phones, cars, printers, speakers, smart meters, routers, and other devices are constantly exchanging information.
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

<details markdown="1"><summary>Resources</summary>

- Flipper Zero: [Flipper Zero Official Documentation](https://docs.flipper.net/zero) 
- Flipper Zero: [Flipper Zero NFC Documentation](https://docs.flipper.net/zero/nfc) 
- Flipper Zero: [Flipper Zero Infrared Documentation](https://docs.flipper.net/zero/infrared) Explains how infrared remotes work and how to capture, analyse, and replay IR signals.
- Flipper Zero: [Flipper Zero GPIO & Modules Guide](https://docs.flipper.net/zero/gpio-and-modules) Introduces hardware interfacing, pins, and serial communication for understanding lower-level device signals.
- [RTL-SDR Quick Start Guide](https://www.rtl-sdr.com/rtl-sdr-quick-start-guide/)
- [Software Defined Radio with HackRF – Lesson 1](https://greatscottgadgets.com/sdr/1/) Foundational tutorial on how radio works and how SDR tools let you observe and experiment with signals.
- Proxmark3: [ Getting Started](https://github.com/Proxmark/proxmark3/wiki/Getting-Started) 
- Adafruit: [PN532 RFID/NFC Guide](https://learn.adafruit.com/adafruit-pn532-rfid-nfc)  
- Ubertooth: [Getting Started Guide](https://ubertooth.readthedocs.io/en/latest/getting_started.html) Introduction to Bluetooth packet capture and wireless protocol analysis.
- [OWASP Vulnerability Disclosure Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html) 
- [Nearby Glasses](https://play.google.com/store/apps/details?id=ch.pocketpc.nearbyglasses) is an app that tries to sense if smart glasses are being used nearby.

</details>


## Cryptography and cybersecurity {#cryptography-cybersecurity}

<details markdown="1">
  <summary>
    Add a question</summary>
  
- Add an answer
- That serves as an intro or hook for this topic

</details>

<details markdown="1">
  <summary>
    Resources</summary>
  
- Khan Academy: [Cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) 
- [CryptoHack](https://cryptohack.org/) 
- [OWASP Top Ten](https://owasp.org/www-project-top-ten/) Web application security risks.
- [Electronic Frontier Foundation – Surveillance Self-Defense](https://ssd.eff.org/) Personal digital security.
- [LASR Labs](https://www.lasrlabs.org/past-projects) 13-week research programme that aims to assist individuals in transitioning to full-time careers in AI Safety, and a repository of papers that have come out of the programme.

</details>

## Off-grid {#off-grid}

<details markdown="1">
  <summary>
    Add a question</summary>
- Add a response

</details>

<details markdown="1">
  <summary>
    Resources</summary>
  
- Low-tech Magazine: [Off-Grid Solar Guide](https://www.lowtechmagazine.com/solar/). Research-driven explorations of small-scale renewable systems
- [LibreSolar Project](https://libre.solar/) 
- Eco-Worthy [How to Build Off-Grid Solar](https://uk.eco-worthy.com/blogs/solar-panel-system/off-grid-solar-installation-guide)

</details>

## Media archaeology {#media-archaeology}

<details markdown="1">
  <summary>
    Add a question</summary>
- Answer

</details>

<details markdown="1">
  <summary>
    Resources</summary>

- [Media Archaeology Lab](https://mediaarchaeologylab.com/)
- [Dead Tech Lib](https://www.sussex.ac.uk/broadcast/read/68364)  
- Internet Archive: [Software Collection](https://archive.org/details/software) 
- SIGGRAPH Digital Art Archive: [History Resources](https://history.siggraph.org/). Documentation of early digital art and computing experiments
- [Jussi Parikka](https://jussiparikka.net/category/media-archaeology/)
- Ben Roberts and Mark Goodall (eds), [New Media Archaeologies](https://www.routledge.com/New-Media-Archaeologies/Roberts-Goodall/p/book/9781041183549)

</details>

## Bioacoustics {#bioacoustics}

<details markdown="1">
  <summary>
    Add a question</summary>
- Answer

</details>

<details markdown="1">
  <summary>
    Resources</summary>

- [Sensing the Forest: An Interview with Alice Eldridge](https://sensingtheforest.github.io/2024/02/05/an-interview-with-alice-eldridge/)
- [wilding.radio](https://wilding.radio/)
- [Xeno-canto](https://xeno-canto.org/) Open database of bird sounds from around the world.
- Cornell Lab of Ornithology: [Raven Lite](https://ravensoundsoftware.com/software/raven-lite/) Free software for sound visualisation and analysis.
- [Open Acoustic Devices](https://www.openacousticdevices.info/) Open-source hardware for long-term environmental audio recording.

</details>

## 3D Printing {#three-D-printing}

<details markdown="1">
  <summary>
    Add a question</summary>

- Answers
</details>

<details markdown="1">
  <summary>
    Resources</summary>

- Prusa Research: [3D Printing Handbook](https://www.prusa3d.com/page/3d-printing-handbook_1287/) 
- Ultimaker: [Cura Slicer Software](https://ultimaker.com/software/ultimaker-cura/) Open-source slicing tool 
- Thingiverse: [Open Design Repository](https://www.thingiverse.com/) Collection of printable object files

</details>

## Hardware repair {#hardware-repair}

<details markdown="1">
  <summary>Where to start?</summary>

- Disassemble and reassemble an old device – Take apart a spare phone or laptop and put it back together.
- Clean and inspect a device interior – Remove dust or residue with appropriate tools and learn to visually inspect a PCB for obvious damage or loose connectors.
- Practice  soldering and desoldering – Use a cheap practice board or kit to learn how to heat joints properly, apply solder cleanly, and remove solder.
- Swap a cracked screen.
- Build a LED circuit – Assemble a basic LED and resistor on a breadboard or perfboard.
- Learn to use a multimeter – Measure voltage, resistance, and continuity on batteries, cables, and simple circuits to build diagnostic skills.
- Replace a phone battery – A relatively contained repair that teaches safe opening, connector handling, and reassembly.
- Replace a simple modular part (e.g. speaker or camera module) – Practise part identification and clean installation without soldering.
- Identify the main parts inside a computer case – Open a second-hand PC and  locate the motherboard, RAM, storage drive, power supply, and cables. 
- Reseat RAM in an existing computer – Remove and reinsert RAM sticks.
- Replace or add a storage drive (SSD) – Install a 2.5" SSD or M.2 drive in a system. 

</details>

<details><summary>What are some common tools and terms?</summary>

- Device – An electronic machine such as a phone or computer that contains a power source, circuit boards, chips, and connectors all working together.
- Motherboard – The main, flat circuit board inside a computer, covered in slots, chips, and connectors; this is where you install and connect most parts when building a PC.
- Circuit – A pathway for electricity. In a computer, circuits appear as thin copper lines on a board and as microscopic structures inside chips. If a circuit is broken or shorted, the device will not work properly.
- CPU (Processor) – A small, flat square chip with a metal top and tiny contact pads or pins underneath. It feels solid and smooth and fits into a specific socket on the motherboard; inside are billions of microscopic circuits.
- RAM (Memory) – A long, thin stick of circuit board with small black chips attached and gold contacts along the edge. It clicks into slots on the motherboard and temporarily stores data while the computer runs.
- Chip (Integrated Circuit) – A small black rectangle or square soldered onto a board; it contains extremely tiny circuits etched into silicon, protected by its outer casing.
- Heat Sink / Cooler – A heavy metal block, often with fins and a fan, that sits on top of the CPU to draw heat away and prevent overheating.
- Connector / Slot – A shaped plastic socket with metal contacts inside, designed so parts like RAM, cables, or the CPU fit in securely and only in the correct orientation.
- Solder – A soft metal alloy that melts when heated and is used to permanently attach components to a circuit board.
- Soldering Iron – A pen-shaped heated tool used to melt solder when repairing or building electronic circuits.
  - Microcontroller – A tiny computer on a single chip that controls specific tasks inside a device, such as managing power, buttons, or sensors.
- [Spudger](https://en.wikipedia.org/wiki/Spudger) – A small plastic or nylon pry tool used to open devices and disconnect cables without scratching or shorting components.
- SMD (Surface-Mount Device) – A small electronic component soldered directly onto the surface of a circuit board, common in phones.
- PCB (Printed Circuit Board) – The main board inside a device that holds components and connects them using thin copper tracks.
- Flux – Used during soldering to help solder flow smoothly and form strong electrical connections.
- Hot Air Rework Station – A tool that blows controlled hot air to remove or attach small surface-mounted components.
- Multimeter – A handheld tester used to measure voltage, resistance, and continuity when diagnosing faults.
- BGA (Ball Grid Array) – Type of chip attached underneath with tiny solder balls.
- Ribbon (Flex) Cable – Thin, flexible cable that connects parts like screens or cameras to the main board.
- ESD (Electrostatic Discharge) – Static electricity that can damage electronics. anti-static mats and wrist straps can help. prevent it.
</details>

<details markdown="1">
  <summary>Resources</summary>

- [iFixit](https://www.ifixit.com/) Wiki-style collection of step-by-step phone repair instructions and teardowns for many common device models.
- Stanford: [Intro to soldering](https://sites.google.com/stanford.edu/soldering-internal/learning)
- Adafruit: [Solderless Breadboards](https://www.adafruit.com/category/462)
- My Computer Works: [A beginner's guide to DIY device repair tools](https://www.mycomputerworks.co.uk/a-beginners-guide-to-diy-device-repair-tools-in-2024/)
- Sussex Green Living: [Repair Cafes](https://www.sussexgreenliving.org.uk/repair/)
- [Brighton Borrowers](https://www.brightonborrowers.co.uk/)
- [Electronics Repair School](https://www.youtube.com/c/Electronicsrepairschool)
  
</details>

## Hackathons and Makerspaces {#hackathons-makerspaces}

<details markdown="1">
  <summary>What are hackathons, makerspaces, and jams?</summary>

- A hackathon is a time-bounded collaborative event — often 24–72 hours — where participants prototype software, hardware, or research ideas.
- A makerspace is a shared workshop providing tools such as 3D printers, laser cutters, electronics benches, and hand tools for community use.
- A game jam or design jam focuses on rapid creative production around a theme or constraint.
- Maker culture grew from DIY electronics, open hardware movements, and early hackerspaces in the 2000s.
- These spaces can support peer learning, open innovation, and experimentation outside formal institutional settings.

</details>

<details markdown="1">
  <summary>Resources</summary>

- Hackaday: [Hackaday.io Projects](https://hackaday.io/projects) Community-documented hardware and electronics builds.
- Fab Foundation: [Fab Lab Network](https://fabfoundation.org/) Global network of digital fabrication labs.
- Global Game Jam: [Official Site](https://globalgamejam.org/) Annual worldwide game jam with resources and archives.

</details>
