# MIST4610-Project2-Group2

## Team Name:
61608 Group 2

## Team Members:
1. Clark, Emily [@Emc33728](https://github.com/Emc33728)
2. Park, Isabella [@jp09478](https://github.com/jp09478)
3. Patel, Siddh [@srp8](https://github.com/srp8)
4. Singh, Saachi [@Saachi715](https://github.com/Saachi715)

## Dataset Description: 
Describing your dataset and what data it contains:
Where was it obtained, what are the dimensions of it (rows and columns), what are the various
columns, data types, etc. Describe it in sufficient detail so that an uninformed reader would
understand the dataset.

Our first dataset on missing persons cases in the United States provides a comprehensive collection of data focused on geographic and case-specific attributes, offering valuable insights into the distribution of such incidents across the country. Visualized in a map (Sheet 3), the dataset plots cases using geographic coordinates, with additional details like state and case counts highlighted through color and size variations. Although the exact source of the data isn’t specified, it is likely compiled from public records or law enforcement databases, often used for research and trend analysis in missing persons cases. The dataset is structured in a tabular format, potentially containing hundreds or thousands of rows, where each row represents an individual missing persons case. The columns include "STATE," a categorical string field (e.g., "California," "Texas") used to color-code data points by state on the map; "CNT(Case Number)," an integer field indicating the count of cases per location or state, which determines the size of the circles on the map; "Longitude (generated)," a float field representing the longitude in degrees (e.g., -122.4194 for a location in California), used to plot cases along the x-axis; and an implied "Latitude (generated)," also a float, representing latitude in degrees (e.g., 37.7749), used for the y-axis plotting, though not explicitly listed in the interface. The map visualization aggregates this data to show regional patterns, with larger circles indicating higher case counts and distinct colors for each state, revealing concentrations in areas like California, Texas, and the Northeast—possibly reflecting population density or socio-economic factors. This dataset is well-suited for geographic analysis, helping researchers, law enforcement, and policymakers identify hotspots, allocate resources efficiently, and develop targeted strategies to address missing persons cases across the U.S.

The second dataset on missing persons cases in the United States focuses on demographic factors, specifically examining the relationship between race/ethnicity, biological sex, and the average duration individuals remain missing or unidentified, as visualized in a bar chart (Sheet 2). Although the precise source of the data is not provided, it is likely derived from public records, law enforcement databases, or a national missing persons registry, commonly utilized for demographic analysis in such contexts. The dataset is structured in a tabular format, with rows representing aggregated groups of missing persons cases categorized by race/ethnicity and biological sex, though the exact number of rows is not visible in the visualization. The columns include "Race/Ethnicity," a categorical string field listing groups such as "Asian, Hawaiian/Pacific Islander," "American Indian," "White/Caucasian," "Black/African American," "Hispanic/Latino," "Asian," "Hawaiian," and "Black/African American, Hispanic"; "Biological Sex," another categorical string field with values "Female" (represented by red bars) and "Male" (represented by blue bars); and "AVG(Days Since Updated)," a numerical float field indicating the average number of days since the case was last updated, which serves as the y-axis metric on the chart. The bar chart reveals disparities in case duration across demographic groups, with categories like "Asian, Hawaiian/Pacific Islander" showing the longest average duration for both males and females (around 2000 days), while groups like "Hispanic/Latino" and "Asian, Hispanic" have shorter durations (closer to 500 days). The visualization highlights potential vulnerabilities, with females generally showing slightly longer average durations than males across most racial/ethnic groups, providing critical insights for researchers and policymakers aiming to address inequities in missing persons case resolutions. This dataset is well-suited for analyzing demographic influences on case outcomes, supporting the development of targeted interventions to reduce disparities and improve investigative strategies for at-risk populations.


## Questions:

Q1: Is there a notable geographic pattern or concentration for missing persons cases in the U.S.?

Analyzing the geographic distribution of missing persons cases is essential for identifying regional hotspots, trends, and spatial patterns. By visualizing these patterns, stakeholders can gain a deeper understanding of where incidents are most prevalent, allowing for more effective allocation of law enforcement resources, community outreach efforts, and preventive measures. This approach not only highlights areas with higher risks but also supports the development of tailored strategies to address localized factors contributing to disappearances.

Q2: Are there demographic factors significantly correlated with longer periods of individuals remaining unidentified or missing?

Investigating the role of demographic factors—such as age, gender, race, and socioeconomic background—in the duration individuals remain missing or unidentified provides critical insights into systemic disparities and vulnerabilities. This analysis helps uncover patterns in case outcomes, revealing which groups are disproportionately affected and why certain cases may remain unresolved for longer periods. By understanding these dynamics, policymakers and investigators can develop targeted interventions, enhance equity in resource distribution, and implement strategies to improve case resolution rates for at-risk populations.

## Manipulations: 
The manipulations applied to the data set as part of the analysis:
Were there any manipulations or calculations that needed to be performed on the data, what were
they, describe the purpose and how they were accomplished.

## Analysis and Results:
Analyze and visualize the results of your analysis and describe the implications of your analysis.
Please provide any citations if required as well as supporting visualizations and analysis
generated from Tableau.

### Question 1:
<img width="800" alt="mist_proj2a" src="https://github.com/user-attachments/assets/ff7760fe-11bd-4448-9f2b-606285ff3515" />

### Question 2




<img width="793" alt="mist_proj2c" src="https://github.com/user-attachments/assets/e7ede1c6-5956-4b18-96f1-62363dc22fda" />






