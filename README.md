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

1) As expected, USA provides the best standard of living for its developers. Surprisingly countries like Saudi Arabia, South Africa, Thailand and Turkey have broken into top five.
2) Developers who code as a hobby, like contributing to open source projects, do not seem to have a clear advantage over developers who don't code as a hobby with respect to salary.
3) Job satisfaction has a clear association with salary. The better the salary is, the more the job satisfaction.
4) Data scientists do earn more than non data scientists on average.
5) Data scientists do not earn more than non data scientists in all countries. In some countries they earn more and in some countries they earn less than non data scientists.

You could find more details and visuals at the medium blog post available [here](https://medium.com/@karvsmech/5-most-important-things-to-know-about-software-developers-f61eabfbef04).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the [data](https://insights.stackoverflow.com/survey). Otherwise, feel free to use the code here as you would like!
