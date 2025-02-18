
---

# **Codecademy Learner Performance Dataset**

## **Overview**
This dataset was collected as part of an experiment to understand the factors that contribute to learner performance on a quiz. It contains information about student scores, the number of lessons completed prior to the quiz, and the specific lesson taken immediately before the quiz.

The dataset is preloaded in `script.py` as a Pandas DataFrame named **`codecademy`**.

## **Dataset Structure**
The dataset consists of three columns:

| Column Name  | Description |
|-------------|------------|
| `score` | Student's score on a quiz (numerical) |
| `completed` | Number of other content items completed before taking the quiz (numerical) |
| `lesson` | The lesson taken directly before the quiz (`'Lesson A'` or `'Lesson B'`) (categorical) |

## **Objective**
The dataset can be used to analyze:
- The relationship between **lesson completion** and **quiz scores**.
- Performance differences between students who took **Lesson A** vs. **Lesson B**.
- Potential insights into **learning effectiveness** based on past engagement.

## **Usage**
- Load and inspect the dataset using Pandas:
  ```python
  import pandas as pd

  # Dataset is already loaded as `codecademy`
  print(codecademy.head())  # View the first few rows
  print(codecademy.info())  # Get dataset summary
  ```
- Perform exploratory data analysis (EDA) and visualize insights using **matplotlib** and **seaborn**.
- Run statistical tests to determine significant differences between lessons.

## **Potential Analysis Ideas**
- **Descriptive Statistics:** Calculate the mean, median, and standard deviation of quiz scores.
- **Correlation Analysis:** Check the relationship between `completed` lessons and `score`.
- **Lesson Comparison:** Compare scores between `Lesson A` and `Lesson B` using box plots or t-tests.
- **Predictive Modeling:** Train a regression model to predict scores based on `completed` lessons.

## **License**
This dataset is for educational and research purposes only.

---

Let me know if you'd like any modifications! 🚀
