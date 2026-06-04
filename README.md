# Accenture Stock History
This project involves analysing Accenture’s stock history data [Accenture-Share Price center](https://investor.accenture.com/stock-information/share-price-center).
## Step by Step
- **Collect Data** -- Find the data/spreadsheet to be analysed
    Data link [Accenture_stock_history](https://github.com/ahmadfurqan7/Accenture_stock_history_Analysis_Data/blob/main/Accenture_stock_history%20(raw).xlsx).
- **Data cleaning** -- Correct and remove unnecessary data; for example, if we only need data from the last two years, delete the previous years.
- **Data forecasting** -- Create a forecast for future open prices using a excel formula.

Forecasting formula for `open/high/low/close/volume` price values.
```bash
=FORECAST(x, known_ys, known_xs)
```

| Formula | Note |
|-----|----------|
| `x` | The date of the value to be searched (lock) |
| `known_ys` | All values from the previous `open/high/low/close/volume` values |
| `known_xs` | All dates from the previous values (lock) |

- **Exploratory Data** -- Creating charts to visualise the results of the forecasting
Drawing a trend line to indicate the general direction or trend of the data movement. This line serves to visualise whether the data is rising, falling, or flat.

Assessing accuracy using the R-squared value of the trend line.

![Forecasting Chart](https://github.com/ahmadfurqan7/Accenture_stock_history_Analysis_Data/blob/main/Accenture_stock_history.jpg)

- **Data Visualization** -- creating charts from data to present findings and insights.

Creating a bar chart showing the correlation between annual trading volume using Power BI software
![Forecasting Chart]()

Creating a dashboard chart showing the correlation between the `open`, `high`, `low`, and `close` prices for each year using Power BI software
As well as calculating statistical values such as the average.
![Forecasting Chart]()

From the data visualizations created, we can generate a report showing the highest and lowest values for annual volume
As well as identifying the highest and lowest prices for `open`, `high`, `low`, and `close` each year.


## License

[LICENSE](LICENSE)
```
  _    _ _  ______  _   _ 
 | |  | | |/ / __ \| \ | |
 | |  | | ' / |  | |  \| |
 | |  | |  <| |  | | . ` |
 | |__| | . \ |__| | |\  |
  \____/|_|\_\____/|_| \_|                
```
