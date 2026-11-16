# Data Directory

This directory holds the data files for the project, organized by
processing stage.

## Directory Structure

```
data/
├── raw_data/           # Original, untouched data files
├── derived_data/       # Cleaned and processed data files
└── README.md           # This file - data documentation
```

## Current status

Both `raw_data/` and `derived_data/` are currently empty. No data
have been added to this compendium yet, and no data preparation
scripts exist in `analysis/scripts/`.

When data are added, document here, for each file: its source and
collection dates, its format and size, the script that produces each
derived file, a data dictionary, and any known quality issues.
Files in `raw_data/` should be treated as read-only.
