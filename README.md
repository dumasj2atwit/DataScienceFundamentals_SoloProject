# Final Project for Data Science Fundamentals - Jake Dumas

## Introduction


The purpose of this project was to gain experience in finding, cleaning, querying, and analyzing a dataset to build on the skills I have learned throughout the semester. I was tasked with locating a dataset, creating and answering two research questions, applying a machine learning technique, and creating this documentation. After some deliberation, my group settled on a dataset of video game sales from Kaggle, and I decided to use it to answer more questions. Following our decision These were the questions I decided to choose for myself:
* Which publishers dominate the video game market based on global sales?
* How has the number of game releases changed over time?

## Selection of Data


### Dataset Overview


My group chose our [dataset](https://www.kaggle.com/datasets/gregorut/videogamesales) both because of interest and because the large amount of numerical data would allow us to analyze it without too much transformation. Our dataset has several categories:
<img width="1182" height="450" alt="image" src="MainFrame.png"/>
* The Ranking/Index
* The name of the game at said place
* The platform the game was released
* The year of release
* The game's publisher
* The sales for North America (in millions)
* The sales for Europe (in millions)
* The sales for Japan (in millions)
* The sales for all other countries (in millions)
* The global/total sales overall (in millions)


### Dataset Cleaning


While the data was relatively clean, we still had about 2% (roughly 350 data points) of missing or N/A values. While much of this data was sufficiently low in the ranking to have little effect on our final outcome, we opted to fill in a large chunk of the missing data by hand. The missing data was contained almost entirely in the release year and/or publisher, which can be easily fact-checked and filled in. Through this effort, we reduced the about 350 missing values to 139, which is under 1% of our data. After bringing it to this point, we decided that our data was sufficient to work with and set it up for analysis of our topic questions.



### Data Oddities


Our dataset has a few oddities that we can't really fix or edit. The biggest oddity is that our data is missing sources from particular years, specifically 1979, 2018, and 2019. Some years also have very low numbers of logged releases, which will likely affect our conclusions, likely not significantly, but at least notably.


## Methods


### Packages


* Pandas
* Numpy
* Matplotlib
* Seaborn
  

### Charting/Machine Learning Applied

* Stacked Area Plot
* Scatter Plot
* Linear Regression
  

### Specific Analysis Features


To make working with our dataset easier, we decided to split our original dataset into several subframes during initialization. While most of these subframes were not utilized, they were a great initial foray into our data. By setting these up, we were able to better understand the information our data contained, explore several different ways to set up later frames, and use shorthands for particular data groups when asking questions.
<img width="1113" height="361" alt="image" src="Main Frame Setup + Subframes.png" />



## Results
