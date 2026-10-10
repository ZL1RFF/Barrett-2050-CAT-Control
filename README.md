![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)


# Barrett 2050 CAT Control by ZL1RFF - Documentation in Progress...

**Barrett 2050 HF Transceiver CAT Control**
A feature-rich, modern PyQt6 graphical user interface (GUI) designed for remote CAT control and monitoring of the Barrett 2050 High Frequency (HF) Transceiver via RS-232 serial communication. Engineered with a tactical, dark-themed hardware aesthetic inspired by professional radio equipment.

🚀 ***Key Features***

**Intelligent COM Port Management:** Automatically detects available system serial ports with a priority default to COM3, featuring a live dropdown selector and manual port refresh utility.  

**Tactical OLED-Style Display:** Features a high-contrast dark instrument panel showing live local time (NZDT) and UTC clocks, operating power status, active mode, and exact frequency readout.   

**Custom Analog S-Meter & SWR Widget:** Built-in QPainter custom widget replicating professional dual-scale S-meters with standard S-units, dB increments (+20, +40, +60dB), an SWR scale, and real-time peak-hold decay.

**Precision VFO Tuning Dial:** Interactive rotary tuning knob styled after flagship receivers (like the Icom IC-R8600) supporting smooth mouse drag rotation, mouse wheel frequency steps, and circular hardware-style UP/DOWN arrow buttons.  

**Flexible Step Sizes & Band Selection:** Quick-select tuning step buttons (10 Hz, 100 Hz, 1 kHz, 10 kHz) alongside a 9-band preset matrix covering amateur HF allocations from 80m through 10m.   In-Band Lock Protection: Optional toggle lock that restricts tuning and direct frequency entry strictly within legal amateur band boundaries.   

**Direct Frequency Entry:** Numerical quick-entry field supporting direct MHz or kHz keyboard entry with input validation.

**Front-Panel Mode & Power Controls:** Dedicated control grids for switching operating modes (USB, LSB, AM, CW, AFSK) and transmitter power levels (Low, Med, High).  

**DSP & Noise Filtering Control:** Integrated controls for multi-level Noise Reduction (Off, Low, Med, High) and Noise Blanker toggles.   

**AF Gain Control:** Smooth audio volume slider mapped to Barrett serial volume commands (0–15).   RS-232 Rocker Switch Interlock: Custom physical-style rocker switch widget for enabling or disabling remote serial control on the fly.   Asynchronous Polling Engine: Background round-robin loop that continuously syncs radio state parameters including signal strength, frequency status (IF), noise reduction (EM), and noise blanker (EN) states.   
