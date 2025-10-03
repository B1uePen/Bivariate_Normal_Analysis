# Bivariate_Normal_Analysis

This project demonstrates **bivariate normal distribution analysis** including scatter plots, confidence ellipses, histograms, contour plots, normality tests, and Pearson correlation confidence intervals.

The goal is to generate a synthetic bivariate normal dataset and analyze its properties. Key features include:

1. **Data Generation**  
   - Created a 2D dataset with specified mean vector and covariance matrix.

2. **Visualization**  
   - Scatter plots with 50% and 90% confidence ellipses.  
   - Histograms with overlaid 1D normal PDFs.  
   - Contour plots showing joint PDF of X and Y.

3. **Normality Testing**  
   - Chi-square test in 2D bins.  
   - KS and Shapiro-Wilk tests (manual implementation possible).

4. **Correlation Analysis**  
   - Computed Pearson correlation coefficient.  
   - Constructed 95% confidence interval for correlation using Fisher's z-transform.

---

## Technologies Used

- Python 3  
- NumPy (data generation and calculations)  
- Matplotlib (visualization)  
- SciPy (statistical tests)  
- Seaborn (scatter plots)
