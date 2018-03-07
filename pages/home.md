---
layout: main
lang: en
permalink: /
title: The Embedded RISC-V Project
author: Liviu Ionescu

date: 2018-02-28 23:20:00 +0300

---

## Mission statement

Define a **modern C/C++ friendly microcontroller architecture** based on the RISC-V instruction set, that makes writing embedded software **easier and more productive**. And... enjoy the process!

In technical terms, the mission statement can be rephrased as: define a set of specifications for **RISC-V microcontrollers** intended for **embedded real-time** / **low power** / **IoT** applications that do not require an operating system. Favour **C/C++** multi-threaded **RTOS** systems.

## Preliminary specs

For convenience, the initial proposal for the **RISC-V Microcontroller Profile** specification uses the markdown syntax, and is available as the [specs-markdown](https://github.com/emb-riscv/specs-markdown/blob/master/README.md) GitHub project.

Contributions are welcome in the project [issues](https://github.com/emb-riscv/specs-markdown/issues) ar [pull requests](https://github.com/emb-riscv/specs-markdown/pulls).

## Project plan

The following steps are considered for the Embedded RISC-V project:

- incorporate feedback from the open source community and possibly from the industry and finalize the specifications
- implement a version in QEMU and port a RTOS ([µOS++](https://github.com/micro-os-plus)) to test the context switching mechanism
- synthesize a Verilog version that runs on the Arty board, similar to E31Arty/E51Arty bitstreams
- work together with the industry and create physical devices

## License

Similarly to the RISC-V specs license, the **RISC-V Microcontroller Profile** specs are also provided free of charge under the terms of the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) license, with all rights reserved to Liviu Ionescu.

Unless otherwise mentioned, all other content is also provided free of charge under the terms of the [MIT License](https://opensource.org/licenses/MIT), with all rights reserved to Liviu Ionescu.

