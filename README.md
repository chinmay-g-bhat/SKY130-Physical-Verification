# SKY130 Physical Verification Labs

This repository documents my hands-on Physical Verification and Tapeout workshop using the open-source **SKY130 Process Design Kit (PDK)**. The project covers physical verification methodologies performed before IC fabrication, including Design Rule Checking (DRC), Layout Versus Schematic (LVS), parasitic extraction, hierarchy management, GDSII generation, density verification, antenna checks, and Electrical Rule Checking (ERC).

The complete workflow was performed using **Magic VLSI, Netgen, KLayout, Xschem, Ngspice, and OpenLane**, providing practical exposure to physical verification and tapeout sign-off concepts.

## Workshop Overview

The repository is organized according to the completed workshop modules and practical laboratory exercises.

## Tools & Technologies

- SKY130 Process Design Kit (PDK)
- Magic VLSI
- Netgen
- KLayout
- Xschem
- Ngspice
- OpenLane
- Linux Environment

## Day-wise Contents

### Day 1 – Introduction to SKY130 and Open Source Tools

- Introduction to SKY130 PDK
- Open Source EDA Tools
- SKY130 Technology Layers
- Device Libraries and PDK Structure
- Basic DRC/LVS Design Flow
- Schematic and Layout Creation using Xschem & Magic

### Day 2 – Layout, Extraction and Physical Verification

- Layout and extraction
- GDSII read/write operations
- Extraction commands
- DRC setup and verification
- LVS setup
- Layout verification exercises

### Day 3 – DRC Rules and Physical Verification Labs

- Silicon manufacturing concepts
- Backend metal layer rules
- Local interconnect rules
- Device and layout design rules
- DRC violation analysis and debugging
- Antenna rules
- Density rules
- Electrical Rule Checking (ERC)
- Practical DRC laboratory exercises

### Day 4 – OpenLane and Physical Verification Flow

- Physical design flow overview
- Synthesis
- Static Timing Analysis
- Floorplanning
- Placement
- Clock Tree Synthesis
- Routing
- RC extraction
- Physical verification
- GDSII generation
- Tapeout sign-off flow

### Day 5 – LVS and Verification Debugging

- LVS fundamentals
- Hierarchical LVS
- Netlist comparison
- Device and net matching
- LVS debugging
- Analog block LVS
- Layout versus Verilog verification
- Interpretation of Netgen verification results

## Verification Flow

Schematic → Layout → DRC → LVS → Parasitic Extraction → Antenna & Density Checks → ERC → GDSII → Tapeout Sign-off

## Learning Outcomes

- Understanding of the SKY130 Process Design Kit
- Practical exposure to open-source VLSI tools
- Physical layout creation and verification
- Design Rule Checking (DRC)
- Layout Versus Schematic (LVS) verification
- Parasitic extraction
- Antenna, density and ERC checks
- GDSII generation
- Physical verification debugging
- Understanding of tapeout-related sign-off flow
