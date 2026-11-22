# DSG-Final-Project
A Digital System Design final project that uses an FPGA to count laps, record lap times, and track the fastest lap.
Project Overview

The F1 Race Timing & Lap Monitoring System is an FPGA-based digital system designed to simulate a Formula 1 race timing mechanism.

The system tracks lap counts, measures individual lap times, identifies the fastest lap, and stores lap history using digital logic components implemented in VHDL.

This project aims to integrate the concepts learned throughout Digital System Design Laboratory Modules 2–9 into one functional system.

Main Features

* Lap Counter: Counts completed laps.
* Lap Timer: Measures the duration of each lap.
* Fastest Lap Detection: Identifies the fastest completed lap.
* Race Control: Manages START, RACING, and FINISH states using an FSM.
* Lap History: Stores lap times using RAM.
* Output Display: Displays race information.

Digital Components

* Logic Gates & Combinational Logic
* Flip-Flops & Registers
* Counters & Clock Divider
* Finite State Machine (FSM)
* Comparator
* Multiplexer
* RAM

Tools & Technologies

* Language: VHDL
* Software: AMD Vivado
* Hardware: Zybo Z7-10 FPGA Board
* Testing: VHDL Simulation & FPGA Implementation

Project Timeline

Week 1 – System Design & Development

* Finalize project concept and architecture.
* Develop individual VHDL modules.
* Perform initial simulations.

Week 2 – Integration & Testing

* Integrate all system components.
* Test and debug the complete system.
* Implement the design on FPGA.
* Prepare final documentation and presentation.

Team Members

Name	Responsibility
Alia	FSM & System Control
Calista	Lap Counter & Timer
Clyo	Comparator & RAM
Raisha	Display & System Integration

Expected Outcome

A functional FPGA-based race timing prototype capable of counting laps, measuring lap times, identifying the fastest lap, and storing race timing data.

The project will demonstrate how multiple digital system design concepts can be integrated into a practical application.
