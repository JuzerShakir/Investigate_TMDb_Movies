# My Third Project in Machine Learning Foundation Nanodegree
# Investigate a Dataset
## Project: Investigate TMDb Movie Database 

<p align="center"><img src="TMDb_movie.jpg"></p>

----

### Table Of Contents:
- [Description](#description)<br>
    - [About the project](#about-the-project)<br>
    - [What needs to be done](#what-needs-to-be-done)<br>
    - [Why this project](#why-this-project)<br>
- [Data](#data)<br>
    - [Files](#files)<br>
    - [Dataset file](#dataset-file)<br>
- [Loading Project](#loading-project)<br>
    - [Requirements](#requirements)<br>
    - [Execution](#execution)<br>
- [Conclusion](#conclusion)<br>
    - [What I learned](#what-i-learned)<br>
    - [Evaluation](#evaluation)
    - [Results](#results)

----


### Description

#### About the project

In this project, I have to choose any one Dataset for investigation out of 4. Click [here](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True) to open a document with links and information about datasets that I can investigate for this project.

I have choosen `TMDb Movie Data` for my Investigation in this project. 

#### What needs to be done

For the this project, I will conduct my own data analysis and create a file to share my findings. I will start by taking a look at the dataset and brainstorm what questions I could answer using it. Then i will use pandas and NumPy to answer the questions that I am most interested in, and create a report sharing the answers. I have not been required to use inferential statistics or machine learning to complete this project, but I will make it clear in my communications that my findings are tentative. This project is open-ended in that they aren't looking for one right answer.

#### Why this project

In this project, I'll go through the data analysis process and see how everything fits together. I'll use the Python libraries NumPy, pandas, and Matplotlib which make writing data analysis code in Python a lot easier! Not only that, these are sought-after skills by employers!

----

### Data

#### Files

This project contains 2 files and 1 folder:
- `tmdb_movies_data.csv` : The dataset file containing 10k+ entries of movies that I have worked on. 
- `Investigating_Database.ipynb` : The investigation of the dataset has been done in this jupyter notebook file. 
- `export/` : Folder containing HTML and PDF file of notebook.

#### Dataset file

This data set contains information about 10,000 movies collected from The Movie Database (TMDb). Contains data such as `title, cast, director, runtime, budget, revenue, release year` etc. 
- Certain columns, like `‘cast’` and `‘genres’`, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the `‘cast’` column. Nothing to care much of, I leave them as is.
- The final two columns ending with `“_adj"` show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

-----

### Loading Project

#### Requirements

This project requires **Python 3** and the following Python libraries installed:

- [Python 3.6.5](https://www.python.org/downloads/release/python-365/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 


#### Execution

In a terminal or command window, navigate to the top-level project directory `Investigate_TMDb_Movies/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Investigating_Database.ipynb
```  
or
```bash
jupyter notebook Investigating_Database.ipynb
```

This will open the Jupyter/iPython Notebook software and project file in your browser.

-----

### Conclusion

#### What I learned

 - What all steps are involved in a typical data analysis process.
 - Comfortable posing questions that can be answered with a given dataset and then answering those questions.
 - Know how to investigate problems in a dataset and wrangle the data into a format that can be used.
 - Have practice communicating the results of the analysis.
 - Being able to use vectorized operations in NumPy and Pandas to speed up your data analysis code.
 - Being familiar with Pandas Series and DataFrame objects, which lets access data more conveniently.
 - Last but not least, Know how to use Matplotlib and Seaborn to produce plots showing findings.
 

#### Evaluation
My project was reviewed by a Udacity reviewer against the **<a href="https://review.udacity.com/#!/projects/3176718735/rubric" target="_blank">Investigating a Dataset rubric</a>**. All criteria found in the rubric must be *meeting specifications* for me to pass.

#### Results
[My Project Review by an Udacity Reviewer](https://review.udacity.com/#!/reviews/989156)

----