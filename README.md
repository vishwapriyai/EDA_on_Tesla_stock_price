# EDA_on_Tesla_stock_price

ABOUT THE DATA
Date: The date for which the stock price data is recorded.
Open: The opening price of TSLA stock on that day.
High: The highest price reached during the trading day.
Low: The lowest price reached during the trading day.
Close: The closing price of TSLA stock on that day.
Volume: The trading volume (number of shares traded) on that day.
Adj Close: The adjusted closing price, which accounts for dividends and stock splits
I download the data from kaggle("https://www.kaggle.com/code/serkanp/tesla-stock-price-prediction/input")

exploratory data analysis (EDA) tasks on the Tesla stock price data. Here's a summary of what I've done:

Data loading and basic examination:

Loaded the data from a CSV file.
Checked the first few rows of the dataset using .head() and the last few rows using .tail().
Checked the data types and non-null counts for each column using .info().
Checked for any missing values using .isnull().sum().
Examined unique values in each column using .nunique().

Data preprocessing:

Converted the 'Date' column to a datetime data type.
Sorted the data by date.

Data visualization:

Plotted a heatmap of correlation matrix between numeric features using seaborn's heatmap.
Plotted the closing price trend of Tesla stock over time.
Calculated and plotted the 20-day moving average of the closing price.
Analyzed seasonality and trends by plotting the monthly average closing price and performing seasonal decomposition.
Identified outliers using boxplot visualization and IQR method, then visualized the original and cleaned data.
Calculated and visualized daily returns of Tesla stock.
Explored event analysis by examining data around a specific event date.
Lastly, you installed the pygwalker library, which seems unrelated to the EDA process.

Overall, I've covered a wide range of analyses to gain insights into the Tesla stock price data.
