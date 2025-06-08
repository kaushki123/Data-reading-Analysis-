# Data-reading-Analysis-

COVID-19 Data Analysis and Visualization Project

This project focused on analyzing a global COVID-19 dataset with 321 entries and five key columns: Date, Region, Confirmed, Deaths, and Recovered cases. The goal was to clean, process, and visualize the pandemic's impact across various regions.

The dataset was loaded using Pandas, and the Date column was converted to datetime format. Due to over 56% missing data, the State column was dropped. Checks confirmed no nulls or duplicate entries in the remaining data.  make short only for minor intro

Exploratory Data Analysis (EDA) was conducted on the numerical features using correlation matrices and heatmaps. A strong correlation (0.90) was found between Confirmed cases and Deaths, highlighting severe regional impacts.

Visualizations were generated to understand regional trends. Matplotlib was used to create bar charts of top regions for Confirmed, Deaths, and Recovered cases, with the US, Spain, Italy, and France among the most affected. Plotly was used for an interactive grouped bar chart showcasing the top 10 regions by case type.

This project demonstrated proficiency in Python libraries such as Pandas, NumPy, Seaborn, Matplotlib, and Plotly. It emphasized the importance of clean data, effective visualization, and statistical insight in public health analysis.
