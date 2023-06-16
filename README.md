# CSV File Analysis and Categorization

This repository contains a solution for analyzing and categorizing data from two CSV files. The goal is to merge the CSV files into a single dataframe and then split the data into different categories based on the "codekata" score. The categories include "Exceeded Expectations," "Reached Expectations," "Needs Improvement," and "Unsatisfactory."

## Problem Description

1. **Merge CSV Files**: Start by importing the necessary libraries and merging the two CSV files into a single dataframe. This step ensures that all the data is consolidated for further analysis and categorization.

2. **Categorize Based on Codekata Score**: Next, divide the data into different categories based on the "codekata" score for the present week. The following categories should be created:

   - **Exceeded Expectations.csv**: Include observations where the "codekata" score exceeds 15,000 points for the present week.
   - **Reached Expectations.csv**: Include observations where the "codekata" score is between 10,000 and 15,000 points for the present week.
   - **Needs Improvement.csv**: Include observations where the "codekata" score is between 7,000 and 10,000 points for the present week.
   - **Unsatisfactory.csv**: Include observations where the "codekata" score is less than 7,000 points for the present week.

Ensure that each CSV file created contains the relevant observations according to the specified criteria.

## Getting Started

To work on this task, follow these steps:

1. Import the necessary libraries to manipulate and analyze CSV data.
2. Merge the two CSV files into a single dataframe.
3. Split the dataframe into multiple categories based on the "codekata" score for the present week.
4. Create separate CSV files for each category, storing the corresponding observations.

## Repository Structure

This repository contains the following files:

- **Task Question.ipynb**: Jupyter Notebook file containing the task.
- **Solution.ipynb**: Jupyter Notebook file containing the code for merging and categorizing the CSV data.
- **exceeded_expectations.csv**: CSV file containing observations with codekata scores exceeding 15,000 points for the present week.
- **reached_expectations.csv**: CSV file containing observations with codekata scores between 10,000 and 15,000 points for the present week.
- **needs_improvement.csv**: CSV file containing observations with codekata scores between 7,000 and 10,000 points for the present week.
- **unsatisfactory.csv**: CSV file containing observations with codekata scores less than 7,000 points for the present week.
- **README.md**: Markdown file providing an overview of the task and instructions for running the code.

## Conclusion

By following the steps outlined in this repository, you will be able to merge the provided CSV files and categorize the data based on the "codekata" score. The resulting CSV files will allow you to identify observations that exceed expectations, meet expectations, need improvement, or are unsatisfactory. This categorization can provide valuable insights for further analysis and decision-making.

Feel free to explore the code and adapt it to your specific needs. Happy coding!
