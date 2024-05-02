<div align="center">
  <h1>Who Do Threat Actors Target in the Cyberspace? What Are They Looking For?</h1>
  <h2>By Sofiia Druchyna</h2>
  <h3><a href="https://sof0-0.github.io" target="_blank">GitHub.io Page</a></h3>
</div>

### Introduction

This research project is a part of CMPS 3160: Introduction to Data Science at Tulane University. I provide a comprehensive
analysis of cyber threat actors and cyber-attacks worldwide between 2014-2024 using two CISSM Cyber Events Datasets: FullThreatActors.csv and FullAttackList.csv. 
The datasets are accessible [here](https://cissm.liquifiedapps.com/#table). <br>

The objective is to understand emerging cyber threats and the behavior of threat actors in cyberspace,
as well as determine if there is any significant correlation between the location and type of each attack and actors' motives. I further use and cross-validate three machine learning models to predict the 
location, industry, and type of future attacks based on attackers' origins and motives.

### Research Questions

- Can we classify/group threat actors based on specific characteristics from the first dataset?
- How does the motive of cyber attackers correlate with victim characteristics and attack types?
- What are the trends and patterns in cyberattacks over the years?
  
### Methodology

*Original Experiments with Datasets* <br>

I explored the trends in the datasets using existing features and provide several bar plots to display the distribution of the particular characteristic. 
I further used grouping and filtering techniques to analyze on the subsets of data. 
Lastly, I created several pivot tables and data cubes to simultaneously display the sample count using several variables.

*Modeling Description* <br>

Having the defined research questions as our main objectives, I have built the KNN Classifier, SVM Classifier, and Decision Tree Classifier and experimented with various features, further performing the cross-validation to get the best prediction score on the new data. 
I have compared various model types (KNN vs SVC vs DT Classifiers) and determined the best model based on the cross-variable predictions (identifying trends between the attack Types and the Sub-Type from the same dataset) vs 
the cross-sets predictions (predicting the victim based on the attacker's characteristics and Motive, or the Country; or, determining the attacker's Type based on the victim's main characteristics).

### Key Findings

**General Results:**

- Identified leading threat actors and their motives (e.g., hacktivism, cybercrime).
- Highlighted correlations between attacker motives, attack types, and victim characteristics.
- Noted significant trends such as increased cyber activity during specific periods in different regions.

**Detailed Results:**

- The United States and Iran have been leading in the cyber-actors list.
- A distinct spike in U.S. hacktivist activity, the most common actor type, was recorded in 2015.
- The leading criminal actor in cyberspace is the Russian Federation.
- The leading nation-state's actor in cyberspace is China.
- An enormous spike in cyberattack activity starting in 2021 between the Russian Federation and Ukraine due to the war in the region. Most attacks from the Russian Federation are classified as criminal and disruptive and are performed with the "Sabotage" motive.
- Public Administration and Health Care industries are targeted the most.
- The "Financial" motive is the most prevalent in the United States, while the "Protest" motive is the most prevalent in Eastern Europe.
- The actor's motive and the attack type they choose are correlated the most and can be used to predict future attacks. <br>

### Contribution

This project contributes to the field of cybersecurity by providing insights into cyber threat actors' behavior and motives. 
The findings can be used for predictive analysis of future cyber threats and to enhance global threat intelligence.

### Usage
Please, use the [Github.io](https://sof0-0.github.io) page to access the Jupyter Notebook with all project details.
