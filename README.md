# Impact of COVID-19 on Working Professionals: Power BI Dashboard
## Project Overview
This project analyzes the impact of the COVID-19 pandemic on working professionals, focusing on employment status, remote work adoption, and salary changes across different industries.
- Tools: Power BI and Excel
- Dataset: [[Kaggle Dataset by Normie](https://www.kaggle.com/datasets/gcreatives/impact-of-covid-19-on-working-professionals/data)].

## Key Questions
This dashboard is designed to explore key insights into the long-term effects of COVID-19 on the workplace. By examining various dimensions such as work hours, productivity, and employee well-being, it aims to provide valuable behavioral analysis that highlights the pandemic's impact on working professionals. Additionally, this dashboard serves as a predictive model to facilitate informed decision-making and make relevant data accessible to stakeholders seeking to understand and address the evolving dynamics of the modern workplace.

These are the key questions to achieve the above stated goal:
    
- **What is the impact of remote work on productivity and stress levels?**
    
- **What are the effects of increased childcare responsibilities and their subsequent impact on productivity and stress levels since the pandemic?**

- **What percentage of employees had to make technological adaptations, and does it relate to increased productivity?**

- **How has the pandemic affected work hours per sector?**

- **How has perception of job security changed since the pandemic, considering stress and new health issues (both physical and mental) incurred by COVID-19?**
 
- **What is the relationship between commuting changes and work-life balance?**

## Variables defined in Database

| Variable                      | Type       | Description                                                                                      |
|-------------------------------|------------|--------------------------------------------------------------------------------------------------|
| Increased_Work_Hours          | Binary     | Indicates whether the individual's work hours have increased as a result of the pandemic. 1 for increased, 0 for unchanged or decreased. |
| Work_From_Home                | Binary     | Reflects whether the individual has started working from home due to the pandemic. 1 for yes, 0 for no. |
| Hours_Worked_Per_Day         | Continuous | The average number of hours the individual works per day, providing insight into changes in work duration during the pandemic. |
| Meetings_Per_Day             | Continuous | The average number of virtual meetings the individual attends per day, highlighting the shift in communication methods. |
| Productivity_Change           | Binary     | Indicates if the individual's productivity has changed due to the pandemic. 1 for increased or decreased productivity, 0 for no change. |
| Stress_Level                  | Categorical| Self-reported stress level, providing insights into the psychological impact of the pandemic on work life. |
| Health_Issue                  | Binary     | Indicates if the individual has developed new health issues (mental or physical) during the pandemic. 1 for yes, 0 for no. |
| Job_Security                  | Binary     | Perception of job security during the pandemic, with 1 indicating feeling less secure.          |
| Childcare_Responsibilities     | Binary     | Whether childcare responsibilities have increased as a result of the pandemic. 1 for increased responsibilities, 0 for no change or decreased. |
| Commuting_Changes             | Binary     | Reflects changes in commuting patterns due to the pandemic, such as reduced or no commuting. 1 for changes, 0 for no change. |
| Technology_Adaptation         | Binary     | Whether the individual had to adapt to new technologies for remote work. 1 for yes, 0 for no.  |
| Salary_Changes                | Binary     | Indicates if the individual experienced any salary changes during the pandemic. 1 for change (increase or decrease), 0 for unchanged. |
| Team_Collaboration_Challenges | Binary     | Indicates if there were challenges in collaborating with teams during the pandemic. 1 for yes, 0 for no. |
| Sector                        | Categorical| The sector in which the individual is employed, providing context for the data and potential sector-specific impacts. |
| Affected_by_Covid             | Binary     | Indicates whether the individual’s work life was affected by COVID-19. This column is biased towards affected individuals (predominantly 1s). |

## Dashboard Visualization!
![Screenshot of Power BI report](covid_workforce/dashboard_overview.png)
- To View and Download the Original Dashboard, go to the [*covid_workforce*](covid_workforce) folder and download the raw *.pbix* file. 

## Key Conclusions
Looking at the above dashboard, we can now make some conclusions about our earlier established goals for this project:

- **What is the impact of remote work on productivity and stress levels?**
  - Based on the dashboard, remote work has a mixed impact on productivity. Those working from home generally experienced an increase in productivity, but it also correlates with varying stress levels. Individuals with medium stress levels reported the highest productivity gains, while those with high stress levels saw less improvement. This suggests that while remote work can enhance productivity, managing stress is a critical factor.
    
- **What are the effects of increased childcare responsibilities and their subsequent impact on productivity and stress levels since the pandemic?**
  - Childcare responsibilities have had a significant impact on both productivity and stress levels. Individuals with medium levels of stress reported the highest increase in childcare responsibilities, but surprisingly, they also saw moderate productivity gains. In contrast, those with high stress levels saw a more pronounced decline in productivity, highlighting that increased childcare responsibilities add to the stress burden and reduce productivity for many working professionals.

- **What percentage of employees had to make technological adaptations, and does it relate to increased productivity?**
  - According to the dashboard, 60.51% of employees experienced increased productivity while adapting to new technologies as part of their shift to remote work. The data shows a highly positive relationship between these technological adaptations and increased productivity. This suggests that companies who support their employees with technology training could see gains in overall performance.

- **How has the pandemic affected work hours per sector?**
  - The impact on work hours across the four sectors—IT, Healthcare, Education, and Retail—appears relatively similar, with each sector seeing an increase in work hours of about 25% for their employees. This suggests that while the nature of work in each sector may differ, the overall effect of the pandemic on workload has been consistent across industries. The similarity in increases could indicate that employees in all sectors have faced comparable pressures and demands during the pandemic, regardless of the industry they are in.

- **How has perception of job security changed since the pandemic, considering stress and new health issues (both physical and mental) incurred by COVID-19?**
  - The dashboard shows a direct connection between perceived job security and the development of new health issues during the pandemic. Those with high stress levels and low job security were more likely to report new health issues, both mental and physical. Employees with medium or low stress levels were less impacted by health problems. This correlation suggests that addressing job security concerns could alleviate some of the health-related, specifically mental-health, challenges workers have faced since the pandemic.
 
- **What is the relationship between commuting changes and work-life balance?**
  - There is a clear link between reduced commuting times and improvements in work-life balance. The dashboard highlights that as commuting changes, average work hours slightly decrease, but productivity show more significant improvements. This suggests that eliminating or reducing commuting can lead to more flexible work schedules, allowing employees to allocate time more efficiently and increase productivity, aiding in overall work-life balance.

## Contact
For more details or suggestions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/-vivianhe) or email: [haleyvivian16@gmail.com].
