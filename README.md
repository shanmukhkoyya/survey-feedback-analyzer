# Survey Feedback Analyzer

**Tools:** Python · Jupyter Notebook

This beginner-level Python project takes a small set of survey comments and ratings, cleans the text, and calculates simple summaries. It demonstrates core Python data handling, not advanced sentiment analysis.

## Questions explored
- What is the average rating?
- How many feedback entries contain selected words such as good, poor, or excellent?
- Which comment is longest by word count?
- Which unique words appear in the cleaned text?
- How can additional feedback rows be entered and added to the data structure?

## Workflow
1. Start with the 10 feedback records supplied in the assignment.
2. Optionally enter additional names, comments, and ratings.
3. Clean comment text by removing selected punctuation, converting to lowercase, trimming whitespace, and collapsing repeated spaces.
4. Calculate ratings and word-based summaries.
5. Optionally sort records by rating.

## Files
| File | Purpose |
|---|---|
| [Notebook](Survey_Feedback_Analyzer.ipynb) | Notebook with interactive input and analysis |
| [.gitignore](.gitignore) | Ignores common local files |

## How to run
1. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
2. Run the cells in order.
3. When asked how many extra feedback records to add, enter 0 to use only the original 10.
4. Otherwise, enter the requested name, comment, and rating from 1 to 5.
5. Review the cleaned text and summary outputs.

## Python concepts practised
Lists and dictionaries, input handling, loops, conditions, string methods, functions, averages, word counts, sets, zip, and sorting.

## Interpretation notes
- Results vary when additional feedback is entered.
- Keyword counts indicate feedback entries containing a whole word; this is not a comprehensive sentiment model.
- The longest comment is determined by word count.
- Rating-based sorting orders records by the provided rating; it does not judge the meaning of the comment.

## Author
**Shanmukh Koyya** · [GitHub](https://github.com/shanmukhkoyya) · [LinkedIn](https://www.linkedin.com/in/shanmukh-koyya/) · [Email](mailto:shanmukhkoyya1234@gmail.com)
