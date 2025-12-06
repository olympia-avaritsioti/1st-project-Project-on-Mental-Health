# First-project
Dataset source:https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset/data

Team:Mental Health Buddies
Avaritsioti Olympia, Zachos Panos, Zervos Theologos

Scope: 1st Project of Bootcamp Data Science at Big Blue Data Academy

Data: This dataset is based on a mental health questionnaire and demographic information, work-related factors, and self-reported mental health indicators.

Data Cleaning process: The dataset contained missing values exclusively in the self_employed feature. To preserve the original distribution, missing values were imputed based on the proportion observed in the non-null entries (approximately 90% and 10%, respectively)

Exploratory Data Analysis :
-convert Timestamp column from object to datetime
-creation of separate columns of year and month 
Insights made under three separate groups:
-No students females
-No students males
-Students

Insights:
For females time spend indoors correlates with the change in habits & the occupation

For females there is not important correlation for family history and mental health history

Regarding students, since the dataset did not include direct metrics, we estimated mental illness by assigning equal weights to the available categories and identified, in descending order, the countries most affected

We found that the number of students with a mental health score above the average is not associated with family history, as there were more cases among those without a family mental health background.

Additionally, for students with a score above the average, mental health outcomes do not appear to depend on the frequency of staying indoors

Higher Score means greater impact in overall Mental Health per Male person.

Lower Score means lesser impact in overall Mental Health.

Moldova seems to be leading in Mental Health issues and on the other hand Croatia,Greece,Mexico etc. countries seem to have the best work-to-life balance and general mental Illness state in correlation to our aforementioned factors.         