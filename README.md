## CS 1D Design Thinking Project
This project aims to design and build a prototype of an electronic game using OMEGA-16, a 16-bit ALU implemented using Alchitry Au FPGA.

#### Part 1: MHP
The goal is to make a 1-bit FULL adder using basic logic gates and solder te circuit on a stripboard
<br /> **Mini & Electronic Hardware Prototype:**
<br /><img src="https://github.com/wanq27/cs-1d-game/assets/118462447/284177de-c3f9-4311-b05b-95022fd65e38" width="700"/>

#### Part 2: EHP
The goal is to build an electronic game using OMEGA-16. 

> Constraints
**You can only use the Alchitry Au FPGA** (or MOJO FPGA if you spoiled your precious Au), no other **general purpose microcontrollers**: **any programmable / versatile IC** 

- **This means: No Arduino, ESP, Raspberry Pi, PIC , or equivalent microcontrollers that have complex microprocessors or capability to decode pre-programmed animations (or sound)**
- You can use a selected **serial** to **parallel** **interface** to make your life easier, such as **74HC595**, **HUB75**, or *equivalent*. You **can also use** MAX7219 but with its decode functionality disabled. When in doubt, send your inquiries to Natalie
- You **need** to write your own drivers to interface with these parallel or serial interfaces
- **The Br reference schematic is different from original Alchitry due to our custom PCB. [Use our NEW one here](https://drive.google.com/file/d/1T3Vth8YpqDq1iOcPEW6TWjwVH0-h-59C/view?usp=sharing). This document can also be found in the folder linked above**

#### 2D Project
The task now involves enhancing the hardware for better energy efficiency and data handling, while redesigning the game's interface for a broader audience. The objectives are to minimize technical and financial challenges in prototype development, and to maximize user engagement with an intuitive, inclusive UI/UX design. We aim to refine game elements like the risk/reward system for diverse player needs, streamline the datapath for efficiency, reduce lag, and make I/O presentation broadly accessible. This approach highlights our commitment to a gaming experience that is technologically advanced, sustainable, and inclusive for a diverse community.
