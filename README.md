# Project Name

" Maternal and Reproductive Health - A Global Overview"


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Datasets](#datasets)
* [Setup](#setup)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- As we all know, a woman's body is under the influence of a myriad of hormonal changes from birth until her death. This includes menarche, monthly menstrual cycles, pregnancy and lactation, contraception/sterilization, menopause and post menopausal period. Since a woman's body goes through so many different hormonal phases, there needs to be some global indicators to measure how well she is doing in terms of her maternal and reproductive health. With the analysis of the dataset that I imported from WHO website, I am trying to find the global average for those health indices as well as finding those countries who do well or poor on those indices. In addition, by analyzing the datasets I obtained from UNESCO website, World Bank, and Wikipedia, I am looking to find if there is any correlation in my findings with those of religion, GDP Per-capita and adult literacy in such countries.

- Here are my areas of analysis:

1. What are some of the common indicators for maternal and reproductive health of females?

1. Proportion of girls in marriage  before 15 years of age

2. Proportion of women aged 15-49 who have their need for family planning satisfied with contraceptive use

3. Adolescent Birth Rate

4. Proportion of women with antenatal(pregnancy) care coverage

5. Proportion of child births in institutions

6. Still-birth (baby born dead) rates

7. Female genital mutilation or cutting

8. Are there any positive correlation between low GDP Per-capita and poor performance on health indices by countries?

9. Are there any positive correlation between low adult literacy and poor performance on health indices by countries?

10. Are there any positive correlation between religious practices and poor performance on health indices by countries?

## Technologies Used

- Python
- Tableau

## Datasets
1. WHO Dataset
- https://apps.who.int/gho/data/node.main.530?lang=en
2. Wikipedia
- https://en.wikipedia.org/wiki/Religions_by_country
3. World Bank Datasets
- https://data.worldbank.org/indicator/NY.GDP.PCAP.CD
- https://data.worldbank.org/indicator/SE.ADT.LITR.ZS

## Setup
- import pandas as pd
- import datetime
- import re
- import matplotlib.pyplot as plt
- import seaborn as sns
- %matplotlib inline

- Use, pd.read_csv('../data/file.csv') to
- Save the files as DataFrames
- Data cleaning process
- Merging cleaned DataFrames
- Webscrapping from the Wikipedia site of interest
- Convert the dataset to DataFrames
- Merging the new DataFrame with the previous one
- Use, df.to_csv("../data/df.csv") to convert the final DataFrame to a csv file
- Import the csv file to Tableau and prepare the Dashboard


## Project Status
Project is nearing completion

## Acknowledgements

- This project was inspired by the many women and young girls I cared for as their doctor in India and in the Middle East

- Many thanks to my incredible NSS DDA7 Cohort peers and Instructors for making this happen. I would also like to thank my loving family in supporting my endeavor.


## Contact
Created by Anjana Hassan(beenahassan1234@gamil.com) - feel free to contact me regarding this capstone project!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
