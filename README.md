# Study of the Efficacy of Different Anti-Cancer Treatments
![labrat](https://criver.widen.net/content/tphknpjpnk/jpeg/RM-001678.jpeg?w=640&keep=c&crop=yes&color=cccccc&quality=80&u=fwtil1)

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
</br>

`python v.3.9.12`
`jupyter notebook v.6.4.8`
`pandas v.1.4.2`
`Visual Studio v.1.74.1`
`Matplotlib Pyplot v.3.5.1`
