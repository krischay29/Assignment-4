# Assignment-4
frequency = c(0.6,0.3,0.4,0.4,0.2,0.6,0.3,0.4,0.9,0.2)
bloodpressure = c(103,87,32,42,59,109,78,205,135,176)
first = c(1,1,1,1,0,0,0,0,NA,1)
second = c(0,0,1,1,0,0,1,1,1,1)
final = c(0,1,0,1,0,1,0,1,1,1)
par (mfrow = c(1,3))
boxplot(frequency)
boxplot(bloodpressure)
boxplot(first, second, final)
par (mfrow = c(1,3))
hist(frequency)
hist(bloodpressure)
hist(c(first, second, final))
Explanation:
Boxplots: The distribution of the "Frequency" variable is shown in the first boxplot.
The "Blood Pressure" variable's distribution is shown in the second boxplot.
The distribution of the categorical variables "First," "Second," and "Final Decision" side by side is shown in the third boxplot. The many variables are distinguished by distinct colors.
Interpretation: Each variable's central tendency, spread, and skewness are visually summarized using boxplots. It is possible to view the distribution's overall shape as well as outliers.
Histograms: The distribution of the "Frequency" variable is shown in the first histogram.
The "Blood Pressure" variable's distribution is shown in the second histogram.
This third histogram shows the distribution of the three combined categorical variables: "First," "Second," and "Final Decision."
Interpretation: Histograms provide information about each variable's frequency distribution. They aid in figuring out any patterns or abnormalities and comprehending the concentration of numbers inside various ranges.
