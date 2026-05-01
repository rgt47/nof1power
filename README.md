# nof1power <a href="https://github.com/rgt47/nof1power"><img src="man/figures/logo.png" align="right" height="138" alt="nof1power hex sticker" /></a>

Power Analysis and Simulation for N-of-1 Trials

## Overview

`nof1power` provides power analysis and simulation tools for N-of-1 clinical
trial designs. N-of-1 trials are randomized crossover trials conducted in
individual patients, useful for determining optimal treatments for individual
patients.

## Features

- Power calculation for N-of-1 crossover designs
- Sample size estimation
- Monte Carlo simulation for complex designs
- Visualization of power curves

## Installation

```r
devtools::install_github("rgt47/nof1power")
```

## Research Compendium

This package is structured as a reproducible research compendium using the
zzcollab framework. The analysis directory contains:

- `analysis/data/` - Raw and derived data
- `analysis/scripts/` - Analysis code
- `analysis/report/` - Manuscript and reports
- `analysis/figures/` - Generated visualizations

## Development

```bash
# Start Docker container
make r

# Run tests
make docker-test

# Build documentation
make docker-document
```

## License

GPL-3

## Author

Ronald (Ryy) G. Thomas (rgthomas@ucsd.edu)
