# Christoph Brauer
### Systems, Graphics & Hardware Engineer | "Sergeant Major" of Code
Polyglot systems engineer with multi-decade execution experience spanning bare-metal assembly, compiler construction, custom 3D shader engines, and advanced hardware reverse engineering. I strip away bloated abstraction layers to solve critical performance, memory, and hardware bottlenecks. 

**Operational Style:** Give me the technical constraints, clear the bureaucratic runway, and get out of the way. I dive deep, debug the impossible, and deliver highly optimized, production-ready code.
## 🛠️ Flagship Engineering Gear
### 🕹️ Active Tangible Input Device (TID) — Full Hardware/Software Co-Design*Complete academic and practical research project developing an active, wireless prototyping framework for advanced Human-Computer Interaction (HCI) on standard capacitive touchscreens.*
**Full Thesis Documentation:** [Read the Complete PDF](https://krustyland.net)


* **Core Processing & Architecture:** Built a star-topology hardware network centered on an **Espressif ESP32 dual-core MCU** running at 240 MHz, utilizing low-power Bluetooth LE for host communication and high-speed SPI/I2C for peripherals. Engineered a multitasking, object-oriented firmware architecture (over 10,000 lines of standard C++) built on the **FreeRTOS kernel** and ESP-IDF, ensuring highly deterministic, non-blocking sensor execution.
* **Hardware Hacking & Component Integration:** Reused a disassembled **Valve Steam Controller trackpad assembly**, mapping its proprietary 12-pin flex cable pinout to interface natively over a 10 MHz SPI bus with a Pinnacle 1CA027 controller chip.
* **Open-Loop Audio Haptics:** Implemented real-time tactile waveforms by routing digital I2S DMA streams straight from the ESP32 into a **Maxim MAX98357A 3W amplifier** to drive an integrated **ALPS Haptic Reactor** (LRA), achieving highly configurable, audio-style haptic effects.
* **Sensor Fusion & Telemetry:** Integrated an **MPU-6050 6-DoF IMU** using its on-chip Digital Motion Processor (DMP) to handle sensor-fusion math autonomously, pairing it with **dual VL6180X and VL53L0X Time-of-Flight (TOF) laser distance sensors** to track sub-millimeter lift-off vectors and 3D gesture manipulation.
* **Custom Human Interface Mechanics:** Developed a concentrically aligned **clickable touchwheel** splitting a physical button ring into 4 tactile quadrants, expanded via an **MPR-121 capacitive touch sensor** into a high-granularity 12-segment scrolling wheel. Offloaded visual animations (exceeding 100 Hz refresh rates) to a 24-module **WS2812B NeoPixel ring** driven completely via the ESP32’s hardware **RMT (Remote Control) port and DMA**, bypassing CPU-intensive bit-banging.
* **Multi-Material Industrial Prototyping:** Modeled a parametric, modular 3D-printable cylindrical enclosure utilizing secure snap-in joints to hold tightly packed hardware and an integrated 4-cell LiPo battery array. Solved passive touchscreen recognition by co-printing an asymmetric, non-perpendicular outer ring combining **rigid PLA** for structural integrity with a **flexible conductive TPU core** acting as grounded capacity markers to continuously trace positioning and rotation without triggering screen sleep-filters.

---

### 💻 Procedural Graphics & Shader Math

*   **[Pure-Fragment Raymarching Shaders](https://krustyland.net)**
    *   *The Strategy:* Zero polygons, zero vertex arrays, zero pre-loaded 3D meshes. The entire 3D camera geometry and scene composition are generated procedurally using pure signed distance fields (SDFs) and mathematical equations calculated natively inside a WebGL sandbox.
*   **[WebGL Blinn-Phong Real-Time Shading Engine](https://krustyland.net)**
    *   *The Strategy:* Handcrafted interactive rendering engine calculating vector dot products, view targets, light directions, and specular reflection models per-fragment. Swappable real-time toggle between classic Phong and optimized Blinn-Phong halfway-vector configurations.

---

### ⚡ Systems, Compilers, & Hardware Modification

*   **Language-Agnostic Engine Mastery:** Deeply experienced across the entire paradigm stack—from direct hardware assembly (x86, 68000, Z80), system languages (C/C++), and shader languages (GLSL), up to high-level system software.
*   **Compiler Engineering:** Built clean lexical analysis pipelines, custom parsers, Abstract Syntax Trees (AST), and direct machine-code generation tools to establish highly deterministic compilation without bloated third-party library dependencies.
*   **Hardware Modification & Testing:** Veteran setup in low-level hardware diagnostics, tracking signal data/address lines live across motherboards, and reverse-engineering proprietary hardware security layers (such as retro console modification pipelines).

---

## 🚀 Technical Armory

*   **Languages:** C, C++, Assembly (x86, Motorola 68000, Zilog Z80), GLSL, WebGL, JavaScript
*   **Architectures & MCUs:** ESP32, ARM, AVR, FreeRTOS Core, Retro Arcade & Console Systems (Neo-Geo MVS, Mega Drive, PlayStation)
*   **Hardware Interfaces:** SPI, I2C, I2S DMA, RMT, Logic Analyzers, Oscilloscopes, Parameterized CAD Modeling (Fusion 360)
*   **Frameworks & Build Tools:** ESP-IDF, PlatformIO, Native GCC Toolchains

---

## 📬 Contact Me

*   **Location:** Hamburg, Germany
*   **Work Availability:** Open to high-impact **Full-Time Core Engineer** positions or **Half-Time Remote** architectural/performance consulting contracts.

