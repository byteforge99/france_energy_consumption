# Net-Zero Buildings Data Challenge – France Edition

## Overview
This project is part of the **Net-Zero Buildings Data Challenge – EU Edition**, focusing on analyzing the energy performance of buildings in France. The goal is to identify cost-effective renovation strategies and develop machine learning models to optimize energy efficiency.

## Project Hypothesis
### Energy Consumption & Greenhouse Gas Emissions
- **H1:** Older buildings have higher energy consumption and greenhouse gas emissions.
- **H2:** Larger habitable surfaces contribute to increased energy consumption and emissions.
- **H3:** Buildings with glass roofs may have higher energy consumption due to heat loss.
- **H4:** Buildings in colder winter zones have higher heating energy consumption.

### Thermal Performance & Heat Loss
- **H5:** Buildings with more north-facing bay windows experience higher heat loss.
- **H6:** Commercial buildings (shopping centers, ERP) have higher energy consumption due to heating and cooling demands.
- **H7:** The presence of an airlock at entrances reduces energy loss and improves efficiency.

### Geographical & Environmental Impact
- **H8:** Buildings located in high-altitude departments consume more energy due to harsher climates.
- **H9:** Areas with a high density of old buildings have lower average energy efficiency ratings.

## Objectives
1. Conduct **Exploratory Data Analysis (EDA)** to derive insights on building energy performance.
2. Identify the most cost-effective renovation strategies in terms of energy savings and financial efficiency.
3. Develop a **Machine Learning Model** to predict energy consumption, estimate efficiency class, or provide renovation recommendations.
4. Present findings in a structured and accessible **report** for non-technical audiences.

## Approach
### 1. Exploratory Data Analysis (EDA) *(30 points)*
- Investigate trends and distributions in the dataset.
- Identify key factors influencing energy consumption.
- Determine cost-effective and financially efficient renovation measures.

### 2. Machine Learning Model *(40 points)*
- Developed a model to **predict building energy consumption** (kWh/m²) based on available features.
- Preprocessed data, handled missing values, and engineered features for better performance.
- Evaluated model accuracy and interpretability.

### 3. Report *(20 points)*
- Summarized findings with clear visualizations and actionable insights.
- Structured report to be understandable for non-technical stakeholders.

### 4. Bonus *(10 points)*
- Applied the model to a real-world case study to demonstrate practical utility.

## Project Structure
```
|-- data/                 # Contains datasets used for the challenge
|-- notebooks/            # Jupyter notebooks for EDA and model development
|-- reports/              # Final analysis report
|-- src/                  # Source code for data processing and modeling
|-- README.md             # Project documentation
|-- requirements.txt      # Dependencies
```

## Requirements
To run the notebooks and scripts, install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the **EDA notebook** to explore the dataset:
   ```bash
   jupyter notebook France_Energy_Sector.ipynb
   ```
