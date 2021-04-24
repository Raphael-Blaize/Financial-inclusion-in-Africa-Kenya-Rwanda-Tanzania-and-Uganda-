# Financial-inclusion-in-Africa-Kenya-Rwanda-Tanzania-and-Uganda

# Overview 

* Financial Inclusion remains one of the main obstacles to economic and human development in Africa. For example, across Kenya, Rwanda, Tanzania, and Uganda only 9.1 million adults (or 13.9% of the adult population) have access to or use a commercial bank account.

* Traditionally, access to bank accounts has been regarded as an indicator of financial inclusion. Despite the proliferation of mobile money in Africa and the growth of innovative fintech solutions, banks still play a pivotal role in facilitating access to financial services. Access to bank accounts enables households to save and facilitate payments while also helping businesses build up their credit-worthiness and improve their access to other financial services. Therefore, access to bank accounts is an essential contributor to long-term economic growth.

* The research problem is to figure out how we can predict which individuals are most likely to have or use a bank account. Your solution will help provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania, and Uganda, while providing insights into some of the key demographic factors that might drive individuals’ financial outcomes.

#### -- Project Status: [Completed]

## Project Intro/Objective
* The research problem is to figure out how we can predict which individuals are most likely to have or use a bank account

### Partner
* [Moringa School]
* https://moringaschool.com/

### Methods Used
* Descriptive Statistics
* Data Visualistaion Techniques
* Data Analysis
   * EDA Univariate Analysis
   * Bi-variate Analysis
   * Multivariate Analysis

### Technologies
* Python
* Pandas,Numpy,Gooogle Colab

```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
from pandas_profiling import ProfileReport
!pip install pandas==1.2.4
!pip install pandas-profiling==2.7.1
```

## Data Used
 * Data Soruces used
    * Variable Definitions: http://bit.ly/VariableDefinitions
    * Dataset: http://bit.ly/FinancialDataset
    * LINKS TO WHERE THE DATA WAS EXTRACTED FROM
        * FinAccess Kenya 2018. https://fsdkenya.org/publication/finaccess2019/
        * Finscope Rwanda 2016. http://www.statistics.gov.rw/publication/finscope-rwanda-2016
        * Finscope Tanzania 2017. http://www.fsdt.or.tz/finscope/
        * Finscope Uganda 2018. http://fsduganda.or.ug/finscope-2018-survey-report/
  * Data Analysis used
      * Univariate Analysis 
          * [EDA.HTML](https://github.com/Raphael-Blaize/Financial-inclusion-in-Africa-Kenya-Rwanda-Tanzania-and-Uganda-/blob/main/output%20(1).html)
          * Frequency Distibutions
          * Bar graphs
          * Descriptive Statistics
              * Standard deviation
              * Mean
              * Variance
              * Skewness
              * Kurtosis
          * Histograms
       * Bivariate Analysis
           * Stacked column chart to understand the variables better and how the correlate
       * Univariate Analysis 
           * Removing Multicollinearity from our dataset
           * LDA Analysis
        
  * Challenge Book list
     * Define the question, the metric for success, the context, experimental design taken and the appropriateness of the available data to answer the given question
     * Find and deal with outliers, anomalies, and missing data within the dataset.
     * Perform univariate, bivariate and multivariate analysis recording your observations
     * Implement the solution by performing the respective analysis i.e. factor analysis, principal component analysis, and discriminant analysis.
     * Challenge your solution by providing insights on how you can make improvements
  
## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Visualisation
- EDA 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate
