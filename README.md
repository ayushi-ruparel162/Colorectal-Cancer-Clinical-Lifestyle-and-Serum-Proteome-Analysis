# Thesis proteomics analysis

Public-facing repository for the analysis documented in `analysis/Thesis_final_public.ipynb`.

## Data privacy

The repository deliberately does **not** contain:

- raw or processed patient-level proteomic measurements
- clinical metadata
- private metadata dictionaries
- merged patient/proteomics tables
- private intermediate CSV/XLSX/TSV files

The public notebook has been modified so that direct loading/exporting of restricted
datasets is disabled.

## Repository structure

```text
analysis/                  Public notebook
results/figures/           Approved, non-identifying figures
scripts/                   Public-repository safety checks
private_data/              Local-only data; ignored by Git
```

## Running the analysis

The original analysis requires restricted proteomic and clinical inputs. Those inputs
are not distributed with this repository.

