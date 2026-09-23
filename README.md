# PCSE Hardware

Research repository for the design, simulation, fault-injection
evaluation, recovery mechanisms, synthesis, and analysis of PCSE
hardware.

## Project Status

**Status:** Research / Development

## Overview

PCSE is being investigated as a hardware-level mechanism for detecting
and responding to processor faults.

The project uses the open-source Ibex RISC-V processor as an external
experimental platform. PCSE-specific RTL, simulation infrastructure,
fault models, recovery software, synthesis scripts, and analysis are
maintained in this repository.

## Repository Structure

```text
pcse-hardware/
├── rtl/                    PCSE RTL and testbenches
├── sim/                    Simulation and fault injection
├── recovery/               Software recovery mechanisms
├── synthesis/              Yosys synthesis infrastructure
├── analysis/               Data analysis and visualization
├── paper/                  Research paper sources and artifacts
├── docs/                   Technical documentation
├── WEEK_LOGS/              Development and research logs
└── external/ibex/          External Ibex dependency
```
## Experimental Platform

PCSE experiments use:

- RISC-V
- lowRISC Ibex
- SystemVerilog
- Verilator
- GTKWave
- Yosys
- RISC-V GCC toolchain
- Python

The exact Ibex revision used in experiments is documented in
`docs/IBEX_VERSION.md.`

## Reproducibility

Experimental results should record:

- Ibex revision
- RTL revision
- simulator version
- synthesis tool version
- compiler/toolchain version
- configuration parameters
- fault model
- random seeds where applicable
## AI-Assisted Development

AI tools may be used during development for code generation,
debugging, documentation, analysis assistance, and review.

All substantive AI assistance is documented in:

- `AI_USAGE.md`
- `ACKNOWLEDGMENTS.md`
- `docs/AI_PROMPTS.md`

AI-generated output is reviewed and validated by the project author
before inclusion in research artifacts.

## Research Integrity

AI assistance does not replace experimental validation, source
verification, or scientific judgment.

Experimental claims in the paper must be supported by reproducible
results.

## License

See the repository license for the applicable terms.
