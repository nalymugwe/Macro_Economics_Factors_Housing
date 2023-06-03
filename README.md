# Macro_Economics_Factors_Housing
An EDA of macro economic factors that would influence the performance of the real estate industry in Kenya
Macroeconomic factors are broad economic indicators that influence the overall health and performance of a country's economy. Exploratory Data Analysis (EDA) of macroeconomic factors can help with real estate analysis in several ways:
- Identify Trends: EDA can reveal long-term trends in macroeconomic factors, such as GDP growth or inflation. Understanding these trends can provide insights into the overall economic conditions and the potential impact on real estate markets.
- Understand Relationships: EDA can help identify correlations or relationships between macroeconomic factors and real estate indicators, such as housing prices or housing demand. This can assist in understanding how changes in macroeconomic variables influence the real estate market.
- Forecast and Predictive Analysis: By analyzing historical data and trends, EDA can help build predictive models to forecast real estate market performance based on macroeconomic factors. These models can aid in making informed investment decisions or assessing market risks.
- Risk Assessment: EDA can assist in assessing the risk associated with real estate investments by analyzing macroeconomic factors. Understanding how factors impact the real estate market can help in evaluating investment opportunities and potential risks.


### **Notes from Trend Analysis**
- The commercial bank weighted average rates i.e savings rate, lending rate, deposit rate and savings rate are all moving in the same trend with overdraft and lending rates being the highest followed by deposit rate and lasty savings rate. The highest commercial bank rates were recorded between 1994 and 1999. This was probably influenced by an economic crisis where the World Bank withheld aid until the then President (The Late Moi) agreed to economic reforms. Additionally there was political unrest following the re-election of the Late Moi.
-Diaspora remittances have had an upward trend through the years where North America has dominated with the highest value in remittances followed closely by Europe. However since 2020, the value of Europe has dropped and has been overtaken by the Rest of the World. This could mean that either the diasporians are no longer immigrating to Europe or they have withdrawn from sending money to Kenya.
- Central Bank rate are quite volatile with no trend. These rates include repo rate, reverse repo rate, interbank rate and cash reserve requirement Rate.
- The highest government debt is from external debt followed closely by treasury bonds which have both been on an upward trend through the years. The value of treasury bills has been on a downward trend since 2019.
- Nairobi low income earners are the hardest hit as they have the highest rate of inflation followed by the middle income earners. Between 2019 and 2020, the Nairobi high income earners were hit the hardest by inflation rate. This could have been influenced by the olitical uncertainity from the handshake between the former Kenyan president, Uhuru Kenyatta and Raila Odinga and also the bombing in one of Nairobi's plush areas i.e. Dusit D2.
- The consumer price index has been on an upward trend over the years compared to the inflation rate that has experienced a schostatic trend as the values seem to go down for a while then pick up for awhile.
- The real estate growth is synonymous with the annual GDP growth.


### **Notes from Univariate Analysis**
Univariate analysis i.e. the use of histograms and boxplots, plays a crucial role in understanding data distributions, detecting outliers and summarizing data characteristics to provide insights into individual variables. From the univariate analysis done, the following insights were extracted: 
- None of the variables is normally distributed.
- The cash reserve requirement rate variable is the only variable in the dataset whose values are skewed to the left. This means that a majority of these values are concentrated towards the smaller values and the mean is less than the median. 
- The rest of the variables have their values skewed to the right meaning that a majority of the values are concentrated towards the larger values and the mean is greater than the median.
- Variables without outliers are the consumer price index, central bank rate and cash reserve requirement rate. The presence of outliers in the other variables could be influenced by uncertain economic conditions.


### **Findings of Correlation Analysis**

Correlation analysis is an important statistical technique that helps us understand the linear relationship between variables. It allows us to determine whether there is a relationship between variables and the nature of that relationship. 
- The heatmap analysis gives an overview of the linear relatiosnhip between the variables where the boxes in blue show a negative linear relationship between the variables and the boxes in red show a positive linear relationship. Values that are equal to 1 show a perfect correlation, values between 0.8(+/-) and 1 (+/-) show a very high correlation, values between 0.6(+/-) and 0.4 (+/-) have a strong correlation, values between 0.4(+/-) and 0.2 (+/-) have a moderate correlation, values between 0.2(+/-) and 0 (+/-) have a weak correlation and values that are zero have no correlation.
- Further analysis of the correlation analysis with real estate growth as the dependent variable revealed that the nominal annual GDP had the strongest positive correlation whereas government stock had the weakest negative correlation. 


### **Findings from Regression Analysis**
The regression analysis results include coefficients for the various macro economic factors that may impact real estate growth. Here is a summary of the findings and their potential implications for real estate:

Factors associated with positive real estate growth:
- Cash Reserve Requirement Rate: An increase in this rate is associated with an increase in real estate growth, suggesting that higher cash reserves may positively impact real estate growth.
- North America and Europe Diaspora Remittances: Higher remittances from North America can positively impact real estate growth. Increased remittances can provide additional capital for real estate investments and contribute to the overall growth of the sector.
- Not Allocated: An increase in not allocated funds is associated with an increase in real estate growth, however this variable is no longer in use as remittances are now grouped into North America, Europe and the Rest of the World.
- Commercial Banks Weighted Average Deposit Rate: Higher deposit rates are associated with an increase in real estate growth, implying that favorable deposit rates may incentivize individuals to deposit more increasing the availability of funds to stimulate real estate growth.
- Treasury Bills and Treasury bonds: An increase in the value of treasury bills and bonds indicates a higher demand for government debt, which can indirectly contribute to real estate growth by influencing interest rates and market liquidity.
- Overdraft at Central Bank: The availability of overdrafts at the central bank can provide liquidity to commercial banks, which in turn can support lending for real estate projects and positively impact real estate growth.
- Other Domestic Debt: Increased levels of other domestic debt indicate higher borrowing activities, which can lead to increased investment in real estate projects and positively affect real estate growth.
- Nairobi Upper/Middle/Lower Income Inflation Rate: Higher inflation rates in different income categories in Nairobi can potentially indicate increased economic activity and demand, which can positively influence real estate growth in those specific income segments. For example, higher inflation in lower-income areas (Nairobi Lower Income Inflation Rate) is associated with increased real estate growth, while inflation in other regions (Rest of Kenya Inflation Rate) shows a negative relationship with real estate growth.
- Nominal Annual GDP Growth: An increase in the nominal annual GDP growth will positively impact the real estate growth.

Factors associated with negative real estate growth:
- Repo Rate: A higher repo rate set by the central bank can increase borrowing costs for banks, potentially leading to reduced lending and investment in real estate, thus negatively impacting real estate growth.
- Reverse Repo Rate: An increase in the reverse repo rate can encourage banks to hold more funds with the central bank, which can restrict liquidity and reduce available capital for real estate investment, negatively affecting real estate growth.
- Interbank Rate: A higher interbank rate can increase borrowing costs for banks and limit their ability to provide loans for real estate projects, potentially resulting in a negative impact on real estate growth.
- Central Bank Rate: A higher central bank rate can increase borrowing costs for banks and borrowers, which can hinder real estate investment and negatively impact real estate growth.
- Rest of World Diaspora Remittances: Remittances from the rest of the world, with a negative coefficient, may not have a significant positive impact on real estate growth, possibly due to factors such as lower remittance volumes or investment patterns.
- Commercial Banks Weighted Average Savings Rate: A higher savings rate offered by commercial banks can encourage individuals and businesses to save more, potentially reducing the available capital for real estate investment and negatively affecting real estate growth.
- Commercial Banks Weighted Average Lending Rate: A higher lending rate offered by commercial banks can increase borrowing costs for individuals and businesses, leading to reduced demand for real estate loans and negatively impacting real estate growth.
- Advances from Commercial Banks: Reduced levels of advances from commercial banks indicate a higher chance in the growth of real estate.
- Consumer Price Index (CPI): The negative coefficient for the consumer price index suggests that a higher CPI, which measures the cost of living, may have a negative influence on real estate growth. This could be due to increased living costs affecting affordability and demand for real estate.
- Annual GDP Rate: The negative coefficient for the annual GDP rate indicates that higher GDP growth rates may have a negative impact on real estate growth. This might suggest that other sectors of the economy are growing faster than the real estate sector.
- External Debt: The negative coefficient for external debt suggests that higher levels of external debt may have a negative impact on real estate growth. This could be due to factors such as increased financial vulnerability or limitations on investment capacity.
- Average Annual Inflation Rate: A higher average annual inflation rate has a negative coefficient, indicating that higher inflation levels on average may have a dampening effect on real estate growth.
- Government Stocks: The negative coefficient for government stocks suggests that higher levels may have a negative impact on real estate growth.


### **Notes from Predictive Analysis**

6 regression models were selected to determine the suitable regression model from the performance metrics. The regression models used and their performance metrics are seen in the table input above. 

The discussion of results is as below:
- R-squared represents the proportion of the variance in the dependent variable that is predictable from the independent variables. It ranges from 0 to 1, where 1 indicates a perfect fit. In this case, the Gradient Boost Regression model has the highest R-squared value of 0.999205, indicating an excellent fit to the data. This suggests that the Gradient Boost Regression model explains 99.92% of the variance in the dependent variable.
- Mean Squared Error measures the average squared difference between the predicted values and the actual values. It provides an overall measure of the model's performance, with lower values indicating better accuracy. The Gradient Boost Regression model has the lowest MSE of 2.369672e+07 (23,696,720), suggesting that it has the smallest average squared difference between the predicted and actual values among all the models.
- Root Mean Squared Error is the square root of the MSE and is expressed in the same units as the dependent variable. It represents the standard deviation of the residuals, providing a more interpretable measure of the model's accuracy. The Gradient Boost Regression model has the lowest RMSE of 4867.93, indicating the smallest average prediction error in the original units of the dependent variable.

Based on these metrics, the Gradient Boost Regression model performs exceptionally well with a high R-squared value and lowest MSE and RMSE values. 
