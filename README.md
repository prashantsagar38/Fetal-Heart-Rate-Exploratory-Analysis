# Fetal-Heart-Rate-Exploratory-Analysis

## Project Title:
</br>
Cardiographic Dataset Analysis: Exploring Fetal Heart Rate Patterns and Indicators

## Project Overview:
</br>
The goal of this project is to conduct a comprehensive exploratory analysis of the "cardiographic.csv" dataset, which contains various metrics related to fetal heart rate monitoring. The analysis will involve cleaning and preparing the data, summarizing its statistical properties, visualizing key aspects, and uncovering patterns and insights that could provide valuable information about fetal health.

## Dataset Description:
</br>
The dataset comprises the following features related to fetal heart rate (FHR) and associated metrics:

LB (Baseline Fetal Heart Rate): Represents the average fetal heart rate over a period.</br>
AC (Accelerations): Indicates the presence of accelerations in the FHR, a sign of fetal well-being.</br>
FM (Fetal Movements): Tracks fetal movements detected by the monitor.</br>
UC (Uterine Contractions): Measures uterine contractions, which can impact FHR patterns.</br>
DL (Decelerations Late): Indicates decelerations that occur late with respect to uterine contractions, potentially signaling fetal distress.</br>
DS (Decelerations Short): Represents brief decelerations in the FHR.</br>
DP (Decelerations Prolonged): Measures long-lasting decelerations in the FHR.</br>
ASTV (Percentage of Time with Abnormal Short Term Variability): Represents the percentage of time with abnormal short-term variability in the FHR.</br>
MSTV (Mean Value of Short Term Variability): The average value of short-term variability in the FHR.</br>
ALTV (Percentage of Time with Abnormal Long Term Variability): Represents the percentage of time with abnormal long-term variability in the FHR.</br>
MLTV (Mean Value of Long Term Variability): The average value of long-term variability in the FHR.


### Objectives:

### Data Cleaning and Preparation:

- Load and inspect the dataset.
<img width="1320" height="296" alt="image" src="https://github.com/user-attachments/assets/e43fe8ea-b3de-4209-93e0-43b870349ca3" />

* Handle missing values and inconsistencies.
<img width="1302" height="372" alt="image" src="https://github.com/user-attachments/assets/6c1eb406-8c85-4a33-a28e-14573eb0a65b" />

+ Normalize and correct data types as needed.
<img width="1315" height="372" alt="image" src="https://github.com/user-attachments/assets/e33781ce-9e0e-4b3d-ae5f-f7b2342857c2" />

- Detect and manage outliers.</br>
<img width="1316" height="157" alt="image" src="https://github.com/user-attachments/assets/08b5a0fa-8ce1-418f-a5b6-0e7a8d686331" />


### Statistical Summary:

- Compute and present statistical summaries for each feature (e.g., mean, median, standard deviation).
<img width="1312" height="666" alt="image" src="https://github.com/user-attachments/assets/00833102-adbb-4322-9a88-d93027512410" />

* Highlight key observations and unusual patterns.</br>
<img width="1316" height="172" alt="image" src="https://github.com/user-attachments/assets/a42850de-5df0-4d24-b571-357a055109cb" />

### Data Visualization:

- Create visualizations to understand the distributions of numerical features (e.g., histograms, box plots).
<img width="1307" height="637" alt="image" src="https://github.com/user-attachments/assets/ccd3b5f9-1dd4-40eb-adaa-4e53f7eac718" />
<img width="1221" height="437" alt="image" src="https://github.com/user-attachments/assets/8c11cc36-dc5a-4525-9d69-bdd9dd9e8891" />
<img width="1302" height="77" alt="image" src="https://github.com/user-attachments/assets/6f4c506d-edea-4c53-b2bf-f8e2f98d30f9" />
<img width="962" height="665" alt="image" src="https://github.com/user-attachments/assets/8cb4f196-eb53-439a-bb8f-ca02b6f59a7a" />
<img width="1310" height="631" alt="image" src="https://github.com/user-attachments/assets/e02c403e-bd0e-46a9-acba-0317fa9ce7ad" />
<img width="1312" height="551" alt="image" src="https://github.com/user-attachments/assets/5f8e05a9-6661-4198-8098-2202d4e35523" />
<img width="1310" height="587" alt="image" src="https://github.com/user-attachments/assets/54c576d6-6dd7-4bae-ad24-9bfe1f0b6b95" />

+ Develop scatter plots and correlation heatmaps to explore relationships between variables.
<img width="1337" height="126" alt="image" src="https://github.com/user-attachments/assets/279947be-5041-4593-86bb-b8a653a65ac4" />
<img width="1342" height="627" alt="image" src="https://github.com/user-attachments/assets/ba29714d-e306-4be3-bb31-31042176ec0c" />
<img width="1347" height="562" alt="image" src="https://github.com/user-attachments/assets/64afbe6b-f8f2-41c4-a02e-cbbddeeb21d7" />
<img width="1350" height="562" alt="image" src="https://github.com/user-attachments/assets/bc42fb86-da49-4fc4-9bf8-f93e70da4f5b" />
<img width="1352" height="562" alt="image" src="https://github.com/user-attachments/assets/a2e40e5f-2f80-4e54-9002-cf1c38810493" />

* Use bar charts or pie charts to visualize categorical data.
<img width="1336" height="142" alt="image" src="https://github.com/user-attachments/assets/f73956c8-9def-4f5e-b0d7-e4db8a45a7e4" />
<img width="1342" height="622" alt="image" src="https://github.com/user-attachments/assets/bfff9058-bdac-40fb-8cdb-1fbea81965c0" />
<img width="1335" height="146" alt="image" src="https://github.com/user-attachments/assets/7b785a91-ed19-4c7e-a2bb-80a11c5e54e8" />
<img width="1332" height="626" alt="image" src="https://github.com/user-attachments/assets/06413a29-7bf1-410b-a3a5-e692e13c0b0d" />
<img width="1337" height="161" alt="image" src="https://github.com/user-attachments/assets/ab805ab9-4594-47c1-916d-34f673731b5f" />
<img width="1347" height="627" alt="image" src="https://github.com/user-attachments/assets/9e9b6c18-62b4-44eb-a547-9f7de723ab32" />

- Apply advanced visualization techniques like pair plots or violin plots for deeper analysis.
</br>

### Pattern Recognition and Insights:

- Identify correlations between features and discuss their implications.
* Explore temporal trends and patterns if applicable.
<img width="1337" height="580" alt="image" src="https://github.com/user-attachments/assets/26237394-e203-48d2-be26-49c63ad2ee3c" />

</br>

### Conclusion:

- Summarize key insights and patterns uncovered.
* Provide recommendations for further analysis or potential actions based on the findings.

### Impact: 
</br>
The insights gained from this analysis can help in understanding fetal heart rate patterns and potentially improve monitoring and decision-making during pregnancy. By identifying significant patterns and correlations, this project aims to contribute valuable information for healthcare providers working with fetal cardiographic data.
