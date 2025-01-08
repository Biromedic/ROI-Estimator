# Results Comparison

The performance of three machine learning models—**Linear Regression**, **KNN (k=12)**, and **Random Forest**—was evaluated using **Mean Squared Error (MSE)** and **R² Score**. The results are summarized in the table below:

| Metric                  | Linear Regression | KNN (k=12) | Random Forest |
|-------------------------|-------------------|------------|---------------|
| **Mean Squared Error**  | 90.03            | 27.35      | 35.13         |
| **R² Score**            | 0.7366           | 0.9201     | 0.8972        |

## Model Performance Insights

### Linear Regression
- **Performance**:  
  - Highest MSE: **90.03**  
  - Lowest R² Score: **0.7366**
- **Observations**:  
  - Limited ability to capture complex relationships in the dataset.

### KNN (k=12)
- **Performance**:  
  - Lowest MSE: **27.35**  
  - Highest R² Score: **0.92**
- **Observations**:  
  - Best-performing model, significantly improved by optimizing the `k` parameter.

### Random Forest
- **Performance**:  
  - MSE: **35.13**  
  - R² Score: **0.8972**
- **Observations**:  
  - Competitive results, effectively capturing non-linear relationships using ensemble methods.

---

## Additional Analysis and Insights

### High MSE and Variability of the Target Variable
- **Range of ROI**: 21 to 122.  
- **Impact**:  
  - High variability leads to larger squared errors, especially for extreme values.

### Outliers and Model Sensitivity
- **Impact**:  
  - High MSE indicates sensitivity to outliers.
  - Despite this, high R² scores suggest the models capture significant variability in ROI.

### Root Mean Squared Error (RMSE)
- **Interpretation**:  
  - RMSE: ~**5.23 units**.  
  - Relatively small considering the ROI range.

### Feature Set Limitations
- **Current Features**:  
  - Property Age, Location, Market Trend.
- **Suggested Additions**:  
  - Economic indicators, population growth rates, property size.  
  - These could enhance model accuracy and reduce MSE.

---

## Summary of Findings
1. **Key Observations**:
   - High MSE reflects ROI variability, outliers, and limited feature set.
   - KNN achieved the best performance with **MSE: 27.35** and **R² Score: 0.92**.

2. **Future Enhancements**:
   - Addressing dataset variability and outliers.
   - Expanding the feature set for improved predictions.

---

## Conclusion

This project demonstrates the application of machine learning models to predict **Return on Investment (ROI)** in real estate. Three models—Linear Regression, KNN, and Random Forest—were developed and evaluated.

### Key Findings
#### Linear Regression
- **Strengths**: Simple, interpretable.  
- **Weaknesses**: Limited ability to model non-linear relationships.  
- **Performance**:  
  - **MSE**: 90.03  
  - **R² Score**: 0.7366  

#### KNN (k=12)
- **Strengths**: Captures local patterns effectively, benefits from parameter optimization.  
- **Performance**:  
  - **MSE**: 27.35  
  - **R² Score**: 0.92  

#### Random Forest
- **Strengths**: Effective for non-linear relationships and feature interactions.  
- **Performance**:  
  - **MSE**: 35.13  
  - **R² Score**: 0.8972  

### Implications
- **Best Model**: KNN is the most suitable for this dataset due to its high accuracy.  
- **Alternative**: Random Forest is a reliable option for more complex datasets.

---

## Future Work
1. **Feature Expansion**:  
   - Incorporate additional features like economic indicators and demographic data.

2. **Advanced Techniques**:  
   - Explore Gradient Boosting or Neural Networks for better performance.

3. **Optimization**:  
   - Improve computational efficiency for KNN to handle larger datasets.

By achieving accurate ROI predictions, this project demonstrates the potential of machine learning in **real estate investment decisions**, enhancing **profitability** and **efficiency**.
