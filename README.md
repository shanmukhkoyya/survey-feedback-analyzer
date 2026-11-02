<div align="center"><h1>💬 THE FEEDBACK LAB</h1><p>TEXT CLEANING · RATING SUMMARIES · PANDAS</p><img src="https://img.shields.io/badge/PYTHON-3776AB?logo=python&style=for-the-badge"/> <img src="https://img.shields.io/badge/PANDAS-150458?logo=pandas&style=for-the-badge"/> <img src="https://img.shields.io/badge/JUPYTER-F37626?logo=jupyter&style=for-the-badge"/></div>

## Lab bench
```mermaid
flowchart TD
 A[Load responses] --> B[Inspect columns]
 B --> C[Clean text]
 C --> D[Summarise ratings]
 D --> E[Explore response patterns]
```

## Notebook station
<p align="center"><a href="Survey_Feedback_Analyzer.ipynb"><img src="https://img.shields.io/badge/LAUNCH%20NOTEBOOK-OPEN%20JUPYTER-F37626?style=for-the-badge&logo=jupyter"/></a></p>

| EXPERIMENT | INSPECT |
|---|---|
| Load | Shape, columns and data types |
| Clean | Missing values and text normalization |
| Rate | Summary statistics and distributions |
| Explore | Frequent words and response patterns |

## Reproduce the lab
```bash
pip install pandas jupyter
jupyter notebook
```
Open the notebook and run cells from top to bottom.

**Scope note:** Word frequency is not sentiment analysis. Findings should not be generalized beyond the supplied sample.