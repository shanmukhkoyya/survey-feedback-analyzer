# 💬 SURVEY FEEDBACK ANALYZER
### A guided notebook walkthrough

<p align="center"><img src="https://img.shields.io/badge/PYTHON-3776AB?logo=python&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/PANDAS-150458?logo=pandas&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/JUPYTER-F37626?logo=jupyter&logoColor=white&style=for-the-badge"/></p>

## The notebook route
```mermaid
flowchart LR
 A[Load responses] --> B[Inspect columns]
 B --> C[Clean text]
 C --> D[Summarise ratings]
 D --> E[Explore feedback]
```

## Notebook launch
<p align="center"><a href="Survey_Feedback_Analyzer.ipynb"><img src="https://img.shields.io/badge/OPEN%20THE%20NOTEBOOK-Launch%20Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/></a></p>

## Lab worksheet
| Notebook section | What to inspect |
|---|---|
| Loading | Source structure and fields |
| Cleaning | Missing values and text normalization |
| Ratings | Summary statistics and distributions |
| Feedback | Common words and response patterns |

## Reproduce this exercise
```bash
pip install pandas jupyter
jupyter notebook
```
Open the notebook and run cells from top to bottom.

**Scope:** Text frequency is not sentiment analysis. Survey patterns should not be generalized beyond the supplied sample.