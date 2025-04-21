# DATA_ANALYST_INTERN

The sales_data.csv dataset was loaded and explored using pandas. Initial inspection showed no missing values, but approximately 1000 duplicate rows were found, mainly differing by the Year column.
I have done a good insight from this by finding a how much profit each product making in each year and on an avaerage how many units of each product are being ordered
Categorical columns like Country and Product_Category were cleaned by stripping whitespace and applying title case formatting.
Skewness was assessed using df.skew(), revealing high skew in features such as Profit, Cost, and Revenue. 
Outliers were identified in the numeric columns (Unit_Cost, Unit_Price, Profit, Cost, and Revenue) using the IQR method and were capped to their respective upper and lower bounds to reduce distortion in the data.
After these preprocessing steps, the dataset is now clean, consistent, and ready for further analysis or modeling.

