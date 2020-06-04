# Star Wars Survey

This folder contains data behind the story [America’s Favorite ‘Star Wars’ Movies (And Least Favorite Characters)](https://fivethirtyeight.com/features/americas-favorite-star-wars-movies-and-least-favorite-characters/).

I have here used this data to conduct a series of statistical inferences designed to identify which demographics in the population have the highest ratio of fans. Here are the files included in this document:

1) A folder of all images created in this study (using Python's pyplot from matplotlib, generated in jupyter notebook)

2) Presentations (folder) - A summary of the data for use in a presentation, perhaps to a marketing team. Included in multiple formats - pdf, powerpoint, and a collection of each slide as a png image to allow viewing in multiple environments/operating systems.

3) Star Wars Survey - Analysis of Target Market.ipynb: a jupyter notebook file, in which all work was completed. The data file is imported and manipulated using Python and the Pandas module, while many assessments are done using the NumPy module. Statistical hypothesis tests are calculated using the Scipy.stats module. Graphical representations of data is generated using pyplot from matplotlib.

4) Star Wars Survey - Analysis of Target Market.pdf: a pdf version of the jupyter notebook file, so that those who do not/can not run jupyter notebook locally can still view the work completed (contains all information in the notebook).

5) StarWars.csv: The data file itself, from which this study was performed (from fivethirtyeight.com).

6) stat_funcitons.py: a python script of my own making. Contains several simply functions that appeared to be missing from the Scipy.stats documentation, mostly used for easy of flow without having to type mathematical formulas in over and over. Contains several formulas, including a converter to make a two-tailed probability, calculations of confidence intervals, short funtions to convert ratios into z-scores and t-scores, and a few hypothesis tests, among other things. A more complete documentation can be found at https://github.com/LawlessJ/Stat-functions.