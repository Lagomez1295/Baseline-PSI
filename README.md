# PSI Baseline Estimation and Time-in-Range Analysis

This repository contains the Python-based signal processing pipeline used for baseline estimation and maintenance phase analysis of Patient State Index (PSI) signals during total intravenous anesthesia (TIVA).
The analysis pipeline was developed as part of the research project:
> “Re-evaluating Performance Metrics for Closed-Loop Total Intravenous Anesthesia Systems: Insights from a Post-Market Evaluation”

## Features

- PSI signal smoothing
- Maintenance phase detection
- Emergence detection
- Baseline estimation
- Time-in-range analysis
- Visualization of PSI trends

## Repository Structure

```text
Baseline-PSI/
│
├── PSI_Baseline_Analysis.ipynb
├── requirements.txt
├── README.md
└── example_data/
```

## Requirements

Python 3.10+

Main libraries:

- numpy
- pandas
- scipy
- matplotlib

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

Open the notebook:

```bash
jupyter notebook PSI_Baseline_Analysis.ipynb
```

or run directly in:

- Google Colab
- Jupyter Notebook
- VS Code

## Reproducibility

The notebook was designed to allow reproducible signal processing and analysis workflows for PSI-based anesthesia monitoring research.

All example data included in this repository are anonymized or synthetic.

## Intellectual Property Notice

This repository contains only the analysis and visualization components used in the study.

Proprietary closed-loop control algorithms, adaptive dosing architectures, and commercialization-related software components associated with SmartTIVA are not included.

## Citation

If you use this repository in academic work, please cite:

```text
Gomez L, et al.
PSI Baseline Estimation and Time-in-Range Analysis.
GitHub repository.
```

## License

This project is licensed under the MIT License.
