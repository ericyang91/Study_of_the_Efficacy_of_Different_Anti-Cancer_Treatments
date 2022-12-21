# Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments
</br>

## Purpose:
The purpose of this study is to compare the efficacy of Capomulin, an anti-cancer medication, against other treatment regimens. In this study, 249 mouse subjects that were identified with squamous cell carcinoma, a common form of skin cancer, received medications of interest. Tumor development was then observed and recorded at certain time intervals up to 45 days.


## Data:

  A quick snapshot of the DataFrame:
</br></br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/rawdata.png" alt="rawdata"/>
</p>
</br>

## Observations:
</br>
Summary Statistics:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/summarystatistics.png" alt="summarystatistics"/>
</p>
</br>
Number of Timepoints for each Regimen:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/numberoftimepoints.jpg" alt="numberoftimepoints"/>
</p>
</br>
Sex Distribution of Specimen:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/sexdistribution.jpg" alt="sexdistribution"/>
</p>
</br>
DataFrame Including Final Timepoints:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/newmerged.png" alt="newmerged"/>
</p>
</br>
Outliers of the Best Regimens by Mean Tumor Volume:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/outliers.jpg" alt="outliers"/>
</p>
</br>
Box Plot of the Best Regimens by Mean Tumor Volume:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/boxplot.jpg" alt="boxplot"/>
</p>
</br>
Capomulin Treatment of Mouse r157:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/capotreatment.jpg" alt="capotreatment"/>
</p>
</br>
Capomulin Treatment: Average Tumor Volume vs. Average Weight:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/capoweight.jpg" alt="capoweight"/>
</p>
</br>
Linear Regression:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/Study_of_the_Efficacy_of_Different_Anti-Cancer_Treatments/blob/main/Images/linregress.jpg" alt="linregress"/>
</p>
</br>

## Analysis:
</br>

- Top 5 performing schools as measured by % passing both math and reading are all charter schools, with the total number of students and budget below the district average. The statistical significance of the difference is subject to further testing.
- Top 5 performing schools as measured by % passing both math and reading have test scores above the district average. The statistical significance of the difference is subject to further testing.
- Bottom 5 performing schools as measured by % passing both math and reading are all district schools, with the total number of students and budget above the district average. The statistical significance of the difference is subject to further testing.
- Bottom 5 performing schools as measured by % passing both math and reading have test scores below the district average. The statistical significance of the difference is subject to further testing.
- Schools in the lower budget per student category have higher subject scores. The statistical significance is subject to further testing.
- Schools in the higher budget per student category have lower subject scores. The statistical significance is subject to further testing.
- Schools with small student population (less than 2,000) on average have higher test scores. The statistical significance is subject to further testing.
- Charter schools on average have higher test scores. The statistical significance is subject to further testing.
</br>
** The general trend is that charter schools that on average have smaller student population have higher math and reading scores compared to district schools. Charter schools also spend on average less budget per student. Further study is required separate the effect of school types from that of the population on students' performance. It is also important to explore if there are any other factors related to charter schools that are affecting students' performance. Before these studies are performed, it is recommended to be cautious before making strategic decisions on budgeting. **

</br>
</br>

## Languages and Libraries:
</br>

`python v.3.9.12`
`jupyter notebook v.6.4.8`
`pandas v.1.4.2`
`Visual Studio 1.74.1`
