# GitHub Upload Checklist

## Before upload

- [ ] Create repository: `leakage-controlled-dynamic-comparator-45nm`
- [ ] Use a professional repository description
- [ ] Decide whether the repository should be Public
- [ ] Do not upload GPDK045/foundry/BSIM/license files
- [ ] Do not upload Cadence installation files
- [ ] Do not upload PSF/raw simulation databases
- [ ] Verify README images render
- [ ] Verify the report PDF opens
- [ ] Verify CSV/JSON results
- [ ] Verify the repository has no sensitive/proprietary files

## First commit

```bash
git add .
git commit -m "Initial project documentation and reported results"
git branch -M main
git remote add origin https://github.com/<username>/leakage-controlled-dynamic-comparator-45nm.git
git push -u origin main
```

## Later commits

```text
Add Cadence schematic documentation
Add testbench and simulation setup
Add transient waveform results
Add power and leakage measurements
Add delay and PDP analysis
Improve project documentation
```
