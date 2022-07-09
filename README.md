# BC2406 Project
 
A report on how the renewable energy could be useful in predicting/improving GDP and growth

Studies on Environmental Factors:
This report studies environmental factors, primarily renewable energy, and their relationship with two variables – GDP per capita, and GDP per capita growth, over a period of 28 years (1991 to 2018). Due to the presence of many strong outliers for GDP per capita growth, the relationship was studied by converting it into a categorical variable (Acceptable growth).

Linear Regression and Continuous CART Model (GDP per capita):
The study was conducted using Linear regression and continuous CART models. We tested different models and explored how the results varied across different datasets (Splitting by economy type). Upon many comparisons, we have found that continuous CART was the better model of the two for all datasets (Lower RMSE). Using CART, the results are shown below:
Renewable Energy Consumption and Population Growth are found to be the two most significant variables for predicting GDP per capita for all datasets. Moreover, environmental variables generally have high importance with CO2 emissions being top 4. It was also observed that CO2 emissions had a negative weight for developed countries
Upon further studying the variable importance of Renewable electricity output and Renewable energy consumption over three time periods (1991-1999, 2000-2008, 2009-2018) we observed:
Overall dataset: Renewable electricity output’s importance increased over the years.
Developed Countries dataset: Renewable energy consumption’s importance increased 
Developing Countries dataset: Both variables’ importance remained constant.
Hence, Renewable energy consumption is a strong predictor for the GDP per capita of a country, and its importance in the developed countries model will likely increase over time.
Logistic Regression, Categorical CART Model (Acceptable growth):
The study was conducted using Logistic regression and categorical CART models. Just like above, we compared the models and found that CART has a better prediction accuracy for all datasets except for developing countries. Using CART and logistic models, the results are:
CART:
In general, environmental variables are strong predictors of Acceptable growth for all datasets with CO2 emissions being a relatively strong predictor.
Overall dataset: Population total and nitrous oxide emissions are the two most significant variables. Moreover, both renewable energy variables are good predictors.
Developed Countries dataset: Population total and CO2 emissions are the two most significant variables. 
Just like above, we studied the trend of the two renewable variables over three time periods:
Overall dataset: Renewable electricity output’s variable importance increases over time.
Developed Countries dataset: Renewable energy consumption’s importance increased over time.
Logistic Regression (Developing countries dataset): 
CO2 emissions and greenhouse gases are good predictors of Acceptable growth. Other environmental variables are also close to statistical significance. Moreover, Renewable energy consumption’s variable importance and strength as a predictor increases over time.
Hence, from the two models, we can conclude that both renewable energy variables are strong predictors for Acceptable growth for the overall dataset model. Moreover, renewable energy 
consumption’s strength as a predictor increases over time.


# Appendix:
## Some EDA:
![image](https://user-images.githubusercontent.com/44868878/178106155-c437fe3b-03e3-468c-8f7b-4288b28b3d6e.png)
![image](https://user-images.githubusercontent.com/44868878/178106164-de27bd22-67ec-445e-9828-4a43ceacdd79.png)

## Model Diagnostics:
![image](https://user-images.githubusercontent.com/44868878/178106173-cc01ef50-ce53-4aac-ad5b-f22be05ed651.png)
![image](https://user-images.githubusercontent.com/44868878/178106176-f30fb9de-02c6-4210-9cad-f8105bbd1a83.png)

## CART Pruned tree
![image](https://user-images.githubusercontent.com/44868878/178106191-b83c2971-747b-4ba4-a0ac-b8bcd60c65b0.png)

## FULL REPORT CAN BE FOUND IN PDF

