# Induction Motor Rotor Bar Breakage Classifier

This repository contains the code and data for classifying rotor bar breakages in induction motors using machine learning techniques. The project aims to accurately detect faults in induction motors, providing a robust alternative to traditional Motor Current Signature Analysis (MCSA) methods.

## Project Overview

Induction motor rotor bar breakage can lead to performance degradation and potential motor failure. This project uses a stacking ensemble model with Random Forest and Gradient Boosting as base learners and Random Forest as the meta-model to diagnose rotor faults based on stator current data. The model's results closely match those of traditional MCSA, highlighting its reliability and accuracy.

## Data

The dataset used in this project is the **Broken Bars Induction Motors 2023 (BBIM2023)** dataset.

- **BBIM2023 Dataset**: Abu Elhaija, W., & Abu Al-Haija, Q. (2022). [Broken Bars Induction Motors 2023 (BBIM2023)](https://doi.org/10.17632/f5ksvkrp73.1). Mendeley Data, V1.

## Model

The machine learning model utilizes:

- **Base Learners**: Random Forest, Gradient Boosting
- **Meta Learner**: Random Forest

This stacking approach enables the model to capture complex patterns in the data, providing accurate fault classification even under varying conditions.

## Future Work

Future enhancements could include training the model on additional fault types such as underhang, overhang, and misalignment using data available online, making it more versatile for comprehensive motor health monitoring.
