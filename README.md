# DS4002 Project 1: Sentiment Analysis in Fake vs. Real News 

## Overview
This repository contains all materials related to DS4002 Project 1, which analyzes sentiment in fake vs. real news articles in proximity to the 2016 US presidential election. The project invesigates whether fake news articles tend to have more negative sentiment than real news and whether sentiment in fake news changed as the 2016 US presidential election approached.

## Research Question: 
Does the sentiment score of news articles from the ISOT Fake News Dataset tend to be more negative among fake news articles compared to real news? Does the sentiment of fake news
become more negative in proximity to the 2016 presidential election?

## Hypotheses
- H1: The mean sentiment score of fake news articles is significantly lower (more negative) than the mean sentiment score of real news articles.  
- H2: The mean sentiment score of fake news articles before 08 November 2016 is significantly lower (more negative) than the mean sentiment score of fake news articles after 08 November 2016.

## Software and Platform Used
Python was used for data processing, analysis, and visualization.
some of the packages we used: 
- pandas – For data manipulation and preprocessing.
- matplotlib & seaborn – For data visualization.
- VADER – For sentiment analysis.
- wordcloud – To generate word clouds for frequent words in fake vs. real news.


## Documentation Map
In this section, you should provide an outline or tree illustrating the hierarchy of folders and subfolders contained in your Project Folder, and listing the files stored in each folder or subfolder.

DS-4002-Project-1 │── 📂 DATA │ ├── 📂 initial_data │ │ ├── Fake.csv │ │ ├── True.csv │── 📂 OUTPUT │── 📂 SCRIPTS │── 📜 LICENSE │── 📜 README.md          

## Section 3: Instructions for Reproducing Results
In this section, you should give explicit step-by-step instructions to reproduce the Results of your study. These instructions should be written in straightforward plain English, but they must be concise, but detailed and precise enough, to make it possible for an interested user to reproduce your results without much difficulty. N.B. This section will be crucial for the CS1 assignment, where you'll be required to reproduce the results of other groups. Therefore, make sure to explain this section thoroughly. 
