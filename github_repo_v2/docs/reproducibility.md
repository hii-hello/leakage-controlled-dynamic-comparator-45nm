# Reproducibility Guide

## Required environment

1. Licensed Cadence Virtuoso.
2. Authorized 45nm CMOS technology library.
3. Required transistor models/PDK configuration.
4. Comparator schematic and testbench.
5. Spectre transient analysis.
6. Virtuoso Calculator/ADE measurement setup.

## Repository limitation

This repository intentionally does not distribute GPDK045, foundry model files, Cadence binaries, license files, or generated simulation databases.

## Suggested workflow

```text
45nm Technology Library
        ↓
Conventional Comparator
        ↓
LECTOR-Controlled Comparator
        ↓
Testbench
        ↓
Transient Simulation
        ↓
Power / Leakage Measurement
        ↓
Rising / Falling Delay
        ↓
PDP + Energy/Cycle
        ↓
Conventional vs Proposed
```

## Measurement convention

The report uses 50% of the 1.8 V supply (0.9 V) as the delay threshold and measures delay between the clock trigger and the corresponding output transition.

The repository contains report-derived results and selected visual evidence, but not the complete proprietary PDK environment required for independent reproduction.
