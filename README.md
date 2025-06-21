# Analysis-of-Employee-Experience-Survey-py
### Problem Statement: To Analyze the provided Employee Experience Survey dataset from a fictional nonprofit organization to identify key trends and insights related to employee engagement, job satisfaction, work-life balance, and other factors.

1. Dataset Loading and Preparation: :  Libraries used for the analysis are numpy, pandas, seaborn, matplotlib, scipy . 

![image](https://github.com/user-attachments/assets/d9efc5dc-428e-453f-b4b6-5d4d3efcfcf1)


2. Shape of dataset and First Five observation of data:  
![image](https://github.com/user-attachments/assets/31944ab9-de2d-44ee-8966-a5e612ed29c0)

3. Data understanding : Dataset is consists of 18 variables and 15 entries.  There is no null value present in the dataset. All the variables is of object data type.
![image](https://github.com/user-attachments/assets/e2d2e488-fd19-4142-ae16-1551303a080b)

4. Summary of the dataset: In the summary of dataset the count, unique, top and frequency of top can be seen. For instance, department have 8 unique entries and the top department is Sales with the frequency of 4.
![image](https://github.com/user-attachments/assets/0776fd14-d68a-4ff2-9f99-d233939ab2e9)

5. Extracting the demographic features from the dataset: There are 3 demographic features present in the dataset i.e.  Age Bracket, Gender and Ethnicity of the employees. So, extracting those demographic features which is essential for further analysis of employee experience to find the trends based on these features.
![image](https://github.com/user-attachments/assets/d3e19ab0-a347-42dd-b666-98e11de3edb1)

6. Mapping the responses: The responses ('Strongly Disagree', 'Disagree', 'Neutral', 'Agree' , 'Strongly Agree') are qualitative in nature, meaning they represent subjective opinions and cannot be directly used in numerical calculations. In order to perform statistical analyses (e.g., calculating mean, standard deviation, or running hypothesis tests), there was the  need to quantify these responses. So, mapping the responses was done.

![image](https://github.com/user-attachments/assets/6c9ea3b6-b2a5-4f2f-abfc-0bb2f27c8cd1)

7. Descriptive Statistics:
* Descriptive Statistics for Overall Engagement: Employees' involvement with the organization is generally neutral to slightly positive, according to the mean Overall involvement score of 3.4. There is some variation in the degree of involvement that various employees experience, as indicated by the standard deviation of 1.3, which displays a modest spread of engagement levels. Half of the employees had engagement levels between 2.5 (below neutral) and 4.5 (above neutral), with a median of 3.0, according to the 25th percentile (2.5) and 75th percentile (4.5).
![image](https://github.com/user-attachments/assets/50d1a4ab-b277-44a1-8ff4-4602be43735f)

* Descriptive Statistics for Job Satisfaction:  With an average job satisfaction score of 3.0, workers are generally indifferent to their level of job happiness.A wide range of employee experiences are reflected in the standard deviation of 1.31, which indicates a moderate variability in satisfaction levels with ratings ranging from 1 (extremely dissatisfied) to 5 (very delighted).
![image](https://github.com/user-attachments/assets/48b609d5-618c-4adc-a600-fd8cfce5edd8)

8. Trends Identification:
* Trends of Department vs. Job Satisfaction:
  - With average job satisfaction scores of 5.0 and 4.0, respectively, design and HR departments have the greatest levels of job satisfaction among employees.
  - Significant dissatisfaction among employees is shown by the IT department's lowest average job satisfaction score of 1.0.
  - Additionally, with scores below 3, Operations and Product Development demonstrate comparatively lower levels of satisfaction, indicating that these divisions  
  require focused efforts to improve employee satisfaction.
![image](https://github.com/user-attachments/assets/ef3d4806-7953-47e2-87d4-a3215b4fce37)

* Trend of Demographic feature vs. Job Satisfaction
  - Age Bracket: The Age Bracket group of 18-24 has the highest level of satisfaction with score of 3.42. Where as the Age Bracket group of 35-44 seems to have 
    lowest average job satisfaction score of 2.0. 
  - Gender: Male employees report higher job satisfaction (3.33) compared to female employees (2.78), suggesting a potential disparity in work experiences between 
    genders.
  - Ethnicity: Hispanic and Caucasian employees show the highest job satisfaction (4.0), while Indian employees report significantly lower satisfaction (1.67), 
  indicating differences in job satisfaction across ethnic groups that may require attention.
![image](https://github.com/user-attachments/assets/f4d8693d-923f-4898-8de4-33738f2cb204)

9. Inferential Statistics:
* t-test: It is a statistical method used to determine whether there is a significant difference between the means of two groups. So, will perform the independent t-test to see if there's a statistically significant difference in Job Satisfaction between two specific departments.  
* Job Satisfaction- IT and HR: The p-value (0.333) is greater than the significance level of 0.05, means there is no statistically significant difference in job satisfaction between the IT and HR departments. Based on the results, we fail to reject the null hypothesis, suggesting that the mean job satisfaction for IT and HR is similar. 
![image](https://github.com/user-attachments/assets/e3e18049-7d6a-421b-9998-d24134a3f456)

* Work-Life Balance- Sales and Design: 
The p-value (0.154) is greater than the significance level of 0.05, indicating that the difference in Work-Life Balance between the Sales and Design departments is not statistically significant.
The t-statistic (-1.90) suggests there is some difference in means, but it is not strong enough to reject the null hypothesis.
Therefore, we conclude that there is no significant difference in the average Work-Life Balance between employees in Sales and Design. 
![image](https://github.com/user-attachments/assets/3886a272-a4ee-4a2a-a990-04451423fc8e)

10. Correlation analysis:
![image](https://github.com/user-attachments/assets/c0490506-a54a-4c1b-9de6-3896f54abcd7)

Calculating the correlation between Work-Life Balance and Overall Engagement: A negative correlation suggests that as Work-Life Balance improves, Overall Engagement decreases. Its means employees who focus more on personal life may feel less engaged at work. 
![image](https://github.com/user-attachments/assets/71ff9d89-6242-42e2-9c76-9798c621665e)

11. Business Implications and Recommendations for the Fictional Nonprofit:
* Increase Job Satisfaction in Key Departments: Concentrate on increasing satisfaction in IT and Operations, where employees report the lowest scores. Conduct interviews to identify concerns and carry out action plans such as leadership support and workload modifications.
* Improve Work-Life Balance: Address work-life balance problems among older employees (45-54) and Hispanic employees, who report the lowest satisfaction. To prevent burnout, implement flexible work arrangements and health programs.
* Discuss compensation. Dissatisfaction: Lower salary satisfaction, particularly among younger employees and Caucasians, necessitates action. Conduct a compensation assessment and provide non-monetary rewards like as professional development opportunities and wellness perks.
* Promote Inclusivity and Equity: Strengthen the department's efforts to assist underrepresented groups, particularly Hispanic employees, by providing mentoring programs and cultural competency training to managers.
* Address Gender Differences in Work-Life Balance. To close the gender gap in work-life balance and promote gender parity, provide additional resources for female employees. 












