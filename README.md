# Steel Industry Energy Consumption Analysis

## 🚀 Overview
This project aims to analyze the energy consumption patterns in the steel industry, focusing on various factors such as energy usage by different types of loads (light, medium, maximum), the impact of power factors (leading vs. lagging), CO2 emissions, and the comparison of energy usage across weekdays and weekends. The dataset was acquired from DAEWOO Steel Co. Ltd. in Gwangyang, South Korea.

The analysis includes several key insights related to energy consumption, reactive power loss, and CO2 emissions, along with the identification of trends across different months and days of the week.

## 📂 Files
- **Steel_industry_data.csv** – The dataset containing information on energy usage, power factors, CO2 emissions, and more.
- **Steel Industry Energy Consumption Analysis.Rmd** – R Markdown file containing the analysis, data cleaning, exploration, and visualizations.
- **Steel Industry Energy Consumption Analysis.pdf** – A detailed report summarizing the findings, including charts and visualizations.

## 📊 Key Insights
✔ **Energy consumption trends**: Weekdays generally show higher energy consumption compared to weekends.  
✔ **Load types**: The **Maximum Load** consumes the most energy, followed by **Medium Load** and **Light Load**.  
✔ **Reactive power loss**: Lagging and leading current reactive power are compared, highlighting the power factor differences across various loads.  
✔ **CO2 emissions**: Energy consumption is closely tied to CO2 emissions, with higher energy usage in hot months like August.  
✔ **Energy consumption by load type**: The maximum load uses the most energy, with significant consumption differences between weekdays and weekends.

## 🔧 Techniques Used:
1. **Data Cleaning**:
   - The dataset was cleaned by removing unnecessary columns and handling missing values.
   - **`mutate()`** was used to clean and transform the data, ensuring that numeric columns were properly formatted and empty strings were replaced with `NA`.

2. **Data Exploration**:
   - Descriptive statistics and summary functions were applied to explore the dataset's characteristics.
   - The **`sapply()`** function was used to check the data types and ensure the correct handling of numeric and character columns.

3. **Data Visualization**:
   - **Histograms**, **bar charts**, **treemaps**, and **line graphs** were created using **`ggplot2`** and **`treemapify`** to visualize trends in energy consumption, reactive power, and CO2 emissions.
   - Visualizations help to understand daily energy usage, compare energy consumption by load types, and assess the relationship between energy usage and power factors.

4. **Time Series Analysis**:
   - **`lubridate`** was used to extract months and analyze energy consumption trends over time.
   - **Line graphs** were created to show monthly energy consumption and CO2 emissions, revealing seasonal patterns.

## 📌 Tools Used
- **R** (for data analysis and visualization)
- **R Markdown** (for dynamic reports)
- **ggplot2** (for data visualization)
- **dplyr** (for data manipulation)
- **tidyr** (for data cleaning)
- **lubridate** (for working with dates)
- **treemapify** (for treemaps)

## 💡 Conclusion
This analysis provides insights into the energy consumption patterns in the steel industry, highlighting key factors like load type, power factors, CO2 emissions, and differences between weekdays and weekends. The findings can be used to optimize energy use and reduce environmental impact in the industry.

---

💡 **Feel free to fork this repo & explore further insights!** 🚀
