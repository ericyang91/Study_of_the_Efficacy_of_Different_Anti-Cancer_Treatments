# Study of the Efficacy of Different Anti-Cancer Treatments
![labrat](https://criver.widen.net/content/tphknpjpnk/jpeg/RM-001678.jpeg?w=640&keep=c&crop=yes&color=cccccc&quality=80&u=fwtil1)

## Purpose:

In a recent animal study, 249 mice with squamous cell carcinoma (SCC) tumors were treated with various drug regimens, including Capomulin. Over a 45-day period, the study aimed to assess the efficacy of these treatments in inhibiting tumor development. The task involves using `Python` to analyze the complete dataset and generate tables and figures for the technical report. The study's top-level summary is pending detailed analysis, but it aims to compare the performance of Capomulin against other regimens, considering factors such as tumor size reduction, survival rates, and potential side effects. The ultimate goal is to provide the executive team with a comprehensive overview of the study results to inform future directions in anti-cancer medication development.


## Data:

A quick snapshot of the DataFrame:
</br></br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/rawdata.png" alt="rawdata"/>
</p>
</br>

## Observations:
</br>
### Summary Statistics:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/summarystatistics.png" alt="summarystatistics"/>
</p>
</br>
Capomulin and Ramicane emerge as the most effective in diminishing tumor volume among the mice samples. The minimal variance in sizes under these two regimens, coupled with the smallest standard errors, suggests a heightened level of precision and consistency in their impact. This implies a more uniform and reliable response to treatment within these groups, reinforcing the notion that Capomulin and Ramicane showcase notable effectiveness in consistently reducing tumor sizes across the studied mice samples. These findings underscore the potential significance of these regimens for further exploration and potential clinical applications.
</br>
</br>
Number of Timepoints for each Regimen:
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/numberoftimepoints.png" alt="numberoftimepoints"/>
</p>
</br>
The bar graph illustrates that the study has a greater number of timepoints allocated to the drug regimens 'Ramicane' and 'Ketapril,' while the regimen 'Zoniferol' has the fewest number of timepoints.
</br>
</br>
Sex Distribution of Specimen:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/sexdistribution.png" alt="sexdistribution"/>
</p>
</br>
The pie chart shows that we have a balanced distribution of male and female mice samples. This could imply that the researchers researchers aimed to minimize the impact of sex-related variables, making it easier to attribute observed effects to the treatments rather than potential gender biases. It's worth noting that such considerations in experimental design are essential for robust and reliable scientific findings, as they help control for potential confounding factors and enhance the generalizability of the results.
</br>
</br>
Line Graph Showing Changes in Tumor Volume Across the Timepoints for each Regimen:
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/tumordrugregimen.png" alt="tumordrugregimen"/>
</p>
</br>
Only two drugs - Capomulin and Ramicane - shows efficacy in decreasing the tumor volume in the mice sample. All the other drugs do not appear to have any effect in decreasing the tumor volume.
</br>
</br>
Box Plot of the Best Regimens by Mean Tumor Volume:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/boxplot.png" alt="boxplot"/>
</p>
</br>
There is one outlier under the drug regimen, Infubinol. This could imply several things including measurement error, biological variation, response heterogeneity, or drug resistance or ineffectivenes. Further investigation is required if the outlier raises concerns or questions about the validity of the data or the effectiveness of the drug regimen.
</br>
</br>
Capomulin Treatment: Average Tumor Volume vs. Average Weight:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/corr.png" alt="correlation"/>
</p>
</br>
Linear Regression:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/linregress.png" alt="linregress"/>
</p>
</br>
</br>
## Analysis:
- `Slope (Coefficient)`: The slope of the regression line is approximately 0.9544. This value indicates the change in tumor volume (dependent variable) for each unit increase in mouse weight (independent variable). In this case, as mouse weight increases, the tumor volume is expected to increase by approximately 0.9544 units.

- `Intercept`: The intercept of the regression line is approximately 21.5522. This is the value of the tumor volume when the mouse weight is zero. In practical terms, it might not have a meaningful interpretation in this context, as a mouse weight of zero is not meaningful in the context of this analysis.

- `Correlation Coefficient (rvalue)`: The correlation coefficient is approximately 0.8419. This value measures the strength and direction of the linear relationship between mouse weight and tumor volume. A positive value indicates a positive correlation, meaning that as mouse weight increases, tumor volume tends to increase.

- `P-Value`: The p-value is very small (1.322e-07), suggesting that the observed correlation is statistically significant. This means there is strong evidence to reject the null hypothesis that there is no correlation between mouse weight and tumor volume.

- `Standard Error (stderr)`: The standard error of the slope is approximately 0.1275. It represents the standard deviation of the sampling distribution of the slope. A lower standard error indicates more precision in estimating the slope.

- `Coefficient of Determination (R-Squared)`: The coefficient of determination, or R-Squared, is approximately 0.7089. This value represents the proportion of the variance in the dependent variable (tumor volume) that is predictable from the independent variable (mouse weight). An R-Squared of 0.7089 indicates that about 70.89% of the variability in tumor volume can be explained by the linear regression model using mouse weight.



## Summary:
</br>

- According to Summary Statistics, the four treatment regimens with the lowest mean tumor volume (mm3) in test subjects are Ramicane, Capomulin, Ceftamin, and Infubinol.
- According to Summary Statistics, the four treatment regimens with the lowest standard deviation of tumor volume (mm3) in test subjects are Ramicane, Capomulin, Ceftamin, and Infubinol.
- According to Summary Statistics, the four treatment regimens with the lowest standard error of means of tumor volume (mm3) in test subjects are Ramicane, Capomulin, Ceftamin, and Infubinol, suggesting the reliability of subjects.
- Not all subjects reacted well to Capomulin. An example is subject r157 that showed an increase in tumor volume (mm3) during the course of Capomulin treatment.
- The heavier the mouse, the less effective is Capomulin as depicted by the scatter plot.
- Linear regression shows R-squared value of 0.7, which suggests a reliable relationship between the subject's weight and Capomulin's effectiveness.
</br>
** The study shows that Capomulin's effectiveness on cancer treatment is only matched by that of Ramicane, but far surpasses those of Ceftamin and Infubinol. The effectiveness of Capomulin is influenced by the subject's weight, with lighter subjects reacting better to the treatment. **

</br>
</br>

## Languages and Libraries:
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-3776AB?style=flat&logo=matplotlib&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-3776AB?style=flat&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
