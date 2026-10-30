# Survey Feedback Analyzer

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:14243B,100:00C9D8&height=180&section=header&text=SURVEY%20FEEDBACK%20ANALYZER&fontSize=30&fontColor=ffffff&fontAlignY=40&desc=PYTHON%20%7C%20TEXT%20PROCESSING%20%7C%20DATA%20ANALYSIS&descAlignY=65" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Data_Analysis-00A6A6?style=for-the-badge" />
</p>

## 1. Project Overview

Survey Feedback Analyzer is a beginner-level Python project that processes customer feedback comments and ratings.

The project demonstrates how Python can be used to collect feedback, clean text, calculate rating summaries and explore basic word-based patterns.

It uses a small sample of survey records and allows users to enter additional feedback for analysis.

## 2. Business Problem

Businesses collect customer feedback to understand customer experiences and identify areas that may need improvement.

However, feedback comments are often unstructured text. This project demonstrates a simple Python workflow for preparing comments and summarising ratings and selected keywords.

## 3. Project Objectives

- Store survey records using Python data structures.
- Accept additional feedback through user input.
- Clean text by standardising case and removing selected punctuation.
- Calculate the average customer rating.
- Count feedback entries containing selected keywords.
- Identify the longest comment by word count.
- Find unique words in the cleaned feedback.
- Sort feedback records by rating.

## 4. Project Dataset

The notebook starts with 10 sample feedback records.

Each record includes:

- Customer name.
- Feedback comment.
- Rating from 1 to 5.

Users can optionally add more feedback records when executing the notebook.

## 5. Project Workflow

### Step 1 — Feedback Collection

- Use the initial sample feedback records.
- Allow additional records through user input.
- Store feedback using Python lists and dictionaries.

### Step 2 — Text Cleaning

- Convert comments to lowercase.
- Remove selected punctuation.
- Remove leading and trailing spaces.
- Collapse repeated spaces.

### Step 3 — Rating Analysis

- Calculate the average rating.
- Compare ratings across feedback records.
- Sort records based on rating.

### Step 4 — Text Analysis

- Count entries containing selected keywords.
- Calculate comment word counts.
- Identify the longest comment.
- Extract unique words from cleaned feedback.

### Step 5 — Results Review

- Display cleaned comments.
- Review rating summaries.
- Examine keyword counts and text summaries.

## 6. Analysis Outputs

| Analysis | Purpose |
|---|---|
| Average Rating | Calculate the average of submitted ratings |
| Keyword Counts | Count feedback entries containing selected words |
| Longest Comment | Identify the comment with the highest word count |
| Unique Words | Explore distinct words in cleaned feedback |
| Rating Sort | Arrange feedback records by rating |

## 7. Python Concepts Demonstrated

| Concept | Application |
|---|---|
| Lists | Store feedback records |
| Dictionaries | Organise customer information |
| Input Handling | Accept additional feedback |
| Loops | Process multiple records |
| Conditions | Apply keyword and rating checks |
| String Methods | Clean and standardise text |
| Functions | Organise reusable logic |
| Sets | Identify unique words |
| zip() | Combine related collections |
| Sorting | Order feedback by rating |
| Average Calculation | Summarise ratings |

## 8. Project File

| File | Description |
|---|---|
| [Survey Feedback Analyzer Notebook](Survey_Feedback_Analyzer.ipynb) | Python code, input handling and analysis |
| [.gitignore](.gitignore) | Excludes common local files |

## 9. How to Run the Project

**Prerequisite:** Python and Jupyter Notebook, JupyterLab or Google Colab.

1. Clone or download this repository.
2. Open `Survey_Feedback_Analyzer.ipynb`.
3. Run the notebook cells in order.
4. When asked how many additional feedback records to add, enter `0` to use only the original 10 records.
5. Otherwise, provide the requested name, comment and rating from 1 to 5.
6. Review the cleaned feedback and analysis outputs.

## 10. Scope and Limitations

- The project uses a small sample of survey records.
- Keyword counts only identify selected whole words.
- Keyword matching is not a comprehensive sentiment-analysis method.
- The longest comment is identified using word count.
- Average ratings depend on the records entered during execution.
- The project does not use machine learning or natural-language-processing sentiment models.

## 11. Project Structure

```text
survey-feedback-analyzer/
│
├── Survey_Feedback_Analyzer.ipynb
├── README.md
└── .gitignore
```

## 12. Author

**Shanmukh Koyya**

- **GitHub:** [shanmukhkoyya](https://github.com/shanmukhkoyya)
- **LinkedIn:** [linkedin.com/in/shanmukh-koyya](https://www.linkedin.com/in/shanmukh-koyya/)
- **Email:** [shanmukhkoyya1234@gmail.com](mailto:shanmukhkoyya1234@gmail.com)