![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Good Practices

* *Gareth Hughes & Beto Sibileau*. Data Barcelona (FT), April 2020.

## Description
The Week 3 Project consists on the analysis of two different sources providing Data about COVID 19 and Stock Market respectively. In the following we discuss the good practices to follow during the project workflow.

## Report on Good Practices
*  Label our jupyter notebooks by the section so that it's easier to get a quick overview of what that person is working on.
* Ensure that all functions, subsets and images are well defined and well labelled so that each team member can quickly analyse them without too much effort.
* With regard to Git, to begin with, utilise seperate files to commit our work to, before merging into one repository once all the projects are complete and the work is finalised.
* Our jupyter notebooks will consist of data importing, data cleaning and then subsequent data analysis with outputs of PNGs. We have decided to utilise PNGs are as our image format as Google Slides does not support SVG files and we don't require high resolution.
* The main library we are using in Python is Pandas. We first use it to access one of our Data Bases (`csv` source).
* On top of Pandas we use `pandas-datareader`, which in turn requires the package `requests` in order to access remotely our second Data Base (*Yahoo! Finance*).
* Finally, Data Visualisation is performed through Python library `matplotlib`.
