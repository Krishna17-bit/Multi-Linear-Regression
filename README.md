## Overview
This repository contains Python notebooks that implement multiple linear regression models to predict outcomes based on various datasets. The models aim to understand the relationship between independent variables and a dependent variable by fitting a linear equation to observed data.

## Datasets
## Startups Dataset (50_Startups.csv)
This dataset provides information on 50 startups and includes the following fields:
- R&D Spend: Research and development expenses.
- Administration: Administrative expenses.
- Marketing Spend: Marketing and sales expenses.
- State: The state where the startup is based.
- Profit: The profit made by the startup.
This data is used to build a model that predicts startup profitability based on their expenditures and location.

## Toyota Corolla Dataset (ToyotaCorolla.csv)
This dataset includes details about used Toyota Corolla cars and contains fields like:
- Price: The offer price on the used car market.
- Age_08_04: Age of the car as of April 2008.
- Mfg_Month and Mfg_Year: Manufacturing month and year.
- KM: The kilometers driven by the car.
- Fuel_Type: Type of fuel the car uses (Petrol, Diesel, CNG).
- HP: Horsepower of the car.
- Met_Color: Whether the car has a metallic color (1) or not (0).
- Automatic: Indicates whether the car has an automatic (1) or manual (0) transmission.
- CC: Engine displacement in cubic centimeters.
- Doors: Number of doors on the car.
- Quarterly_Tax: Quarterly tax applicable for the car.
- Weight: Weight of the car in kilograms.
The goal with this dataset is to predict the price of a used Toyota Corolla based on its features.

## Libraries Used
- Pandas: For data manipulation and ingestion.
- NumPy: For numerical calculations.
- Matplotlib: For creating visualizations.
- Seaborn: For making attractive and informative statistical graphics.
- Statsmodels: For estimating statistical models.
