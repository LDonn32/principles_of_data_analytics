# Principles of Data Analytics

By Laura Donnelly


## Contact Details:
Student ID: G00472977

Contact Email: G00472977@atu.ie

## TO DO - 


Tidy up Task 9 references. Task 9 i have using r2 score and manually doing it, will prob go with r2 score version of code as it is easier, but need to add clearer comments, markdown explainations as well as double check references are in write place and all added, none missed. Should be last task to do before going over everything and moving all imports to the top 

Go over the read me and typos 


## Introduction

This repository holds weekly tasks for the Principles of Data Analytics Module for the Higher Diploma in Computer Science in Data Anayltics course, ATU.
Ten tasks were assigned and completed using a Jupyter notebook. The Jupyther Notebook, tasks.ipynb contains all the code. The markdown cells will contain insights and comments on the code's function. The markdown cells will also include references of resources used to complete the tasks. 

This ReadMe file will give an overview of the following:

- How to set up the environmemt to run the code in the tasks.
- The technologies used for this module.
- The packages used for this module.
- The weekly tasks outlined.

## Repository Contents:
tasks.ipynb: Jupyter Notebook that contains all ten assigned tasks with the code, explanations for the code and references.

requirements.txt: List of the Python packages required to run the notebook.

.gitignore: Specifies files and directories to be ignored by Git.

## Setup your own repository

1. Sign up for a free GitHub account.
2. Go to the repository page in your browser.
3. Click the green Code button.
4. Click the Codespaces tab.
5. Click Create new Codespace on main.


# Clone the Repository:
```
git clone https://github.com/LDonn32/principles_of_data_analytics.git

```
# Install Required Packages:
```
pip install -r requirements.txt
```
Please see [Github.com](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) for reference on cloning repository.


## Technologies used:

- Python
- Git
- GitHub
- Codespaces
- Jupyter

## Packages used:
Please refer to the requirements.txt file to see what packages were used for this Jupyter notebook.

## Weekly Tasks Outline

**Task 1: Source the Data Set**
Import the Iris data set from the sklearn.datasets module.
Explain, in your own words, what the load_iris() function returns.

**Task 2: Explore the Data Structure**
Print and explain the shape of the data set, the first and last 5 rows of the data, the feature names, and the target classes.

**Task 3: Summarize the Data**
For each feature in the dataset, calculate and display:

mean
minimum
maximum
standard deviation
median

**Task 4: Visualize Features**
Plot histograms for each feature using matplotlib.
Add appropriate titles and axis labels.

**Task 5: Investigate Relationships**
Choose any two features from the data set and create a scatter plot of them.
Color-code the three different classes of the scatter plot points.

**Task 6: Analyze Relationship**
Use numpy.polyfit to add a regression line to the scatter plot from Task 5.

**Task 7: Analyze Class Distributions**
Create box-plots of the petal lengths for each of the three classes.

**Task 8: Compute Correlations**
Calculate the correlation coefficients between the features.
Display the results as a heatmap using matplotlib.

**Task 9: Fit a Simple Linear Regression**
For your two features in Task 5, calculate the coefficient of determination 
R
2
.
Re-create the plot from Task 6 and annotate it with the 
R
2
 value.

**Task 10: Too Many Features**
Use seaborn to create a pairplot of the data set.
Explain, in your own words, what the pairplot depicts.


## Key Resources Used: 

Below are resources used frequently for the tasks but they are referenced directly in the Jupyter Notebook. 

[Panda Documentation](https://pandas.pydata.org/docs/)

[Numpy Documentation](https://numpy.org/doc/)

[Matplotlib Documentation](https://matplotlib.org/stable/users/index.html)

[Seaborn Documentation](https://seaborn.pydata.org/)

[scikit-learn.org](https://scikit-learn.org/stable/index.html)

[Geeksforgeeks.org](https://www.geeksforgeeks.org/)

[W3schools.com](https://www.w3schools.com/)

I used [ChatGBT](https://chatgpt.com/)chatGBT for support and prompts were referenced in the Jupyter Notebook.


## Additional Resources used: 

[www.kaggle.com](https://www.kaggle.com/code/shrutimechlearn/step-by-step-pca-with-iris-dataset?scriptVersionId=11461313&cellId=7)

[Iris Dataset Archive UCI ]( https://archive.ics.uci.edu/datasets/)


