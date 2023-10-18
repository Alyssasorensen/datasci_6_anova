# datasci_6_anova
## HHA 507 Homework Assignment 6

This assignment will help others gain hands-on experience with ANOVA analysis, understand its assumptions, and apply it to real-world datasets to understand differences among group means.

### *Reasoning Behind My Dataset and Variable Choices in Google Colab File*

### *Insights or Patterns Observed from the ANOVA Outcomes in Google Colab File*

### **Challenges Encountered** 
During this assignment, I faced a single challenge. When conducting the Levene Test to assess homoscedasticity, I consistently encountered "nan" values for both the statistic and p-value. Despite my efforts to identify the error in my code, I couldn't pinpoint the issue. As a result, I began modifying the code. It was only later that I realized my mistake lay in the way I wrote "African American" as opposed to the correct form, "AfricanAmerican." Once I corrected this, the "nan" values disappeared, and I obtained meaningful results: "LeveneResult(statistic=6.612907372118989, pvalue=9.970107179318563e-18)."