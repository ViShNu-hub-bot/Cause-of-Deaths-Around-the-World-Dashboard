# Cause of Deaths Around the World Dashboard

Welcome to the Cause of Deaths Around the World Dashboard project! This dashboard provides insights into global causes of deaths, allowing you to explore trends and patterns over time.

## Live Dashboard
Access the live dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiMjdmOWExYmEtZTE2ZS00NGQ4LWFmMmUtODIwNmE3Y2M2NzM3IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9).

## Preview
![sql Preview](Screenshot%20(182).png)

## Key Insights
- **Line chart:** TotalDeaths by Year
- **Clustered bar chart:** MortalityRate by Country/Territory
- **Clustered column chart:** TotalDeaths by Country/Territory
- **Cards displaying causes of death:** 
  - Acute Hepatitis
  - Alcohol Use Disorders
  - Alzheimer's Disease and Other Dementias
  - Cardiovascular Diseases
  - Chronic Kidney Disease
  - Chronic Respiratory Diseases
  - Cirrhosis and Other Chronic Liver Diseases
  - Conflict and Terrorism
  - Diabetes Mellitus
  - Diarrheal Diseases
  - Digestive Diseases
  - Drowning
  - Drug Use Disorders
  - Environmental Heat and Cold Exposure
  - Exposure to Forces of Nature
  - Fire, Heat, and Hot Substances
  - HIV/AIDS
  - Interpersonal Violence
  - Lower Respiratory Infections
  - Malaria
  - Maternal Disorders
  - Meningitis
  - Neonatal Disorders
  - Neoplasms
  - Nutritional Deficiencies
  - Parkinson's Disease
  - Poisonings
  - Protein-Energy Malnutrition
  - Road Injuries
  - Self-harm
  - Tuberculosis
  - Total Deaths

## Narration
- TotalDeaths trended up, resulting in a 24.92% increase between 1990 and 2019.
- TotalDeaths started trending up in 1990, rising by 24.92% (1,08,44,404) in 29 years.
- At 8,846.94, China had the highest MortalityRate, 938.39% higher than Germany, which had the lowest MortalityRate at 851.99.
- Across all 10 Country/Territory, TotalDeaths ranged from 2,55,59,667 to 26,54,08,106.

## Features
- Slicer to filter based on year, country/territory
- DAX function for mortality rate: `MortalityRate = DIVIDE([TotalDeaths], COUNTROWS(cause_of_deaths) * 1000, 0)`

Explore the data and uncover insights into global causes of deaths!

Find me on [LinkedIn](https://www.linkedin.com/in/vishnukanth-k-a5552327b/) and [Medium](https://medium.com/@vishnukanthvis) for more insights and articles!

#DataVisualization #PowerBI #PublicHealth #DataAnalysis
