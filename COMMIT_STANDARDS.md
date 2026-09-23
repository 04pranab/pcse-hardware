# Commit Standards

Commits should be small, descriptive, and focused on one logical
change.

## Format

Use:

```text
<type>: <short description>
```
## Types
- `feat` New functionality
- `fix` Bug fix
- `rtl` RTL changes
- `sim` Simulation changes
- `test` Testbench or test changes
- `analysis` Analysis changes
- `synth` Synthesis changes
- `docs` Documentation
- `paper` Paper/manuscript changes
- `refactor` Code restructuring
- `chore` Maintenance
## Examples

```bash 
rtl: add PCSE detection logic
sim: add transient fault injection model
test: add detector fault coverage tests
analysis: compute AVF from simulation results
synth: add Yosys synthesis configuration
docs: document Ibex experimental configuration
paper: update fault model methodology
fix: correct detector reset behavior
```

## Guidelines
- One logical change per commit.
- Avoid vague messages such as update, changes, or final.
- Do not commit generated simulation outputs.
- Do not commit secrets or credentials.
- Do not mix unrelated changes.
- Experimental results should identify the configuration that produced
them.

---
