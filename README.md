# Data Science Capstone Project IBM - SpaceX Falcon 9 Landing Predictions


## Project Overview

This project aims to forecast the likelihood of a successful landing of the Falcon 9's first stage. SpaceX offers rocket launches for $62 million, a significantly lower price compared to competitors who charge upwards of $165 million per launch. This cost reduction is largely due to SpaceX's ability to reuse the Falcon 9’s first stage. By accurately predicting landing success, we can estimate launch costs, which could be valuable information for companies looking to bid against SpaceX for rocket launches.

## Business Problem

The cost savings from SpaceX’s reusable first stage are crucial. Therefore, predicting the success of the first stage landing plays a key role in determining the launch costs. By utilizing data science techniques, we aim to understand which factors influence the landing outcome, allowing companies to compete with SpaceX more effectively.

## Approach

1. **Data Collection**
   - Historical SpaceX launch data was retrieved using their public API.
   - Additional information was obtained through web scraping (link to source here).

2. **Data Wrangling**
   - The collected data was cleaned and transformed to ensure it was ready for analysis.

3. **Exploratory Data Analysis (EDA)**
   - EDA was conducted using SQL queries and visualized with Python libraries.

4. **Data Analytics**
   - Interactive maps and dashboards were created with tools like Folium and Plotly.

5. **Predictive Modeling**
   - Machine Learning algorithms were used to predict the likelihood of a successful landing based on various features.

## Dependencies

### Libraries for Data Collection:
- `requests`
- `BeautifulSoup`

### Libraries for Data Wrangling:
- `pandas`
- `numpy`
- `SQLAlchemy`

### Libraries for Visualization:
- `matplotlib`
- `seaborn`
- `folium`
- `plotly`
- `dash`

### Libraries for Machine Learning:
- `scikit-learn`

## Project Deliverables

1. **Comprehensive Business Report** - A PowerPoint presentation summarizing the findings and recommendations.
2. **Jupyter Notebooks** - These contain the code and results of the analysis, along with visualizations.

## Key Insights

The analysis revealed that the most important factors influencing the success of a Falcon 9 first stage landing include (but are not limited to):

- **Payload Mass**
- **Orbit Type**
- **Booster Version**
- **Launch Site**

These factors were found to have a significant impact on predicting the landing success of Falcon 9 rockets.

## Conclusion

This project applied data science and machine learning to predict whether SpaceX's Falcon 9 first stage would land successfully. Accurate predictions of landing success can lead to better cost estimations for SpaceX launches. Further improvements can be made by refining the models and adding more relevant features to enhance prediction accuracy.

---
