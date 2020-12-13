# GMIT Machine Learning and Statistic Module, Task assessment 2020
## Higher Diploma in Data Analytics, Lecturer: Ian McLoughlin
### Karolina Szafran-Belzowska, G00376368
***
This task assessment has been carried out as an assignment of the Machine Learning and Statistic module of the Higher Diploma In Data Analytics at GMIT.

The assessment was implemented in Jupyter Notebook **(tasks.jpynb)** using the Python programming language.

### How to run

1. Open Command prompt and findn the folder/directory where the local copy of the repository is stored.

2. Open the Jupyter Notebook using the command: Jupter Notebook.

3. With Jupyter Notebook open in your browser you can click "tasks.ipynb" and it will open the notebook in another tab.


### The following tasks are included in the Jupyter Notebook

**Task 1**: Square root of 2 function. 

Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.

**Task 2**: Chi-squared Test for Indendence. 

The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example, stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

**Task 3**: Microsoft Excel function for Standard Deviation.

The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) . However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

**Task 4**: k-means clustering of Ronald Fisher’s famous Iris flower data set.

Apply k-means clustering Ronald Fisher’s famous Iris flower data set using scikit-learn. Explain the k-means clustering code and accuracies achieved. Explain how the model could be used to make a prediction of the iris species.


### Libraries used:
- matplotlib: Python plotting library
- NumPy
- SciPy
- Pandas
- Scikit-learn

