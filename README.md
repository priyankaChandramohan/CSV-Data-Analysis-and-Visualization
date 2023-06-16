# CSV Data Analysis and Visualization

This repository contains solutions to analyze and visualize data from two CSV files. The provided tasks involve merging the CSV files, categorizing the data based on the "codekata" score, calculating averages, counting participation, identifying top performers, and creating visualizations.

## Problem Description

1. **Merge CSV Files**: Begin by importing the necessary libraries and merging the two CSV files into a single dataframe. This step ensures that all the data is consolidated for further analysis.

2. **Categorize Based on Codekata Score**: Split each CSV file into multiple categories based on the "codekata" score for the present week. The following categories should be created:

   - **Exceeded Expectations.csv**: Include observations where the "codekata" score exceeds 15,000 points for the present week.
   - **Reached Expectations.csv**: Include observations where the "codekata" score is between 10,000 and 15,000 points for the present week.
   - **Needs Improvement.csv**: Include observations where the "codekata" score is between 7,000 and 10,000 points for the present week.
   - **Unsatisfactory.csv**: Include observations where the "codekata" score is less than 7,000 points for the present week.

   Each category should be saved as a separate CSV file.

3. **Average of Previous Week Geekions vs. This Week Geekions**: Calculate the average of the "geekions" column for the previous week and the current week. Compare these averages to analyze the performance.

4. **Number of Students Participated**: Count the number of unique students who participated in the codekata.

5. **Average Completion of Courses**: Calculate the average completion rate for the Python course, MySQL course, Python English course, and Computational Thinking course.

6. **Rising Stars of the Week**: Identify the top three candidates who performed well in the particular week.

7. **Shining Stars of the Week**: Identify the top three candidates with the highest geekions.

8. **Department-wise Codekata Performance**: Create a pie chart to visualize the codekata performance based on departments.

9. **Department-wise Toppers**: Create a horizontal bar graph or any other visual representation to identify the top performers in each department.

## Repository Structure

This repository contains the following files:

- **Task Question.ipynb**: Jupyter Notebook file containing the task.
- **Solution.ipynb**: Jupyter Notebook file containing the code to perform the data analysis and visualization tasks.
- **data**: Folder containing the two CSV files provided for analysis.
- **exceeded_expectations.csv**: CSV file containing observations with codekata scores exceeding 15,000 points for the present week.
- **reached_expectations.csv**: CSV file containing observations with codekata scores between 10,000 and 15,000 points for the present week.
- **needs_improvement.csv**: CSV file containing observations with codekata scores between 7,000 and 10,000 points for the present week.
- **unsatisfactory.csv**: CSV file containing observations with codekata scores less than 7,000 points for the present week.
- **README.md**: Markdown file providing an overview of the tasks and instructions for running the code.

## Conclusion

By following the steps outlined in this repository, you will be able to merge the provided CSV files, categorize the data based on the "codekata" score, calculate averages, count participation, identify top performers, and create visualizations. The analysis and visualizations will provide insights into the performance of students, department-wise codekata performance, and course completion rates.

Feel free to explore the code and adapt it to your specific needs. Enjoy analyzing and visualizing the data!

If you have any questions or need further assistance, please feel free to reach out.

Happy coding!
