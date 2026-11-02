# musical-giggle

This repository is now set up to generate a very large synthetic dataset for repository-language analysis.

## What is included

- `generate_titanic_dataset.py` — creates a large synthetic dataset with repository metadata, file paths, file sizes, language composition, and commit hashes.
- `.gitignore` — ignores generated output folders.

## Quick start

```bash
python3 generate_titanic_dataset.py --rows 1000000 --output-dir data
```

This will generate a CSV and/or Parquet output based on the selected configuration.

## Notes

The dataset is intentionally synthetic and designed for stress testing, data engineering, analytics demos, and benchmarking large repository metadata pipelines.
