# medium_blog
writing a blog on medium using stack overflow data

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the libraries preinstalled in Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*. Following are the libraries used in this project.

1. pandas
2. numpy
3. matplotlib
4. scipy
5. glob
6. os
7. re



## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Stack Overflow data from 2014 to 2018 to better understand:

1. Which country offers the best standard of living for a software developer if we factor in implied purchasing power parity?
2. If a developer codes as a hobby besides coding at work, does it have any positive impact on his salary?
3. Why developers start actively looking for a new job. Does salary have anything to do with it?
4. Is it really true that data scientists earn more than other developers?
5. If data scientists do earn more, are they earning more in all countries?


## File Descriptions <a name="files"></a>

* data: Folder contains data files of StackOverflow developer survey data, follows name conventions of "YYYY.csv"
* so_developer_data_analysis.ipynb: The Jupyter Notebook used for the answering the above five questions.
* implied_ppp.csv: A .csv file inside ppp_data folder which in turn is inside data folder. This file contains each currency's exchange
rate with respect to US dollar. Also the implied purchasing power parity of each currency with respect to US dollar.

## Results<a name="results"></a>

The main findings of the code can be found at the medium post available [here]().

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the [data](https://insights.stackoverflow.com/survey). Otherwise, feel free to use the code here as you would like!
