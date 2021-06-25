# world_happiness
> An analysis of the state of global happiness through survey data from the World Happiness Report.

# Installation needed
> Run on Python 3.8.5. No packages outside of those included in the Anaconda distribution are needed.

# Project motivation(s)
> My main interest in analyzing these data were to see how the COVID-19 pandemic has impacted
happiness around the globe. Some of the questions/goals of this project included:

1. What countries/regions are happiest?
2. What parameters correlate most positively/negatively with happiness?
3. How'd COVID impact happiness around the world?
4. Can we build a model that predicts happiness using supervised ML?

# Files for project
> There are two source datasets here that provide the survey data for the analysis. They include:

1. world-happiness-report-2021.csv: Includes happiness score and various parameters for the year 2021 (rolling 3-year average)
2. world-happiness-report.csv: Happiness score and various parameters from 2005-2020.

> There is a single Jupyter Notebook (world_happiness.ipynb) that work through these data to answer the questions noted above.

# Results summary
1. What countries/regions are happiest? **The Scandinavian and Northwestern European countries are the happiest in the world. Finland, Denmark, and Sweden make out the top three.**
2. What parameters correlate most positively/negatively with happiness? **Not too surprisingly, a country's wealth and healthy life expectancy are the top factors in happiness, whereas sense of corruption most negatively impacts happiness. Somewhat surprisingly, generosity doesn't appear to be a positive influence on one's happiness.**
3. How'd COVID impact happiness around the world? **Of the sub-sample of 93 countries investigated, while the mean happiness score did decrease slightly, there was no statistical significance in this difference. It appears us humans are overall pretty resilient (our moods, not our immune system) to life-altering global pandemics.**
4. Can we build a model that predicts happiness using supervised ML? **We were able to build a pretty successful simple linear model to predict happiness based on 7 parameters. Our model's r2 = 0.76.**

# Licensing, Authors, Acknowledgements
> Ajaypal Singh provided the dataset on from Kaggle (https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021). These data are originally from the World Happiness Report (https://worldhappiness.report/).
