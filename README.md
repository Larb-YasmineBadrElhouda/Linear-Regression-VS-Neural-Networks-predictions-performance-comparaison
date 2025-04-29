in this notebook  , i explored **bike-sharing demand prediction** using various regression models, including:

**--------------------------------------------------------------------------------------------------------------------**
1. Simple Linear Regression using temperature as the only feature.
2. Multiple Linear Regression using several meteorological and functional features.
3. Neural Network Regression, both:
   - A shallow model (single dense layer),
   - A deep model (multiple hidden layers with ReLU activations).
     
**--------------------------------------------------------------------------------------------------------------------**
steps : 

1. Data Preparation:
  - Load and clean the Seoul Bike Sharing dataset.
  - Convert categorical variables to numeric.
  - Filter data to a specific hour (noon) for temporal consistency.
  - Drop weakly correlated or redundant features.

2. Exploratory Data Analysis:
  - Scatter plots to visually inspect correlations between features and bike count.

3. Models Development:
  - Implemented and trained models 
  - Normalization 
  - Loss function: Mean Squared Error (MSE).
  - Optimizer: Adam with learning rate adjustments.

4. Evaluation & Visualization & Comparison:
  - Comparison between linear and deep models using test MSE.
  - Visualization of predicted vs. actual bike rentals.
    
**--------------------------------------------------------------------------------------------------------------------**

Learning Objectives:

- Understand regression modeling workflows.
- Apply data normalization and feature selection.
- Evaluate trade-offs between simple models and more complex neural networks.
