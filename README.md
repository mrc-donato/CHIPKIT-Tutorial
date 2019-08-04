# Tutorial on Agile Research Test Chips

![alt text](/Chip_gallery.png)

## Overview

Research test chips are the ultimate experiment to demonstrate the true value of novel computer architecture innovations. They are always very highly regarded by reviewers as the most honest evaluation of a new hardware proposal.  In addition, there is a huge pedagogical value in taping out test chips, as it offers insight on the impact of real hardware and microarchitecture details that are critical in guiding higher level architecture decisions and trade offs.  Nonetheless, despite all this, taping out test chips remains a challenge for those who are following this path for the first time.  Traditionally, research chips have been time consuming to design, fabricate and test, and often error prone - potentially requiring re-spins to fix problems.

This tutorial sets out to present a clear and straightforward template for a modern design flow for rapid, agile, and successful tape out of research test chips. We describe a front-to-back design example, drawing on many generations of test chips (shown in the illustration below) following a consistent design approach [1], [2], [3], [4], [5].  To help researchers start up their own SoC designs, the content of this tutorial is supported with the release of our **CHIPKIT** project, which provides a comprehensive set of open source resources for the design and implementation of research tapeouts. The project includes a sample SoC design which leverages this design methodology for demonstrating novel specialized hardware architectures, using the **CHIPKIT** infrastructure.

## Outline

* The value of research test chips: fabrication routes, process technologies, project planning
* Test chip architectures: CPUs, peripherals, memories, interconnects and frameworks
* Design methodologies for custom blocks: Verilog, SystemVerilog, HLS and beyond
* Physical design flow: linting, synthesis, place and route, DRC/LVS, timing closure
* Bring up and test: packaging, PCBs, clocking, testing flows
