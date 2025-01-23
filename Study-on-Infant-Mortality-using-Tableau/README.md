# Extinguished Lights: A Visual deep dive into Infant Mortality

## Introduction
Infant mortality refers to the tragic loss of babies before their first birthday, a global issue affecting societies regardless of geography or socio-economic status. While advancements in medicine have reduced such cases, infant mortality remains a vital indicator of community health and well-being.

Studying its causes is crucial for uncovering immediate factors and deeper systemic issues, such as regional patterns, socio-economic influences, and healthcare disparities. This knowledge helps develop targeted interventions to address root causes effectively.

With access to extensive global data, this research aims to analyze not just the prevalence of infant mortality but also the factors driving it. The ultimate goal is to equip policymakers, healthcare professionals, and communities with actionable insights to reduce infant mortality and promote healthier outcomes for the world's most vulnerable.

## Data Sources
| Source | Name & URL | License | Comments |
| --- | --- | --- | --- |
| Kaggle |  Child and Infant Mortality (https://www.kaggle.com/datasets/programmerrdai/child-and-infant-mortality) | CC0: Public Domain | Primary Data Set |
| Kaggle | World Population (https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset) | CC0: Public Domain | World Countries Data |
| Kaggle | GDP per Capita (https://www.kaggle.com/datasets/nitishabharathi/gdp-per-capita-all-countries) | CC0: Public Domain | World GDP Data |

## Project Deliverables
- Project Report (DOCX or PDF)
- Project Presentation (PPTX)
- Raw Dataset (CSV or TXT)
- Cleaned Dataset (CSV or Tableau Hyper)
- Dashboard & Story (Tableau)
- Code (GitHub)

## Tools Used
`Microsoft Word` `Microsoft Excel` `Microsoft PowerPoint` `Tableau Prep Builder` `Tableau` `Python`

## Data Overview
I used three datasets for my analysis, with "Child and Infant Mortality" as the primary source. This dataset contains statistics on infant mortality across various years and countries, comprising 35 files, of which I focused on five:

- Causes of Death in Children
- Child Deaths by Age
- Child Mortality around the World
- Child Mortality by Sex
- Per Capita Health Expenditure vs. Infant Mortality

Additionally, I used two other datasets for country-specific data: Country-wise GDP and World Population.
To understand the data structure and identify cleaning needs, I imported the sheets into Python using pandas for a quick overview. However, I chose to perform data cleaning manually to better visualize and manage modifications during the integration process.


### Cleansing & Preparation
I analyzed details about the basic structure of each file and type of cleaning required for each
of them before starting with the visualizations. I decided to use the Tableau Prep builder
over Python for the same as it would be easier to visualize my data while cleaning and joining
it. My final data flow from Tableau prep builder is as follows. I generated a Tableau specific (.hyper) file to be used an input data source to Tableau for my visualizations.

<img width="1031" alt="image" src="https://github.com/user-attachments/assets/febc6aec-1056-4709-ac66-cfac04109982" />

### Visualization
Infant mortality, a critical indicator of a society's health and well-being, continues to be a
focal point of global concern. In this series of dashboards, we delve into the intricate
landscape of infant mortality, employing a comprehensive approach that combines data
from various sources. My visualizations aim to illuminate trends, patterns, and critical factors
that influence infant mortality rates across regions and over time.

|Country-wise Deaths Bubble|Top Causes vs Healthcare Spending|Year on Year Difference – Top Causes|
|---|---|---|
|<img width="411" alt="image" src="https://github.com/user-attachments/assets/0a4e3e2c-0cc2-40bc-a872-865fe617a9b7" />|<img width="475" alt="image" src="https://github.com/user-attachments/assets/c5b6d74d-39bb-4e20-810b-a0690f6adc76" />|<img width="486" alt="image" src="https://github.com/user-attachments/assets/495dbccb-e121-4b12-be8e-e2b870d77b30" />|

|Country Specific Factors and Death Counts|Cause-wise Death Counts|Countries with Highest Deaths|
|---|---|---|
|<img width="471" alt="image" src="https://github.com/user-attachments/assets/db5abdbd-11ec-49c4-b0bd-1515b4429b36" />|<img width="503" alt="image" src="https://github.com/user-attachments/assets/91edd927-4e0a-407c-8dd5-89a06decf617" />|<img width="475" alt="image" src="https://github.com/user-attachments/assets/054ec6bd-d797-4d7f-8a92-da8cec67a19b" />|


## Dashboards
#### Dashboard 1: Global Infant Mortality Statistics
<img width="864" alt="image" src="https://github.com/user-attachments/assets/212fcb79-67a7-49dd-9fc3-dc9744be24d1" />

#### Dashboard 2: Exploring Causes and Correlations
<img width="860" alt="image" src="https://github.com/user-attachments/assets/fb38b5c8-c78d-4d1f-82eb-bb19c7772953" />

#### Dashboard 3: Time Series Analysis
<img width="864" alt="image" src="https://github.com/user-attachments/assets/f2520e48-d5db-4b3a-a7d2-69c70a9d93a3" />


## How to Run ?
#### Tableau Prep-Builder

- (Optional) Make Changes to the data preprocessing flow by loading the Tableau Prep Flow file `Infant Mortality.tfl`

#### Tableau
- Load the Hyper file to prepare the cleaned data model `Infant Mortality - Cleaned Data.hyper`
- Load and run the Tableau Workbook mentioned below to access the story and dashboards `Infant Mortality - Tableau Workbook.twb`

## License

MIT License

Copyright (c) 2023 Eshita Gupta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
