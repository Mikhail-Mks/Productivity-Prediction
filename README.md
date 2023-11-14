# Garment Manufacturing Productivity Prediction

## Overview

This repository contains the code and analysis for predicting the productivity range of garment manufacturing processes based on timelines and various parameters. The dataset used in this project is sourced from the UCI Machine Learning Repository, specifically the "Productivity Prediction of Garment Employees" dataset.

## Dataset

The dataset comprises essential attributes of the garment manufacturing process, including date, day of the week, department, team number, number of workers, style changes, targeted productivity, standard minute value (SMV), work in progress (WIP), overtime, incentive, idle time, idle men, and actual productivity. The data has been meticulously collected and validated by industry experts, offering insights into the labor-intensive and manual processes of the garment industry.

## Analysis Highlights

### Targeted Productivity Prediction

The primary objective of this analysis is to predict the targeted productivity for each team on a daily basis using a time series approach and other relevant parameters. The model, built with Keras, exhibits commendable predictive performance.

**Model Evaluation Metrics:**
- Mean Absolute Error (MAE): 0.12398
- Mean Squared Error (MSE): 0.02653
- Root Mean Squared Error (RMSE): 0.16289

These metrics underscore the model's ability to accurately predict targeted productivity.

### Key Findings

1. **Temporal Variation:** Targeted productivity is higher on weekdays than weekends and varies across departments and quarters.
2. **Correlations:** Actual productivity positively correlates with the number of workers, overtime, and incentives, while negatively correlating with style changes, work in progress, idle time, and idle men.

### Conclusion

The analysis demonstrates that garment manufacturing employee productivity can be predicted with a high degree of accuracy. Factors such as timelines, department, team number, number of workers, style changes, targeted productivity, SMV, WIP, overtime, and incentive contribute significantly to the prediction.

## Usage

1. **Data Source:**
   - The dataset can be accessed [here](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees).
   
2. **Dependencies:**
   - Ensure that you have the necessary dependencies installed, including Keras.

3. **Run the Code:**
   - Execute the provided code to train and evaluate the Keras model.

4. **Results and Insights:**
   - Refer to the analysis results for valuable insights into the factors influencing garment manufacturing productivity.

## Future Considerations

While the model performs well, it's crucial to emphasize the importance of high-quality and representative data. Continuous refinement and updating of the model with real-world data will enhance its predictive capabilities. Additionally, consider exploring further optimizations and features to improve the model's robustness.

Feel free to contribute, raise issues, or provide feedback to enhance the project's overall quality.
