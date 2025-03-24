CANADA’S HOUSING MARKET ANALYSIS & PREDICTION

Housing affordability has become an increasingly pressing concern in Canada, with significant implications for future homebuyers, policymakers, and the broader economy. Over the decades, rising housing prices have influenced accessibility to homeownership, shaping the financial futures of individuals and families alike. Understanding housing market trends is essential not only for everyday citizens and prospective homeowners but also for investors and policymakers aiming to create sustainable housing solutions. However, beyond analyzing past trends, the ability to predict future price fluctuations is critical for making informed decisions. Accurate forecasting can help prospective buyers determine the optimal time to purchase a home, assist policymakers in developing targeted housing policies, and enable financial institutions to anticipate market risks. This project seeks to analyze the evolution of housing price indexes in Canada from 1981 to 2023, providing a comprehensive exploration of historical trends while leveraging predictive modeling to assess future price movements and their broader economic implications.

Research Question
For my literature review, I am trying to determine the optimal timing for purchasing a home in Canada by analyzing economic factors and forecasting future prices using predictive modeling. Specifically, I want to learn how historical trends reveal patterns in housing market fluctuations and whether these trends can inform prospective buyers on the best time to enter the market.

My main research question is:
How do historical trends in key economic factors influence housing prices in Canada, and how can predictive modeling be used to forecast future price fluctuations to determine the best time to buy a home?

Methodology (Content in "Initial Results and Code" file) : 

1.	Data Collection
-	Data on economic factors explored  (available on the repository in csv files)
o	GDP
o	Unemployment rates 
o	Mortgages Rates 
-	Target variable:
o	NHPI  

2.	Data preprocessing 
-	Check for any missing values: Conduct a thorough examination of each dataset to identify and handle missing values by removing incomplete records.
-	Select only data for the national average: Filter the datasets to focus solely on national averages for GDP, unemployment, and mortgage rates, ensuring that regional variations do not skew the analysis.

3.	Exploratory Data analysis
-	Graph how variables correlate with NHPI: Create visualizations such as scatter plots and correlation matrices to illustrate the relationships between the New Housing Price Index (NHPI) and the selected economic factors, identifying any notable trends or patterns.
  
4.	Model selection for predictive analysis
- ARIMA Model
- Random Forest

6.	Performance Comparison
- Model Comparison: comparing the performance of ARIMAX and random forest predictive accuracy using metrics such as MAE and R squared 

7. Forecasting:
- Between ARIMAX and Random Forest which ever model has the better performance metric would be used to predict the outyear 
