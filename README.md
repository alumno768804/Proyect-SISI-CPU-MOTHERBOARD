# CPU (Processor) & Motherboard (Chipset)

> **Student:** Lucas Rodríguez Escribano  


## Table of Contents

- [Introduction](#introduction)
- [Main Functions](#main-functions)
- [Key Specifications](#key-specifications)
- [Real-World Examples](#real-world-examples)
- [References](#references)
- [Kahoot Quiz](#kahoot-quiz)

## Introduction

A computer has many components that work together. Two of the most important ones are the CPU and the motherboard.

The **CPU (Central Processing Unit)** is the processor. It executes instructions, performs calculations and helps programs work. For example, when I open a browser, run Java code or play a game, the CPU processes the instructions needed by the program.

The **motherboard** is the main circuit board of the computer. It connects the CPU, RAM, storage, graphics card and other devices so they can communicate. Without a compatible motherboard, the other components cannot work together correctly.

## Main Functions

### CPU: how it works

The CPU receives instructions from programs, processes data and sends results to other components. Its performance depends on different factors, such as the number of cores, clock speed, cache and the type of tasks being performed.

- **Cores:** processing units inside the CPU. More cores can help when a program performs several tasks at the same time.
- **Threads:** sequences of instructions that the CPU can manage. Some CPUs can work on more than one thread per core.
- **Clock speed:** measured in GHz. It indicates how many clock cycles the processor can perform per second, but it does not explain performance by itself.
- **Cache:** small, very fast memory inside the processor. It keeps data that the CPU may need soon.
- **Integrated graphics:** some processors include graphics hardware, so a separate graphics card is not always necessary.

### Motherboard: how it works

The motherboard provides the connections and pathways that allow components to exchange data and receive power. Its main parts include:

- **CPU socket:** the place where the processor is installed.
- **RAM slots:** connectors for the computer's main memory.
- **PCIe slots:** used for expansion cards, such as a dedicated graphics card.
- **M.2 and SATA connectors:** used to connect SSDs and hard drives.
- **VRM (Voltage Regulator Module):** helps deliver the correct voltage to the CPU.
- **BIOS/UEFI:** firmware that starts the computer and allows basic hardware settings to be configured.
- **Rear I/O:** ports for USB devices, network cables, audio and sometimes monitors.

### How the CPU and motherboard connect to other components

**CPU and motherboard:** the processor must fit the motherboard's socket, and the motherboard chipset and firmware must support it. For example, the AMD Ryzen 5 9600X uses socket AM5, while the Intel Core Ultra 5 245K uses socket LGA 1851. They cannot be installed in the same motherboard.

**Motherboard and RAM:** the motherboard determines the type of memory supported and how many memory modules can be installed. The examples in this report use DDR5 memory.

**Motherboard and storage:** M.2 slots can connect compatible NVMe SSDs, while SATA ports can connect SATA SSDs and hard drives.

**CPU and cooling:** the CPU produces heat when it works. A heatsink and fan, or a liquid-cooling system, remove this heat and help the processor maintain safe temperatures.

## Key Specifications

### CPU specifications

- **Cores and threads:** cores perform processing work; threads help organise tasks. More is not always better for every program.
- **Clock speed (GHz):** the base speed and maximum boost speed show different operating conditions.
- **Cache (L1, L2 and L3):** L1 is usually the smallest and fastest; L2 is larger; L3 is usually larger again and shared by CPU cores.
- **TDP / power:** TDP is a thermal-design figure used to plan cooling. It is not always the same as the maximum power consumed.
- **Socket and architecture:** the socket must match the motherboard. Modern desktop CPUs commonly use x86-64 architecture.
- **Integrated graphics:** useful for basic display output and some tasks, but not always as powerful as a separate graphics card.

### Cooling

Cooling is important because a CPU that gets too hot may reduce its speed to protect itself. A cooling system normally includes a heatsink and fan, or a pump, radiator and fans in a liquid cooler. **Thermal paste** is placed between the CPU and cooler to improve heat transfer by filling tiny gaps between their surfaces.

Air cooling is usually simpler and often cheaper. Liquid cooling can move heat to a radiator and may suit some high-power or compact builds, but it is usually more expensive and has more parts.

### Motherboard specifications

- **Form factor:** ATX is a full-size desktop board; Micro-ATX is smaller; Mini-ITX is compact and normally has fewer expansion slots.
- **Chipset:** controls or helps manage features and connections available on the platform. Different chipsets can offer different numbers of ports, expansion options and overclocking features.
- **RAM support:** check DDR generation, maximum capacity and supported speeds.
- **PCIe:** the expansion interface used by graphics cards and some storage devices. The generation and number of lanes affect available bandwidth.
- **Storage connections:** M.2 slots and SATA ports determine which drives can be connected.
- **Rear I/O and networking:** USB, audio, Ethernet, Wi-Fi and display connections vary by model.
- **BIOS/UEFI support:** a firmware update may sometimes be needed for a newer CPU.

## Real-World Examples


### 1. AMD Ryzen 5 9600X — CPU


- **Cores / threads:** 6 cores and 12 threads.
- **Clock speed:** 3.9 GHz base, up to 5.4 GHz boost.
- **Cache:** 480 KB L1, 6 MB L2 and 32 MB L3.
- **Default TDP:** 65 W.
- **Socket / architecture:** AM5 / Zen 5.
- **Integrated graphics:** yes, basic AMD Radeon graphics.
- **Approximate price:** about **€180–€205**.
- **Product page:** [AMD official website](https://www.amd.com/es/products/processors/desktops/ryzen/9000-series/amd-ryzen-5-9600x.html)

This is a desktop processor that could be suitable for programming, multitasking and gaming. It uses AM5, so it needs a compatible AM5 motherboard and DDR5 memory.

### 2. Intel Core Ultra 5 245K — CPU


- **Cores / threads:** 14 cores (6 performance cores and 8 efficient cores), 14 threads.
- **Maximum turbo speed:** up to 5.2 GHz.
- **Cache:** 24 MB Intel Smart Cache and 26 MB L2 cache.
- **Processor base power:** 125 W; maximum turbo power 159 W.
- **Socket / platform:** LGA 1851, Intel Core Ultra 200S Series.
- **Integrated graphics:** Intel Graphics.
- **Approximate price:** around **€250–€320**, depending on shop and availability.
- **Product page:** [Intel official specifications](https://www.intel.com/content/www/us/en/products/sku/241067/intel-core-ultra-5-processor-245k-24m-cache-up-to-5-20-ghz/specifications.html)

This CPU has a mix of performance cores and efficient cores. It needs a motherboard with the correct LGA 1851 socket, such as a compatible Intel 800-series board.

### 3. MSI MAG B650 TOMAHAWK WIFI — Motherboard

- **Form factor:** ATX.
- **Socket / chipset:** AMD AM5 / AMD B650.
- **CPU support:** AMD Ryzen 7000, 8000 and 9000 desktop series, subject to the required BIOS version.
- **Memory:** 4 DDR5 slots, up to 256 GB.
- **Storage:** 3 M.2 slots and 6 SATA ports.
- **Networking:** 2.5 Gb Ethernet, Wi-Fi 6E and Bluetooth.
- **Approximate price:** around **€190–€240**; check current shop offers.
- **Product page:** [MSI official specifications](https://es.msi.com/Motherboard/MAG-B650-TOMAHAWK-WIFI/Specification)

This board is a good example of an ATX motherboard with several storage options and wireless networking. It is compatible with the AMD Ryzen 5 9600X, but the BIOS version should be checked before installation.

### 4. MSI MAG Z890 TOMAHAWK WIFI — Motherboard



- **Form factor:** ATX.
- **Socket / chipset:** Intel LGA 1851 / Intel Z890.
- **CPU support:** Intel Core Ultra processors Series 2.
- **Memory:** 4 DDR5 slots, up to 256 GB.
- **Storage:** 4 M.2 slots and 4 SATA ports.
- **Networking:** 5 Gb Ethernet, Wi-Fi 7 and Bluetooth.
- **Other connections:** PCIe 5.0 and Thunderbolt 4.
- **Approximate price:** about **€317** on the MSI Spain store when checked, although it was listed as out of stock.
- **Product page:** [MSI official store](https://es-store.msi.com/products/mag-z890-tomahawk-wifi-placas-base)

This motherboard is designed for Intel Core Ultra Series 2 processors. It is not compatible with the AMD Ryzen 5 9600X because the socket and platform are different.

### Air cooling example: Thermalright Peerless Assassin 120 SE


An air cooler uses a metal heatsink and fans to move heat away from the CPU. Before buying a cooler, it is important to check socket support, case clearance and the CPU's cooling requirements.

## References

- AMD — Ryzen 5 9600X specifications: https://www.amd.com/es/products/processors/desktops/ryzen/9000-series/amd-ryzen-5-9600x.html (accessed 29 October 2026).
- Intel — Core Ultra 5 245K specifications: https://www.intel.com/content/www/us/en/products/sku/241067/intel-core-ultra-5-processor-245k-24m-cache-up-to-5-20-ghz/specifications.html (accessed 29 October 2026).
- MSI — MAG B650 TOMAHAWK WIFI specifications: https://es.msi.com/Motherboard/MAG-B650-TOMAHAWK-WIFI/Specification (accessed 29 October 2026).
- MSI — MAG Z890 TOMAHAWK WIFI: https://es-store.msi.com/products/mag-z890-tomahawk-wifi-placas-base (accessed 29 October 2026).
- AMD — CPU product and support information: https://www.amd.com/ (accessed 29 October 2026).
- Intel — Processor information: https://www.intel.com/ (accessed 29 October 2026).

## Kahoot Quiz

https://create.kahoot.it/share/cpu-and-motherboard/7f799228-4d2d-4687-a962-ed0e98f78938