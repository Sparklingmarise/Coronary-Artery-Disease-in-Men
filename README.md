# (Dataset Exploration Title)
## by (Ezealigo Uchechukwu)


## Dataset

DataClean-fullage is a dataset on coronary artery disease (CAD) obtained from Kaggle [Link] (https://www.kaggle.com/datasets/homelysmile/datacad). This dataset has 6611 rows and 53 columns. The variables are mostly categorical, having binary numbers '1' and '0' representing 'yes' and 'no', respectively. The data as downloaded was clean and tidy.

The data was first explored for the value counts for the outcome of 6611 patients investigated for heart disease, and the number of days spent in the intensive care unit (icu). Age distribution was checked. Then the unwanted columns were dropped. the patients were categorized by gender, and the gender classification was repeated after selecting all patients with CAD. To further explore the data, we narrowed down into the male gender to verify the factors responsible for CAD and other heart related disease using 6 (six) age classification. 



## Summary of Findings

1. There were more patients discharged according to the doctor’s advice than those that were discharged against medical advice which make up 84% of the patients. This was first insight performed by plotting a bar and pie charts of the outcomes of the medical visit as presented by the dataset. Then the age distribution was explored. It was discovered that although the age range was between 10 years to 117 years, most men that visited the hospital were in the elderly and middle age category.

2. There are more males with CAD than heart failure and cardiomyopathy. This observation was the result of the selected data which was plotted using pie chart.

     |Heart conditions| With (%)| No (%)  |
     |CAD             | 70      | 30      |
     |Heart failure   | 48      | 52      | 
     |Cardiomyopathy  | 22      | 78      |
     


3. Generally, using the pie chart, the number of females (39%) were lower than the males (61%). There are 38% female and 62% male with CAD. This account was unveiled from the exploration of the original dataset and the selected dataset data frame for CAD, respectively. Although this revealed that the data distribution was not uniform, it shows that regarding CAD and heart failure, the males may have a greater susceptibility to CAD. 

4. Among the males with CAD, as shown form the bar chart, the difference between heart failure and hypertension was small unlike in females. However, after CAD, the order is as follows: hypertension, hear failure and diabetes in a descending order. There are more patients with CAD in males compared to other related health conditions in females, using the bar chart.

5. Among the men, 71% have CAD compared to the 29%. Further, we looked at the number of male patients with cad but have other complications. The bar chart shows that hypertension took the lead, followed by men who have experienced heart failure, and may have diabetes and the least among these complications is cardiomyopathy.

6. The men with both CAD (denoted by '1') and diabetes (also denoted by '1') are more hypertensive than those with heart failure and cardiomyopathy.

7. From a boxplot, the distribution of the ages of these patients revealed that the outliers lie at the lower age range (below 60 years) of the dataset, however, it cannot be dropped because children and older adult may have or not have any of the heart related issues. Hence, we may likely categorize age to have a better picture. Among the men, the elderly followed by the middle aged are highly prone to CAD compared to the other categories. This finding was concluded from exploring the males with CAD and plotting a bar chart.

8. At 60-70 years, men have their glucose concentration between 100-200 mg/dL. The heat plot was used to see that some male patients within the same age bracket have their blood glucose at higher levels than 200 mg/dL. Following this, men at age 50-80 years are likely to spent about 5-10 days in the intensive care unit (icu). This was further verified using the violin plot, showing age category versus blood glucose, and diabetes but in addition to the middle aged, elderly, the sensile also spend longer time in the icu.

9. Summary of results from the multivariate plots:
     
     - The glucose concentration for the middle aged, elderly, and senile men was high for those with cad compared to the juveniles, young and long livers with or without CAD.

    - Any man at any age category with or without CAD can spend similar number of days in the icu except for the juveniles with CAD.

    - The juveniles and the young have no report of CAD and diabetes while the middle, elderly, senile and long livers may be diabetic. Although, there are males in the elderly and senile categories that do not have CAD but are diabetic while in both the middle and long livers, there males that do not have both CAD and diabetes.

    - The juveniles and the young have no report of hypertension and diabetes while the middle, elderly, senile and long livers are diabetic and hypertensive. Also, the elderly and elderly can be diabetic and not hypertensive. Similarly, there can be diabetic males without hypertension among the senile and long liver category.

    - Every male with CAD is hypertensive but its degree is lower in juveniles. But the Senile with no cad can also be hypertensive.



## Key Insights for Presentation

- Having CAD is not a death sentence because we have seen that 84% of the patients were discharged from the clinic between 0-5 days of being in the intensive care unit (icu). This calls for more attention to one's health and lifestyle as one ages. In addition, regular medical check-up is advised as individuals approach certain age.

- Both genders are predisposed to having CAD.

- The males are highly at risk of having CAD. Hypertension and diabetes are key driving illness to developing CAD. Men should be careful especially when approaching middle and elderly age. Young men are advised to begin from their young age to consciously ensure that hypertension and developing diabetes is kept at minimal level.

- There is a correlation between hypertension, diabetes and CAD which is particularly high for the middle-aged and elderly men. Men who are close to this age range should adhere to a diet that checkmate their sugar level to prevent diabetes but most importantly, check their blood pressure regularly. Glucose concentration and diabetes are not found among the juvenile and young men, possibly due to some factors. For example, sugar is needed for cell development and energy for high physical activities which are needed by males of such age category.
