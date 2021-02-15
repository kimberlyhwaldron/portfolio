Kimberly Healy Data Portfolio  |  healy.kim@gmx.us     
  
## [Project 1 (click here)](https://kimberlyahealy.github.io/TimeSeries_OnlineRetailData/)

### [Time Series Predictive Modeling <br> Online Retail Data](https://kimberlyahealy.github.io/TimeSeries_OnlineRetailData/)

> The data ([OnlineRetail.csv](https://archive.ics.uci.edu/ml/datasets/Online+Retail)) come from all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail store. The company sells unique gifts and the majority of customers are wholesalers. This report will use techniques to explore the data and use three different time series algorithms to model sales. The conclusion states which model(s) best predict sales and recommendations for further analysis.     
>        
> The following predictive models are used:        
>  - **Model 1: Simple Moving Average**: a weighted average function that identifies the previous pattern in the data and uses that pattern to predict future data points.      
>  - **Model 2: Exponential Smoothing**: similar to Simple Moving Average, but contains a smoothing constant which can be tweaked for more responsive or more stable models.      
>  - **Model 3: Autoregressive Integrated Moving Average (ARIMA)**: unlilke the previous models, ARIMA considers the correlations among the previous values of the time series to predict future values.    
>         
>          
> The following question is answered:     
>  - **Which time series model best predicts company sales?**

***
## [Project 2 (click here)](https://kimberlyahealy.github.io/Regression_2018SalesData/) 

### [Linear Regression Predictive Modeling <br> 2018 Customer Data](https://kimberlyahealy.github.io/Regression_2018SalesData/)

> The data (customer_data_2018.csv) come from the 2018 sales of a small wholesale business. 
>   
>   
> The following models are used:        
>   - **Simple Linear Regression**: a model that estimates the relationship between two continuous variables (one dependent and one independent) by fitting a linear equation to observed data.       
>   - **Multiple Linear Regression**: a model that estimates the relationship between one dependent and two or more independent continuous variables by fitting a linear equation to observed data.      
>          
> The following question is answered:     
>   - **Which regression model best predicts company sales?**


## [Project 3 (click here)](https://kimberlyahealy.github.io/Trends_DigitalMediaAdCampaign/)

### [Performance Analysis, Trends & Recommendations <br> Digital Media Ad Campaign Data](https://kimberlyahealy.github.io/Trends_DigitalMediaAdCampaign/)

> The data (DigitalMediaCampaign.xlsx) come from a digital campaign that included banners, digital video, and rich media advertisements. This report provides insight into the campaign performance.     
>       
> The following KPIs are investigated:    
>  - **Clicks**: The number of times the ad is clicked     
>  - **Click-Thru-Rate**: The rate which impressions drive clicks (Clicks / Impressions)   
>  - **Completion Rate**: The rate which video impressions are viewed (Completes / Impressions)    
>  - **Engagement Rate**: The rate which rich media is engaged with (Interactions / Impressions)       
>          
>          
> The following questions are answered:     
>   - **How does the performance of the ads differ by Site, Device, or Creative Name?** (PARTS V-VII)       
>   - **Are there any trends in KPI performance over time?** (PART VIII)       
>   - **What recommendations would you make? What other KPIs would you consider?** (PART IX)     


## **[Project 4 (click here)](https://kimberlyahealy.github.io/DataMiningKNIME_CurriculumRedesign/)**

### [Data Mining Methods <br> For Curriculum Redesign](https://kimberlyahealy.github.io/DataMiningKNIME_CurriculumRedesign/)


> **Data**: Courses.doc, Enrollment.csv   
> **Tools Used**: KNIME Analytics, Excel   
> **Techniques Used**: String distance, clustering, association rules for classification, frequent pattern
matching   
>  
>  
> **Workflow example 1: string distances & clustering   
> Fix misspelling of course names in dataset.**   
>![KNIME workflow1](https://github.com/kimberlyahealy/DataMiningKNIME_CurriculumRedesign/blob/main/KNIME1.png?raw=true)
>  
>  
> **Workflow example 2: association rule mining  
> Find elective courses that are associated with the top 3 most frequently taken elective courses.**  
>![KNIME workflow2](https://github.com/kimberlyahealy/DataMiningKNIME_CurriculumRedesign/blob/main/KNIME2.png?raw=true)
>  
>  
> **Workflow example 3: frequent pattern matching  
> Group together elective courses frequently taken together using frequent pattern matching.**  
>![KNIME workflow3](https://github.com/kimberlyahealy/DataMiningKNIME_CurriculumRedesign/blob/main/KNIME3.png?raw=true)





## **[Project 5 (click here)](https://kimberlyahealy.github.io/TableauDashboard_GlobalTerrorData/)**

### [Tableau Dashboards <br> Global Terrorism Data](https://kimberlyahealy.github.io/TableauDashboard_GlobalTerrorData/)


> **Data**: [Global Terrorism Database](https://www.kaggle.com/START-UMD/gtd)   
> **Tools Used**: Tableau, Dashboards   
> **Techniques Used**: Static dashboard to visualize descriptive statistics (charts, tree map, text table); Exploratory dashboard to visualize trends (interactive map and interactive trend line)   
>  
>  
> **Dashboard example 1**: Explanatory Dashboard   
>![TABLEAU dashboard1](https://github.com/kimberlyahealy/TableauDashboard_GlobalTerrorData/blob/main/TABLEAU1.png?raw=true)
>  
>  
> **Dashboard example 2**: Exploratory Dashboard   
>![TABLEAU dashboard2](https://github.com/kimberlyahealy/TableauDashboard_GlobalTerrorData/blob/main/TABLEAU2.png?raw=true)
>  
>  
> **Dashboard example 3**: Bonus   
> ![TABLEAU dashboard3](https://github.com/kimberlyahealy/TableauDashboard_GlobalTerrorData/blob/main/TABLEAU3.png?raw=true)





## **[Project 6 (click here)](https://kimberlyahealy.github.io/Classification_WineQuality/)**

### [Classification Models <br> Wine Quality Data](https://kimberlyahealy.github.io/Classification_WineQuality/)

> The data ([WineQuality.csv](https://archive.ics.uci.edu/ml/datasets/wine+quality)) includes the results of physicochemical and sensory tests for different types of wine. The attributes from the physicochemical tests include: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, wine type. The attribute from the sensory test includes: quality, a score between 0 and 10.   
>     
> The purpose of this investigation is to find the optimal classification model to predict wine quality.  
> 
>
> The following predictive models are used for a categorical output:        
>   - **Model 1: Ordered Logistic Regression**: A regression model with an ordinal dependent variable.   
>   - **Model 2: CART (tree)**: Classification & regression tree that takes a either categorical or continuous response variable. At an inner node, it allows a binary split.    
>   - **Model 3: C5.0 (tree)**: Classification tree that takes only a categorical response variable. At an inner node, it allows a multiple split. Each node is split using the best split by the Gini Index among all input variables.   
>   - **Model 4: Random Forest (tree)**: Combines multiple models (i.e. hundreds of decision trees) into a single ensemble. Each decision tree is independent from another tree. Each node is split using the best split among a random subset of all input predictor variables chosen at the node.   
> 
>                  
> The following questions are answered:     
>   - **Which attributes best predict wine quality?**   
>   - **Which model(s) best predicts wine quality?**  




## **[Project 7 (click here)](https://kimberlyahealy.github.io/RelationalDatabase_SQL/)**  

### [Relational DB Specification <br> & SQL Queries](https://kimberlyahealy.github.io/RelationalDatabase_SQL/)  

> **Data**: Inputted using SQL  
> **Tools Used**: Oracle SQL  
> **Techniques Used**: Relational database design (define purpose, ERD, tables schemas, keys, normalization, etc.); SQL to create, alter, and populate tables, manipulate data, query/retrieve data; Relational algebra query   
>
>
> **DB/SQL example 1**: ERD  
>![SQL1](https://github.com/kimberlyahealy/RelationalDatabase_SQL/blob/main/SQL1.png?raw=true)
>  
>
> **DB/SQL example 2**: Tables Schema  
>![SQL1](https://github.com/kimberlyahealy/RelationalDatabase_SQL/blob/main/SQL2.png?raw=true)
>  
> 
> **DB/SQL example 3**: SQL Query  
>![SQL1](https://github.com/kimberlyahealy/RelationalDatabase_SQL/blob/main/SQL3.png?raw=true)
> 
> 
> **DB/SQL example 4**: SQL Query   
>![SQL1](https://github.com/kimberlyahealy/RelationalDatabase_SQL/blob/main/SQL4.png?raw=true)
>  
> 
> **DB/SQL example 5**: SQL Query  
>![SQL1](https://github.com/kimberlyahealy/RelationalDatabase_SQL/blob/main/SQL5.png?raw=true)






## **[Project 8 (click here)](https://books.google.com/books?id=atSBDwAAQBAJ&pg=PA83&lpg=PA83&dq=%22Data+Mining+Methods+for+Describing+Federal+Government+Career+Trajectories+and+Predicting+Employee+Separation%22&source=bl&ots=guHGUaM9iO&sig=ACfU3U2PXpdn_rW1aDQeQKNZAeCXzrHKGA&hl=en&sa=X&ved=2ahUKEwjqhJqPsuruAhWMQc0KHRFXAuIQ6AEwB3oECAYQAg#v=onepage&q=%22Data%20Mining%20Methods%20for%20Describing%20Federal%20Government%20Career%20Trajectories%20and%20Predicting%20Employee%20Separation%22&f=false)**  
### [Data Mining Methods for Describing Federal Government Career Trajectories <br> and Predicting Employee Separation](https://books.google.com/books?id=atSBDwAAQBAJ&pg=PA83&lpg=PA83&dq=%22Data+Mining+Methods+for+Describing+Federal+Government+Career+Trajectories+and+Predicting+Employee+Separation%22&source=bl&ots=guHGUaM9iO&sig=ACfU3U2PXpdn_rW1aDQeQKNZAeCXzrHKGA&hl=en&sa=X&ved=2ahUKEwjqhJqPsuruAhWMQc0KHRFXAuIQ6AEwB3oECAYQAg#v=onepage&q=%22Data%20Mining%20Methods%20for%20Describing%20Federal%20Government%20Career%20Trajectories%20and%20Predicting%20Employee%20Separation%22&f=false)  

Healy Kimberly, Lucas Dan, Miller Cherilyn. (2019) Data Mining Methods for Describing Federal Government Career Trajectories and Predicting Employee Separation. In: Yang H., Qiu R. (eds) Advances in Service Science. INFORMS-CSS 2018. Springer Proceedings in Business and Economics. Springer, Cham. [https://doi.org/10.1007/978-3-030-04726-9_9](https://doi.org/10.1007/978-3-030-04726-9_9)
    
> **Abstract**   
> Data mining methods can be applied to human resources datasets to discover insights into how employees manage their careers. We examine two elements of career trajectories in federal government HR data. First, we apply **association rule mining** and **sequential pattern mining** to understand the prevalence and direction of interdepartmental transfers. Then we apply **logistic regression** and **decision tree induction** to understand and predict employee separation. In this specific application, we find that interdepartmental transfers are uncommon, except between branches of the armed services and out of these branches to the Department of Defence. We also find that demographics, compensation, and political transitions are significant factors for retention, but they account for only a small portion of the probability of a federal employee leaving service. We expect these methods would perform better in industry with a small amount of additional data gathered upon hiring and exit interviews.

