# Ibex Version

PCSE uses the open-source lowRISC Ibex RISC-V processor as an
external experimental platform.

## Upstream

Repository:

https://github.com/lowRISC/ibex

## Pinned revision

The exact Ibex commit used for PCSE experiments must be recorded here.

- Commit: `REPLACE_WITH_GIT_REV_PARSE_HEAD`
- Version/tag: `REPLACE_WITH_GIT_DESCRIBE`

## Policy

The Ibex source tree is treated as an external dependency and is not
part of the PCSE source contribution.

PCSE-specific RTL and modifications belong under `rtl/`.

Experiments must record the exact Ibex revision used so that simulation
and synthesis results can be reproduced.
