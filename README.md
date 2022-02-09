# Machine Learning for Shopify Data

![]()


Data Science project using Supervised Machine Learning to predict LTV and repeat customers for Shopify order exports. Code can be replicated so that Shopify Store Owners can repeat this analysis. 

**Key Findings:** 
- _Regression models_ using data shopify provides explain **4%** of variance in customer LTV. 
- _Classification models_ identified ~ **80%** of repeat customers correctly.

## Table of Contents: 
**I. Data Source**
 - [Shopify Order Exports](https://help.shopify.com/en/manual/orders/export-orders)
 Data comes from Shopify store that specialized in fitness fashion. Please see link above for Shopify's instructions for order export for your store. 

**II. Jupyter Notebooks**
 - [Data Exploration](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/1.Preliminary_Analysis/Preliminary_Wrangling%26EDA.ipynb) -- Exploring our data and determining LTV Range. 
 - [Data Wrangling](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/2.Data_Wrangling/Data_Wrangling.ipynb) -- Reshaping original raw export to get a cleaned customer LTV table. 
 - [Exploratory Data Analysis](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/3.Exploratory_Data_Analysis/EDA.ipynb) -- Exploring which variables correlate with our target LTV and Repeat Customer Variables. 
 - [Modelling](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/tree/main/4.Modelling)
    1.   _Regression Models_: Use of 2 different models to predict post first week spend
    2.   _Classsification Models_: Used 4 different models to predict if customers order past the first week on the platform.

 **III. Supporting Documentation**
 - [Final Report](https://awesomeopensource.com/project/elangosundar/awesome-README-templates) -- Report Summarizes Tech
 - [Presentation](https://github.com/matiassingers/awesome-readme) -- Presentation on Project Purpose, Steps Undertaken and Results
 - [Metrics File]() -- Excel Doc Sumamrizing Metrics from the documnet
 
## Acknowledgments 
Special thank you to: 

- Ben Bell
- Lou Graniou

## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.