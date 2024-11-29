
# Concrete Strength Prediction

## Abstract
Concrete is a fundamental material in civil engineering, and its compressive strength is critical for construction quality. This project uses data on concrete mixtures to predict compressive strength using an Artificial Neural Network (ANN). The dataset contains information on various ingredients and the age of the concrete sample.

---

## Problem Statement
The goal is to predict the compressive strength (MPa) of a concrete sample based on its mixture composition and age. This involves building a predictive model using ANN.

---

## Dataset Description
The dataset consists of 8 independent variables and 1 target variable:

### Features:
1. **Cement**: Amount of cement in the sample.
2. **Blast Furnace Slag**: Improves strength and durability.
3. **FlyAsh**: Enhances the quality of concrete.
4. **Water**: Crucial for the chemical reaction in cement.
5. **Superplasticizer**: Increases workability without adding water.
6. **Coarse Aggregate**: Adds strength and reduces cement requirement.
7. **Fine Aggregate**: Smaller aggregate for better binding.
8. **Age (days)**: Time elapsed since the mix.

### Target:
- **Strength (MPa)**: Compressive strength of the concrete sample.

---

## Project Workflow
1. **Exploratory Data Analysis (EDA)**: Gain insights into the dataset.
2. **Data Preprocessing**: Handle missing values, scaling, and encoding.
3. **Model Development**: Build and train an ANN to predict compressive strength.
4. **Evaluation**: Analyze the model's performance using metrics like MAE and RMSE.

---

