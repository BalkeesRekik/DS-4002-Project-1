# DS4002 Project 1: Sentiment Analysis in Fake vs. Real News 

## Overview
This repository contains all materials related to DS4002 Project 1, which analyzes sentiment in fake vs. real news articles in proximity to the 2016 US presidential election. The project invesigates whether fake news articles tend to have more negative sentiment than real news and whether sentiment in fake news changed as the 2016 US presidential election approached.

## Software and Platform Used
Python was used for data processing, analysis, and visualization.
some of the packages we used: 
- pandas – For data manipulation and preprocessing.
- matplotlib & seaborn – For data visualization.
- VADER – For sentiment analysis.
- wordcloud – To generate word clouds for frequent words in fake vs. real news.
- nltk - For text preprocessing
- mannwhitneyu - For statistical analysis (Mann Whitney U test)

The platform used for development was Google Colab via a juptyer notebook

## Documentation Map

DS-4002-Project-1 

```
│── 📂 DATA 
    ├── 📂 initial_data 
      ├── Fake.csv      
      ├── True.csv
    ├── 📂 analyzed_data 
      ├── filtered_news.zip     
      ├── Data Appendix.pdf    
│── 📂 OUTPUT 
│── 📂 SCRIPTS
    ├── DS 4002 Project 1.ipynb
│── LICENSE 
│── README.md     
```

## Section 3: Instructions for Reproducing Results
To reproduce the results of this study, follow the steps below:

### **1. Clone the Repository**
First, clone this repository to your local machine. In order to that, run this command
```
git clone https://github.com/BalkeesRekik/DS-4002-Project-1.git
```
### **2. Run the Script**
- Go to the SCRIPTS directory and find the DS 4002 Project 1.ipynb
- After finding the jupyter notebook, you can simply run it to reproduce all the results of this project
- There are comments throughout the script to describe how the code works
```
│── 📂 SCRIPTS
    ├── DS 4002 Project 1.ipynb
```
## References
[1] “Mann-Whitney U Test: Assumptions and Example,” Informatics from Technology Networks. Accessed: Feb. 16, 2025. [Online]. Available: http://www.technologynetworks.com/informatics/articles/mann-whitney-u-test-assumptions-and-example-363425
[2] C. Hutto and E. Gilbert, “VADER: A Parsimonious Rule-Based Model for Sentiment Analysis of Social Media Text,” ICWSM, vol. 8, no. 1, pp. 216–225, May 2014, doi: 10.1609/icwsm.v8i1.14550.

