# Economic Trends Analysis

This project focuses on analyzing economic trends using time series data. Time series data provides valuable insights into various economic indicators such as GDP, inflation, unemployment rate, job vacancies, and population. These indicators are crucial for understanding the overall health and trend of an economy, making predictions, and identifying patterns.

## Dataset
The dataset used in this study covers a 22-year time period from 2001 to September 2022, with quarterly data. The dataset contains six columns: time, unemployment rate, GDP growth, inflation, job vacancies, and population. It initially had 86 rows, but after cleaning and removing missing values, it was reduced to 232 rows and 8 columns.

To understand the dataset, it's essential to define the key terms:

1. Unemployment rate: It measures the percentage of the labor force that is actively seeking employment but unable to find work. A high unemployment rate indicates a weak job market and vice versa.

2. GDP growth: Gross Domestic Product (GDP) measures the total value of goods and services produced in an economy. GDP growth refers to the percentage increase in GDP over a specific period, serving as an indicator of economic growth.

3. Inflation: Inflation represents the rate at which the overall price level of goods and services in an economy is increasing. It is usually expressed as an annual percentage increase and is closely monitored by central banks.

4. Job vacancies: Job vacancies refer to available positions in companies or organizations that are ready to be filled. The number of job vacancies is an indicator of labor market strength and demand for workers.

5. Population: Population refers to the total number of people living in a specific area, such as a city, country, or region. Population trends play a crucial role in various planning processes, including housing, education, and healthcare.

## Analysis
The project starts by examining the distribution of factors calculated using the Principal Component Analysis (PCA) function. A histogram visualization shows the concentration of factor values around 0, with a range of -4 to +4. Additionally, a time series graph displays the changes in the PCA factor values over time, identifying specific years with extreme values.

Further analysis involves evaluating a linear model to predict the values of the PCA factor during different phases of the US economy, specifically expansion and recession. The model utilizes a set of variables including 'INDPRO', 'S&P 500', 'PAYEMS', 'CPIAUCSL', and 'BUSINVx'. The comparison between predicted and actual values reveals the model's performance for each variable, highlighting variations between expansion and recession periods.

## Future Steps
In the future, the project aims to explore additional variables beyond the initial set of five to identify stronger correlations with the PCA factor. Moreover, the evaluation of various machine learning algorithms will be conducted to improve prediction accuracy. Increasing the dataset length is also recommended to enhance the training of neural networks, which may yield more reliable results.

## Conclusion
The Economic Trends Analysis project employs time series data to analyze and understand economic indicators such as GDP, inflation, unemployment rate, job vacancies, and population. By evaluating these indicators over time, patterns and trends can be identified, enabling informed decision-making and future planning for governments, businesses, and organizations.

Please refer to the project code and analysis results for more detailed information and implementation details.

If you have any questions or require further clarification, please feel free to reach out.

Thank you for your interest in this project!
