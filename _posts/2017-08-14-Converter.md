---
title: 'Design of a Back-to-back Converter'
date: 2017-08-14
permalink: /posts/2017/08/14/Converter
tags:
  - cool posts
  - category1
  - category2
---
The laboratory I am currently working in needs to build a platform for motor drive experiences. In the establishment process I independently design and build the required back-to-back converter. The converter mainly functions as an output of 5A rated current and it is capable of EtherCAT communication. In the design process I am responsible for the design of the main circuit, controller, measuring and feedback circuit of the converter.

The DIPIPM module from the Mitsubishi Electric is chosen for the main circuit, as it has a 35A rated current output which meets the requirement for the platform and effectively reduces the design work. Configuring the module following the instructions, I devise the isolation power supply and the optocoupler isolation drive. While completing the schematic diagram, I also finish the design of the PCB layout for main circuit.
For the controller circuit, the Infineon XMC4800 chip is used in the design, and the schematic diagram is finished basing on the circuit diagram of the controller for XMC4400 converter, the PCB of which is designed by professional engineers. 
The measuring circuit is the common schematic diagram for measuring the voltage and the current. Above this, I also finish the PCB layout design and soldering job.

Headings are cool
======

You can have many headings
======

Aren't headings cool?
------