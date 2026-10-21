# Survey Feedback Analyzer

A beginner-friendly Python project that cleans survey comments and extracts useful customer-feedback insights. Built in Jupyter Notebook using core Python concepts.

## Objectives

- Start with the 10 feedback records supplied in the assignment.
- Collect additional customer names, comments, and ratings (1–5).
- Assign serial numbers automatically and append records to a dictionary of lists.
- Clean text by removing `. , ! ?`, converting to lowercase, trimming whitespace, and replacing repeated whitespace with single spaces.
- Count feedback entries containing `good`, `poor`, and `excellent`.
- Calculate the average rating, find the longest comment by word count, and list unique words.
- Optionally sort comments from highest to lowest rating.

## Project files

```text
Survey-Feedback-Analyzer/
├── Survey_Feedback_Analyzer.ipynb
├── README.md
└── .gitignore
```

## How to run

1. Open `Survey_Feedback_Analyzer.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab.
2. Run each cell from top to bottom.
3. When prompted, enter how many additional feedback records you want to add. Enter `0` to keep only the 10 preloaded records.
4. For every additional record, enter the customer's name, written feedback, and rating from 1 to 5.
5. Review text-cleaning results, word-count insights, the final summary, and optional sorted results.

## Python skills demonstrated

- Dictionaries and lists
- `input()` and input validation
- `for` loops and `if` statements
- String operations: `lower()`, `replace()`, `split()`, and `join()`
- User-defined functions
- Average calculations and word counts
- `set()`, `zip()`, and `sorted()`

## Important notes

- The notebook uses the exact initial feedback dataset given in the assignment.
- Results can vary depending on the additional feedback entered when running the notebook.
- Word-count insights count feedback entries containing a whole word, not the total number of occurrences across every comment.
- The optional rating-based sorting uses the rating as the sort key.

## Author

**Shanmukh Koyya** — AI Data Analyst portfolio and interview practice  
GitHub: [shanmukhkoyya](https://github.com/shanmukhkoyya)  
LinkedIn: [shanmukh-koyya](https://www.linkedin.com/in/shanmukh-koyya/)
