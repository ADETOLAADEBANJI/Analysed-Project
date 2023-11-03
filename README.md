#  India's Credit Card spending Analysis

### Project Overview

  This project contains a dataset that gives valuable insights into credit card transactions that were made in India, providing an elaborate view of the spending habits across the country. The dataset consists of variables, including gender, card type, city, expense types, and transaction amounts. By exploring this dataset, researchers and analysts can see through trends in customer spending and see the correlations between different data points, enabling them to derive valuable business intelligence.


### Data Source

  The primary dataset used for this analysis is the "credit card transactions-India-simple-csv" file, containing detailed information about credit card transactions of the country.Link to the dataset:
 (https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india)

### Tools
 
 Powerbi: Data cleaning,Formatting and Visualization

### Data Cleaning and Prepearation
 
In the initial data preparation phase, we performed the following tasks:
1.	Data loading and inspection.
2.	Data cleaning and formatting.

### Explanatory Data Analysis:

The following informations were checked
- The Expense types with the lowest and highest transactions
- The highest card type used
- Rankings of the month and year with the card transactions made 
- Gender with the credit card transactions made
- And the cities of which the different levels of transactions were made 


### Data Analysis

Include some interesting code/features worked with

```Dax

  Date_table = CALENDARAUTO()

  Selected column = {
    ("Card Type", NAMEOF('Credit Card Data'[Card Type]), 0),
    ("Exp Type", NAMEOF('Credit Card Data'[Exp Type]), 1)
  }

  Top N Value = SELECTEDVALUE('Top N'[Top N])
```

### Research 

This data gives the opportunity to conduct research on credit card usage, consumer behavior. This analysis uncover patterns, trends, and relationships within the data to gain a better understanding of credit card spending habits in India.
The analysis identified distinct customer’s spending habit, giving visualizations on transactions by month name and  gender, transactions amount by expenses type in percentage and in total, transactions amount made by the  different cities the card type used and many more.


### Dashboard


![india spending habit dashboard 2](https://github.com/ADETOLAADEBANJI/Analysed-Project/assets/149164492/80a1e7a5-7511-48c5-b673-cfd7e2a225f6)
