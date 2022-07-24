# Machine Learning for Shopify Stores 

![](Images/online-shopping-credit-cards.jpg)


Data Science project using supervised machine learning to predict customer Lifetime Value (LTV) and repeat customers for stores running on the Shopify platform, using order exports. Code can be replicated so that store owners can derive business insights on the behavior of their customers. All information pertaining to customer and company identity for this analysis has been removed / anonymized. For questions, feedback or help with deriving customer insights for your business, please feel free to reach out to me at bbellman95@gmail.com 

**Key Findings:** 
- _Classification models_ identified **80%** of repeat customers correctly.
- _Regression models_ of Shopify store data explain **4%** of variance in LTV post first week spending.
 

## Table of Contents: 
**I. Data Source**
 - [Shopify Order Exports](https://help.shopify.com/en/manual/orders/export-orders) --
 Data comes from Shopify store that specialized in fitness apparel. Please see link above for Shopify's instructions to export your store data. 

**II. Jupyter Notebooks**
 - [Data Exploration](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/Jupyter_Notebooks/1.Data_Exploration/Data_Exploration.ipynb) -- Exploring our data and determining LTV Range. 
 - [Data Wrangling](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/Jupyter_Notebooks/2.Data_Wrangling/Data_Wrangling.ipynb) -- Reshaping original raw export to get a cleaned customer LTV table. 
 - [Exploratory Data Analysis](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/Jupyter_Notebooks/3.Exploratory_Data_Analysis/EDA.ipynb) -- Exploring which variables correlate with target LTV and Repeat Customer variables. 
 - [Modelling](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/tree/main/Jupyter_Notebooks/4.Modelling)
    1.   _Regression Models_: Use of 2 different models to predict post first week spend.
    2.   _Classsification Models_: Use of 4 different models to predict post first week repeat orders.

 **III. Supporting Documentation**
 - [Final Report](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/Report_Presentation/Shopify_Report.pdf) -- Report detailing steps undertaken and key findings. 
 - [Presentation](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/Report_Presentation/Shopify_LTV_Repeat_Presentation.pdf) -- Presentation on project purpose, steps undertaken and results
 - [Metrics File](https://github.com/benjaminbellman/Shopify_CLTV_Machine_Learning/blob/main/Report_Presentation/Metrics.xlsx) -- Excel file with model outputs and metric evaluation. 
 
## Acknowledgments 
Special thank you to: 

- Ben Bell
- Lou Graniou
- David Belgrod

## Contributing

Contributions are always welcome! 

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.