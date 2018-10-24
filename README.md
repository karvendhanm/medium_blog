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

1. Which country offers the best standard of living for a software developer?
2. If a developer codes as a hobby, does it have a positive influence on his remuneration?
3. Why developers start actively looking for a new job. Does it have anything to do with their compensation in the present job?
4. Do data scientist earn more than non data scientists on average?
5. Do data scientists earn more on average than non data scientists in all top ten economies?


## File Descriptions <a name="files"></a>

* data: Folder contains data files of StackOverflow developer survey data, follows name conventions of "YYYY.csv"
* so_developer_data_analysis.ipynb: The Jupyter Notebook used for the answering the above five questions.
* implied_ppp.csv: A .csv file inside ppp_data folder which in turn is inside data folder. This file contains each currency's exchange
rate with respect to US dollar. Also the implied purchasing power parity of each currency with respect to US dollar.

## Results<a name="results"></a>

The main findings of the code can be found at the medium post available [here](https://medium.com/@karvsmech/5-most-important-things-to-know-about-software-developers-f61eabfbef04).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the [data](https://insights.stackoverflow.com/survey). Otherwise, feel free to use the code here as you would like!
