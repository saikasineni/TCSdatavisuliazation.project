# TCSdatavisuliazation.project
This project aims to provide a comprehensive dashboard for analyzing Tata Consultancy Services (TCS) stock data using Power BI. The dashboard includes various visualizations such as cards, stacked column charts, stacked bar charts, line charts, and tables to explore key insights into TCS stock performance over time.
# TCS Dashboard Project

This project aims to provide a comprehensive dashboard for analyzing Tata Consultancy Services (TCS) stock data using Power BI. The dashboard includes various visualizations such as cards, stacked column charts, stacked bar charts, line charts, and tables to explore key insights into TCS stock performance over time.

## Preview

![TCS Dashboard Preview](Screenshot%20(153).png)
![TCS Dashboard Preview](Screenshot%20(154).png)

## Key Features

- **Cards**: Provides real-time updates on Tata Open, Close, High, and Low prices.
- **Stacked Column Chart & Stacked Bar Chart**: Visualize market summary of Tata Consultancy Services.
- **Line Chart**: Analyze TCS stock trends by Day, Quarter, Month, and Year.
- **Table**: Detailed breakdown of stock data including Year, Quarter, Month, Day, Open Price, High Price, Close Price, and Low Price.

## How to Use

1. Clone this repository to your local machine.
2. Open the PBIX file in Power BI Desktop to explore the dashboard.
3. Customize the dashboard according to your requirements.
4. Analyze and derive insights from the visualizations.

## DAX Measures

Here are the DAX measures used in this project:

- `Day = DAY('TCS NS'[Date])`
- `Month = MONTH('TCS NS'[Date])`
- `Quarter = QUARTER('TCS NS'[Date])`
- `Year = YEAR('TCS NS'[Date])`
