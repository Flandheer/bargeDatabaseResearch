# bargeDatabaseResearch

## Intro
Research into the creation of an fundamental barge database. Fundamental meaning consisting of length, width and capacity information. The script imports the data, analysis, cleans and enriches it by filling NA values.

You can fond more details in my blog post at Medium [Medium](https://medium.com/@frank.landheer/a-complete-barge-directory-cf97edef3e59) 

## Installation
Research is written in python using Jupyter Notebook. The data is retrieved from on online source and offered in .csv file. Machine learning techniques are used to enrich the data. To run the following packages are needed

* Jupyter notebook
* pandas
* numpy
* seaborn
* matplotlib.pyplot
* statsmodels
* scipy
* sklearn

## Process Breakdown

### Business objectives
What is an adequate database of barges for brokers? This question of course depends on the workfield of brokers. Transporting oils and minerals requires a different set of information than transporting containers. However, in the basics the broker will ask two questions. Will the cargo fit and can the barge go to the destination? These primarily questions are answered by the dimensions of the barge: length, width and capacity. An adequate database, for now, would be a database filled with this information.

### Assess situation
For this initial setup the resources are limited to man hours.

### Determine data mining goals
Finding a source that offers a barge database and see if the data can be made adequate on scale with the source or cleaning methodologies.

### Project plan
- Find data source
- Evaluate value data source
- Process and clean data
- Enrich data if necessary
- Offer database in the form of a CSV document

## Summary
By gathering information from an external source (vessel finder) and cleaning that information, conclusions about the information can be drawn. The analysis based on the data vizualisation shows an complete database but with data fields that have strong correlations with each other. By using machine learning techniques for linear regression problems that non values are filled and a fully filled database is returned in the form of a .csv file

