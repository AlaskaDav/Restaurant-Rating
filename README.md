# Restaurant-Rating In MEXICO

## Table of Content 

- [Description](#description)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [ETL Processing](#etl-processing)
- [Recommended Analysis](#recommended-analysis)
- [Data Analysis Procedures](#data-analysis-procedures)
- [Results and Findings](#results-and-findings)

### PROJECT

## Restaurant Ratings

### Project Description
 
Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences. 

#### Data Source

Restaurant Rating Data : The data sets used for the analysis includes; 
- Customer_preference.csv: containing the number of flights in the country
- Consumers.csv: contains the number of different airline
- Restaurant_Cuisines.csv: this file contains different e=airports and locatio within the country
- Restaurants.csv: contains the number of cancellation that occured within the perios of analysis.
- Rating.xls

#### Tools Used 

- Microsoft Excel: for easy access the contents of the file and understanding of the components of the data.
    - [Download here](http://microsoft.com)
- Powerquerry : To carry ETL process on the data
- PowerBI: For visualization and creating reports

#### ETL Processing

In the initial data preparation process, the following process was performed
1. Data Extraction: extracting data files (.csv files) from Microsoft Excel into Powerquerry for cleaning and transformation
2. Transformation process taken place involves:
   - Promeoted headers
   - Changing data types
   - Removing duplicate values
   - Removing null Values in the data
   - Removing empty rows and columns
   - Creating new columns by adding conditional column
4. Loading process involves loading the completely transformed and cleaned data into PowerBI to build dashboard for reporting and visualizations.
 
#### Recommended Analysis

1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?
2. What are the consumer demographics? Does this indicate a bias in the data sample?
3. Are there any demand & supply gaps that you can exploit in the market?
4. If you were to invest in a restaurant, which characteristics would you be looking for?

#### Data Analysis Procedures:

- Collected data through .csv files from MsExcel.
- Uploading the data into PowerQuery for Cleaning and analysing the contents of the data
- Requested for data clarification and data validity.
- Conecting the tables together using the approriate Primary key and the foreign key.
- Loaded the data into PowerBi for visualization and Presentation.
- Providing insights, presenting informations and advice.
- Creating outstanding reports for end user understanding, board of directors and shareholders.

#### Results and Findings

The analysis results are summarized as follows;
1. The restaurant with the highest rating is **Tortas Locas Hipocampo**( while the lowest rating restaurant is Restaurant Los Compadre. However, consumer's preference and interest in a restaurants has no contribution to the restaurant ratings. Because from the dashboard report, it shows that Tortas Locas Hipocampo which has the highest rating actually has one of the lowest customer preference.
2. From the data gotten, i was able to analyse the customers into different Age Band/Age Range from their Ages as Youths and Adults which eventually supported my entire analysis shows that customers with age range:
   (a) Youth -
   (b) Adults -
3. The Customers demography also includes the marital status i.e Married and singles. The Single Customers are recorded to be the highest customer with almost **90%** of the total population and the customers that are married has **7.25%** while the uncategoriezed customers took the **2.9%** of the customer population.
4. Considering the level of demand and supply, i would focus my target in city that has the highest level of drink and number of restaurants (San Lius Potosi) and the restaurant with the highest population of singles and youth customers ( inorder to generate a high level of turn over as a result of high level of demand.

#### Recommendations
Based on the analysis, I recommend the following actions:
 - Improvement of airport infrastructure and managements
 
#### Limitations

There was a difficulty in representing the insight from the data in periods, so, I had to create a Date table independently from the data and then built a relationship in the model table so as to present the report in a well organized periodic manner i.e Month reporting and Dayl)


🇲🇽  🥘
💻

|Heading1|Heading2|Heading3|
|--------|--------|--------|
|Content1|Content2|Content3|
|Excel |PowerQuerry |PowerBI |

