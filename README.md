# STAT 40233 - Bayesian Methods Final Project
### Using Bayesian Linear Regression to Predict Concrete Strength

Authors (Group 1):
* **Braedon Mulder**: writing (reviewing and editing), methodology, software, formal analysis, presentation.
* **Jayden Patel**: writing (original draft, reviewing, and editing), software, formal analysis, visualization.
* **Mallory Fortner**: writing (original draft, reviewing and editing), methodology, visualization.
* **Matthew Martinez**: writing (reviewing and editing), methodology, formal analysis, presentation.
    

Table of Contents:

* FinalReport.qmd/.pdf - Formatted quarto report
* Final.qmd - R code and testing outputs
* FinalPresentation.pdf - PDF of Google Slides Presentation
* concrete_data.RData - 800 data points for training and 230 with CCS missing (for making predictions)
* concrete_data_full.RData - Full dataset including the missing CCS column for the 230 data points
* 40233_Group_1.RData - Predictions on the 230 data points from concrete_data
* 40233_Group_1_results.RData - RMSE and interval score of predictions
* Two histograms of CCS distributions (before and after Box-Cox transformation)
* Plot of True vs Prediction with 95% CI