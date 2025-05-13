# Pulse Width Modulator

This repository contains a Pulse Width Modulator (PWM) circuit designed to control a DC motor using a 555 timer and an operational amplifier. The schematic is created in KiCad, and an LTspice simulation is included to verify the circuit's performance.

## Features

- Generates a PWM signal using an NE555D timer.
- Adjustable duty cycle via a potentiometer.
- Drives a DC motor through an N-channel MOSFET (2N7000).
- Includes an LM358 op-amp for signal conditioning.
- Powered by a 12V supply.

## Components

- **U1 (NE555D)**: Timer for PWM signal generation.
- **U2 (LM358_DFN)**: Dual op-amp for signal processing.
- **Q1 (2N7000)**: N-channel MOSFET for motor control.
- **M1**: DC motor.
- **RV1**: Potentiometer for duty cycle adjustment.
- **R1 (10 kΩ), R2 (68 kΩ)**: Resistors for timing and biasing.
- **C1 (0.01 μF), C2 (22 nF)**: Capacitors for timing and filtering.

## Files

- `Pulse_Width_Modulator.kicad_sch`: KiCad schematic file.
- `Pulse_Width_Modulator.asc`: LTspice simulation file.

## Requirements

- KiCad for viewing/editing the schematic.
- LTspice for running the simulation.
- 12V power supply for the circuit.
- Standard electronic components as listed.

## Usage

1. Open the schematic in KiCad to review or modify the circuit.
2. Run the LTspice simulation to analyze the PWM signal and motor control.
3. Assemble the circuit on a breadboard or PCB using the specified components.
4. Adjust the potentiometer (RV1) to control the PWM duty cycle and motor speed.
5. Connect a 12V power supply and a DC motor to test the circuit.

## Notes

- Ensure proper grounding and power connections to avoid circuit damage.
- The LTspice simulation can help verify the PWM frequency and duty cycle.
- Select a DC motor compatible with the 2N7000 MOSFET's current and voltage ratings.
