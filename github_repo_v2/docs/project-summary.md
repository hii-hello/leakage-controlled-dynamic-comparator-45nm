# Project Summary

## Objective

Design and analyze a low-power, high-speed leakage-controlled double-tail dynamic comparator for ADC applications using 45nm CMOS technology.

## Proposed technique

The proposed comparator integrates the LECTOR leakage-control technique into a double-tail dynamic comparator to suppress leakage paths using transistor stacking and self-controlled biasing.

## Tools

- Cadence Virtuoso
- Cadence Spectre
- 45nm CMOS / GPDK045
- BSIM4 transistor modeling

## Reported operating point

- VDD: 1.8 V
- Frequency: 250 MHz
- Clock period: 4 ns
- Duty cycle: 50%
- Clock rise/fall: 100 ps

## Reported results

- Total power: 6.492 µW
- Leakage power: 0.75 µW
- Falling delay: 46.59 ps
- Rising delay: 16.54 ps
- Average delay: 31.57 ps
- PDP: 205 fJ
- Energy/cycle: 25.96 fJ
- Total-power reduction: 92.46%
- Leakage-power reduction: 98.17%
- PDP improvement: 91.14%

## Scope note

These values are taken from the submitted project report. This repository does not independently re-run Cadence simulations or validate the results against silicon measurements.
