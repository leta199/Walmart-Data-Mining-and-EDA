# Walmart-Data-Mining-Exploratory-Data-Analysis

## ABOUT THIS PROJECT 
This project applies exploratory data analysis (EDA) as well data mining techniques to uncover insights into potential opportunities and trends within Walmart Inc for 7888  of customers and their purchases. 
This dataset describes Walmart National's orders shipped out from the years 2021 to 2025. I aim to gleam insights into:
-understanding sales outliers
-key perfomance regions 
-sales and profit correlation and change over time 

## HOW IT'S MADE 

Languages used: R verion (4.5.1)  
Packages and modules: tidyverse, lubridate  
Environment: RStudio 

[![Language: R](https://img.shields.io/badge/Language-R-276DC3.svg?style=flat-square)](https://www.r-project.org/)
[![Built with RStudio](https://img.shields.io/badge/IDE-RStudio-75AADB?style=for‐the‐badge&logo=rstudio&logoColor=white)](https://www.rstudio.com/)
![Status](https://img.shields.io/badge/Status-Completed-lightgrey)

### DATA
 [Walmart Dataset](https://drive.google.com/file/d/1gyeK2_uO6hLPQTBBAk4YdNHkBhlXmsz3/view)  
 Vaiables- 21 variables including: shipping modes, sales amount per purchase, profit per purchase, city and region  
Obeservations- 8058 


Data Cleaning    
**Removing duplicate values** while checking to make sure there are no more duplicate rows with the `is.na()` ` and colSums()` functions.   
**Impute missing values** using a for loop and replacing missing values with medians on numeric columns.  
**Format**- of the date columns was changed with  `is.Date()`  and  excess whitespace was trimmed to ensure consistency with a for loop and  `trimws()` function.   
**Factorisisation** turned all character attributes into factors to apply statsitical summary functions such as `summary()` .

## METHODS AND TECHNIQUES  
**Summary statistics**   
Using the `summary()` function.
Delved into the attrubutes using the `str()` function.

**Exploratory Data Analysis**  
Bar charts- to visualise frequncy of region purchases, and product segment sales.   
Scatterplot- to visualise the correlation between sales and profit.  


**Data Mining**  
Time series charts- to track trends in profit over time as well as track sales over time and across product segment.   
Boxplots- to identify outliers. 

## KEY FINDINGS AND INSIGHTS 

**Major Insights:**

1)There is a large range in spending  across individual sales of $17,489.  
2)Walmart experinces their greatest profit spike during winter holiday season i.e Q4 of 2021- 2024.  
3)The consumer market experienced the largest growth of all segments in Q4 of 2024.  
4)South and Central regions deliver the lowest profit of all regions.  
5)New York City and California are the most frequent purchase regions.  
6)Edawrd Hooks is the most frequent customer.   
## Setup & Installation 

Clone this repository and navigate into the project directory:

`git clone https://github.com/YourUsername/Walmart-Data-Mining-and-EDA.git`  
`cd Linear-Regression`

**Usage**
Since there are 

Note: this projects uses relative file paths therefore all imports such as of the `Walmart Dataset.csv` file should be okay as long as file structure remains the same. 


## PROJECT STRUCTURE   
[Walmart‑Data‑Mining‑and‑Exploratory‑Data‑Analysis](https://github.com/leta199/Walmart-Data-Mining-and-EDA)  
├── [raw_data](https://github.com/leta199/Walmart-Data-Mining-and-Exploratory-Data-Analysis-/tree/main/raw_data)  
├── [source_code](https://github.com/leta199/Walmart-Data-Mining-and-Exploratory-Data-Analysis-/blob/main/source_code/Walmart_visualisations_and_insights.r)  
├── [visualizations](https://github.com/leta199/Walmart-Data-Mining-and-Exploratory-Data-Analysis-/tree/main/visualizations)  
├── [README.md](https://github.com/leta199/Walmart-Data-Mining-and-Exploratory-Data-Analysis-/blob/main/README.md)  
└── [report.md](https://github.com/leta199/Walmart-Data-Mining-and-Exploratory-Data-Analysis-/blob/main/report.md)

This is for educational purposes only. 
## POSSIBLE EXTENSIONS   
-I would look into a histogram over the sales abd profit to determine the skew of these variables.   
-Additionally, I would like to apply correkation maps to reveak the unexpected correlations.  
-Finally, machine learning algorithms to help predict future profit ahd sales trends  by region and customer would be powerful. This would help reveal the customers that will churn 
 for better customr retention recommendations. 

## AUTHORS 

[leta199](https://github.com/leta199)
