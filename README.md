# Analysis of Goals + Assists Against Expected Goals + Assists for the 24/25 Premier League Season

## Executive Summary, Documentation, Project Report, Impact Evaluation

In this project, I investigated the relationship between actual goals scored by footballers and assists compared to their expected goals (xG) and D expected assists (xA), which are key indicators in modern football analytics (Mackenzie, 2019; Spearman, 2018). The aim was to assess finishing efficiency and identify players who consistently outperform or underperform relative to their xG and xA. Using historical match data, this analysis provided actionable insights for coaches, analysts, and recruitment teams. The findings highlighted trends in player performance, shot quality, and decision-making, supporting data-driven strategies in professional football (Knotts et al., 2021; Sæther & Solberg, 2015).
The data source used was from Kaggle (Football Players Stats (2024–2025)) and featured player statistics from the 2024–2025 season across the top five European leagues, sourced from FBref (FBref, 2025; Kaggle, 2025). It contained metrics such as goals scored (G), expected goals (xG), assists (A), and expected assists (xA). I also created a custom metric: (G + A) − (xG + xA) to determine who overperformed and who underperformed (Mackenzie, 2019).
 
The tool used for this project was Power BI, chosen for its strong data visualisation capabilities and interactive reporting (Microsoft, 2025; Few, 2012). The approach included collecting the data, cleansing it, analysing it, creating visualisations, and interpreting the results. Expected Goals (xG) has revolutionised football analytics by quantifying shot quality; comparing goals vs xG reveals finishing ability beyond raw goal counts (Spearman, 2018; Mackenzie, 2019). Scatter plots showed the correlation between goals + assists and xG + xA. Efficiency rankings identified top overperformers and underperformers. Players exceeding xG + xA demonstrate elite finishing or tactical advantages, while underperformers may require coaching interventions (Knotts et al., 2021).
The insights from this project can help clubs make better recruitment decisions, optimise tactical strategies, and focus on player development (Sæther & Solberg, 2015; Knotts et al., 2021). Overperformers may be considered for key attacking roles, while underperformers could benefit from targeted coaching interventions. These findings reduce reliance on subjective assessments and promote evidence-based decision-making (Few, 2012; Hyndman & Athanasopoulos, 2018).

## Data Infrastructure & Tools

Power BI was selected as the primary tool for data visualisation and reporting because of its ability to integrate with multiple data sources, manage large datasets efficiently, and provide interactive dashboards (Microsoft, 2025; Few, 2012). Its compatibility with common data formats ensured smooth data ingestion and transformation. Power BI’s built-in analytics features, such as DAX, allowed for creating custom measures like differences and performance comparisons (Microsoft, 2025).

## Data Engineering

Data engineering was critical to ensure accuracy and reliability. The process involved data collection, cleaning, integration, and transformation (Hyndman & Athanasopoulos, 2018). Raw data often contained inconsistencies such as missing values, duplicate entries, and formatting errors. Using Power Query, these issues were addressed by removing duplicates, handling missing values through imputation or exclusion, and standardising formats for dates, player names, and numerical fields (Microsoft, 2025).

## Data Visualisation & Dashboards

Data visualisation played a crucial role in transforming complex datasets into clear, actionable insights. Power BI dashboards were designed to communicate the relationship between goals scored and expected goals (xG) effectively (Microsoft, 2025; Few, 2012). Visualisations included scatter plots to display correlations, ranking tables to highlight top performers, and interactive filters for drilling down by player, team, or season.
 
## Data Analytics

The analysis employed descriptive statistics, correlation analysis, and custom metrics to uncover trends and patterns (Hyndman & Athanasopoulos, 2018). Descriptive analysis summarised key metrics such as total goals, xG values, and differences (G + A) − (xG + xA) for each player (Mackenzie, 2019). Correlation analysis evaluated the strength of the relationship between goals and xG using scatter plots and trend lines. Ranking algorithms identified overperformers and underperformers.
The average of all players difference metric (G+A)-(xG+xA) was only 0.06. Indicating that the difference between G+A and xG+xA was very small. This means that xG and xA can be considered an accurate measurement.
 
## References

European Union (2016) Regulation (EU) 2016/679 (General Data Protection Regulation). Official Journal of the European Union.

FBref (2025) FBref Football Statistics. Available at: https://fbref.com (Accessed: 06/01/25).

Few, S. (2012) Show Me the Numbers: Designing Tables and Graphs to Enlighten. 2nd edn. Burlingame, CA: Analytics Press.

Hyndman, R.J. and Athanasopoulos, G. (2018) Forecasting: Principles and Practice. 2nd edn. Melbourne: OTexts.

Kaggle (2025) Football Players Stats (2024–2025). Available at: https://www.kaggle.com (Accessed: 06/01/25).

Knotts, L., Hensel, Z. and Nickerson, D. (2021) Measuring performance in football using expected goals. Journal of Sports Analytics, 7(2), pp.105–122.

Mackenzie, R. (2019) Expected goals: explanation and application. StatsBomb Blog.

Microsoft (2025) Microsoft Power BI Documentation. Available at: https://learn.microsoft.com/power-bi (Accessed: 06/01/25).

Spearman, W. (2018) Beyond xG: modelling interactions and expected outcomes in football. MIT Sloan Sports Analytics Conference Proceedings.

Sæther, S.A. and Solberg, H.A. (2015) Recruitment and performance analysis in professional football. European Sport Management Quarterly, 15(3), pp.257–276.


