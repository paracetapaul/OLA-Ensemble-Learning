# OLA-Ensemble-Learning

● Ola is a leading ride-sharing platform, aiming to provide reliable, affordable, and
convenient urban transportation for everyone.
● The constant challenge Ola faces is the churn rate of its drivers. Ensuring driver
loyalty and reducing attrition are crucial to the company's operation.
● Analyzing driver data can reveal patterns in driver behavior, performance, and
satisfaction. This would help in foreseeing potential churn, allowing proactive
measures.
● By leveraging data science and ensemble learning, Ola can predict driver churn,
which would be pivotal in its driver retention strategy.

Dataset Explanation: ola_driver.csv
1. MMMM-YY: Reporting month and year.
2. Driver_ID: A unique identifier for every driver.
3. Age: Age of the driver.
4. Gender: Driver's gender. Male: 0, Female: 1.
5. City: City code representing the city the driver operates in.
6. Education_Level: Education level of the driver, categorized into 0 for 10+, 1 for
12+, and 2 for graduate.
7. Income: Average monthly income of the driver.
8. Date Of Joining: The date when the driver joined Ola.
9. LastWorkingDate: The most recent or final day the driver worked with Ola.
10.Joining Designation: Designation of the driver at the onset of their journey with
Ola.
11. Grade: A grade assigned to the driver at the reporting time, likely denoting
performance or other metrics.
12.Total Business Value: The total monetary value (business) a driver brings in a
month. Negative values might indicate cancellations, refunds, or other financial
adjustments.
13.Quarterly Rating: Rating assigned to drivers on a quarterly basis. Ratings range
from 1 to 5, with 5 being the best.

Questionnaire :
1. What percentage of drivers have received a quarterly rating of 5?
2. Comment on the correlation between Age and Quarterly Rating.
3. Name the city which showed the most improvement in Quarterly Rating over
the past year
4. Drivers with a Grade of ‘A’ are more likely to have a higher Total Business Value.
(T/F)
5. If a driver's Quarterly Rating drops significantly, how does it impact their Total
Business Value in the subsequent period?
6. From Ola's perspective, which metric should be the primary focus for driver
retention?
1. ROC AUC
2. Precision
3. Recall
4. F1 Score

7. How does the gap in precision and recall affect Ola's relationship with its
drivers and customers?
8. Besides the obvious features like "Number of Rides", which lesser-discussed
features might have a strong impact on a driver's Quarterly Rating?
9. Will the driver's performance be affected by the City they operate in? (Yes/No)
10.Analyze any seasonality in the driver's ratings. Do certain times of the year
correspond to higher or lower ratings, and why might that be?
