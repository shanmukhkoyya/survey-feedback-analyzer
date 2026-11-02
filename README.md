# Survey Feedback Analyzer

*Notebook walk-through · Python fundamentals · Text cleaning · Descriptive summaries*

---

### The small problem

Customer comments are free text, while ratings are numeric. This beginner notebook brings those two types of feedback into one simple workflow: collect records, clean comments, calculate rating summaries, and inspect selected word patterns.

This is a learning exercise—not a production survey platform or a sentiment-analysis model.

## Notebook contents

| Notebook operation | What it demonstrates |
|---|---|
| Collect records | Lists, dictionaries and user input |
| Clean comments | Lowercasing, punctuation removal and whitespace handling |
| Summarise ratings | Average calculation and sorting |
| Inspect words | Selected keyword counts and unique words |
| Compare comment length | Word counts and longest-comment identification |

## Input data

The notebook begins with **10 sample feedback records**. Each record contains a customer name, a comment and a rating from 1 to 5. During execution, the user may add more records.

## Open the notebook

**[Survey_Feedback_Analyzer.ipynb](Survey_Feedback_Analyzer.ipynb)**

The notebook is the primary deliverable. It contains the Python examples and analysis steps.

## Run it

Install Jupyter, start the notebook interface, open Survey_Feedback_Analyzer.ipynb and run the cells in order. At the prompt for additional feedback records, enter 0 to work with only the original 10 examples. Otherwise, enter the requested name, comment and rating.

## Concepts practised

Lists · dictionaries · loops · conditions · string methods · functions · sets · zip() · sorting · average calculation

## How to interpret the output

- The average rating changes when additional records are entered.
- Keyword counts identify selected words; they do not understand full sentence meaning.
- A comment can contain a positive and a negative idea even when a selected keyword appears.
- The longest comment is selected by word count, not by usefulness or sentiment.

## Limits of this exercise

The sample is small. Keyword matching is not comprehensive sentiment analysis, and the notebook does not use machine learning or natural-language-processing models. The results are useful for practising Python operations, not for making business decisions about customer satisfaction.

---

**Author:** Shanmukh Koyya · [GitHub](https://github.com/shanmukhkoyya) · [LinkedIn](https://www.linkedin.com/in/shanmukh-koyya/) · [Email](mailto:shanmukhkoyya1234@gmail.com)
