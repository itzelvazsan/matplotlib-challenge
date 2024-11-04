# Analysis of Treatments for Squamous Cell Carcinoma (SCC)

This analysis presents the results of a study that examined 9 treatments for squamous cell carcinoma (SCC). SCC is known for being a commonly occurring form of skin cancer.
This study analyzed 249 mice that had developed SCC tumors. The final sample included 248 mice. They received treatment with various drug regimens, along with a control group (placebo). The study established a 45-day observation period to monitor and measure tumor growth. The main objective was to compare the performance of the drugs, with particular attention to the effectiveness of Capomulin relative to the other treatment regimens.

##Statistics Summary
 
The table shows that Ramicane has the smallest mean tumor volume (40.21), and the median suggests that the distribution is approximately normal, as it is close to the mean (40.67). Capomulin, the drug of interest, has the second smallest mean tumor volume (40.67), with a median close to this value (41.55). Both drugs performed better compared to the placebo group.
The standard deviation of Ramicane is 4.84, and the standard deviation of Capomulin is 4.99, indicating that their distributions are not widely dispersed, meaning the observations are close to the mean. It is noteworthy that these two drugs had the smallest standard deviations among all the treatments in the study.

##Comparison of Mouse ID/Timepoints for each drug regimen
The bar chart shows that Capomulin and Ramicane are the drugs with the most timepoints observed in the mice. Both surpassed 200 timepoints. In contrast, the other observations have fewer than 200 timepoints, including the control group. This may suggest that the mice in these two groups survived longer due to the treatments they received.
 

##Distribution of unique female versus male mice used in the study
 
The pie chart shows that the distribution of female and male mice is nearly equal. Although the gender distribution is similar, it would be helpful to identify from medical literature which gender is more commonly affected by SCC. With this information, the distribution could be adjusted to more closely reflect real-world conditions.

##Box plot of Capomulin, Ramicane, Infubinol, and Ceftamin treatments
 
The box plot shows the distributions for four drugs: Capomulin, Ramicane, Infubinol, and Ceftamin. This plot indicates that Infubinol is the only treatment with outliers. The distributions for Capomulin and Ramicane demonstrate that they have the lowest final tumor volumes, and their data is not widely spread. Capomulin has a median that suggests its distribution is slightly skewed toward the third quartile.
Capomulin treatment of mouse l509
Analyzing mouse ID l509, we observe that its tumor volume decreased over the first 35 days, then began to increase in size. This mouse was part of the Capomulin group, so the plot confirms that this treatment helps to reduce tumor volume while the subject receives the drug.
 
##Linear regression: mouse weight vs. average tumor volume
 
The correlation between mouse weight and average tumor volume is 0.84, indicating a strong relationship between the two variables. However, this Pearson coefficient may be high due to collinearity between the variables. It is evident that a mouse's weight is influenced by tumor volume, and vice versa.
Additionally, the regression line shows a positive relationship between the variables. This suggests that a heavier mouse (g) tends to have a larger tumor volume (mm³). This regression may be affected by the same collinearity phenomenon for the same reason.
Conclusion
The principal findings are as follows: 
•	Ramicane and Capomulin have the smallest mean tumor volumes compared to the other groups and performed better than the placebo group.
•	These two drugs had the smallest standard deviations among all treatments in the study, indicating that their distributions are not widely dispersed.
•	The bar chart shows that Capomulin and Ramicane have the highest number of timepoints observed in the mice, in contrast to the other groups. Both surpassed 200 timepoints.
•	The distribution of female and male mice is nearly equal, at 49.6% and 50.4%, respectively. It is important to refer to medical literature to determine which gender is most affected by SCC, as this could influence the study's sampling structure.
•	Infubinol is the only treatment with outliers. The distributions for Capomulin and Ramicane have the lowest final tumor volumes, and their data is not widely dispersed.
•	Mouse ID l509’s timepoints indicate that its tumor volume decreased over the first 35 days, then began to increase. This mouse was in the Capomulin group.
•	The correlation coefficient between mouse weight and average tumor volume is 0.84, indicating a strong relationship. However, this may be due to collinearity between the variables, as a mouse’s weight is likely influenced by its tumor volume, and vice versa.
•	The regression line indicates a positive relationship: a heavier mouse (g) tends to have a larger tumor volume (mm³). This may also be due to collinearity.
