# Data directory

This repository stores nutrition and food data under `data/`.

## Structure

- `raw/` contains original, unmodified source files.
- `processed/` contains cleaned, transformed, or merged datasets.

## Standards

- Keep original data unchanged in `raw/`.
- Use descriptive names for processed files.
- Document schema changes in docs or notebooks.
- Prefer CSV/Parquet files for structured data because they are easy to version and inspect.
