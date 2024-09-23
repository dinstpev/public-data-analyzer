# public-data-analyzer

"Public data that remain unused by the majority cannot truly be considered public."

This project was implemented as part of my master's thesis in the program "Master in Information Systems (PLS)" at the Hellenic Open University (HOU).

Design of a system for analysis, prediction and classification of extracted public data using machine learning algorithms.

Abstract

The problem posed within the context of increasing the volume of public data is that of maximizing its effective utilization, with the aim of extracting knowledge through statistical methods and machine learning techniques.
To this purpose, a system for extracting and analyzing public data was developed.
The system is implemented in three areas: data extraction, data integration and cleaning, and finally, data analysis.

Data was collected from official sources such as the European Central Bank (ECB), Eurostat (ESTAT), the World Health Organization (WHO), Google, YouTube, and the financial service Alpha Vantage. Specifically, data was extracted for key socio-economic indicators such as €STER interest rate indices, BS consumer confidence indices, CISS systemic risk indices, unemployment, debt, inflation, GDP change, Covid-19 cases and deaths, USD/EUR and CNY/EUR exchange rates, prices of major commodities like oil, natural gas, corn, and wheat, search interest trends on Google, and production trends of audiovisual material on YouTube regarding significant events like the Russia-Ukraine war, the Israel-Gaza conflict, climate change, economic crises, and the Covid-19 pandemic. The area of interest for data selection is the Eurozone.

The time period analyzed in the implementation of the system spans from 2020 to June 30, 2024.

All stages and processes of extraction, integration, and analysis are described in detail. The final stage is carried out through the procedures of Exploratory Data Analysis (EDA) using Data Visualization techniques, including time series charts, density histograms, and boxplots. This culminates in the process of Correlation Analysis using Correlation Matrices and presentation with Heat Maps to identify strong linear correlations and visualize them with scatter plots and additional heat maps, grouping them accordingly.

Finally, analyses are conducted and evaliuated using statistical methods and machine learning algorithms such as Linear Regression, Random Forest, Gradient Boosting, and Logistic Regression for Hypothesis Testing and Classification Analysis. Additionally, machine learning algorithms such as k-Means and Agglomerative Clustering are implemented for the Clustering process.

The focus is on how all the aforementioned variables are combined through appropriate checks, so that their values can be used to train statistical and machine learning models with the aim of either extracting knowledge or using them for predictions and strategic planning.
