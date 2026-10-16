Understanding Gen Z Career Aspirations 

A data analytics project exploring what Gen Z wants from their careers, workplace, salary, managers, and company values.

Tools Used: Microsoft Excel | SQL | Power BI

# Project Overview

Companies need to understand what Gen Z expects from their jobs, work environment, and managers.

The goal of this project is to analyse survey data, identify important patterns in career aspirations, and provide actionable recommendations for HR teams.

# Project Objectives

- Analyse career aspirations among Gen Z respondents.
- Understand work mode and salary expectations.
- Identify expectations from managers and company missions.
- Use SQL to answer business questions.
- Build dashboards to communicate insights.
- Recommend actions that HR teams can take.

# Dataset Information

- **Total respondents:** 3,613
- **Respondents from India:** 3,488
- **Excel analysis:** India-only data
- **SQL analysis:** India-only data
- **Power BI analysis:** All 3,613 respondents

# Tools and Techniques

# Microsoft Excel
- Data cleaning
- Pivot tables
- Dashboard creation
- Work mode and salary analysis

# SQL
- Filtering data using WHERE
- Aggregation using COUNT
- Grouping using GROUP BY
- Sorting results using ORDER BY
- Answering business questions

# Power BI
- Data type correction
- Data modelling and relationships
- Measures and calculations
- Dashboard development
- Visual analysis of manager and mission aspirations


 1. Excel Dashboard
Analysis of work mode preferences and salary expectations among Gen Z respondents in India.


 2. Power BI Dashboard — Manager Aspirations
Analysis of what Gen Z expects from managers.


 3. Power BI Dashboard — Mission Aspirations
Analysis of the importance of company mission and values.


# SQL Analysis

**Business Question:** Which career aspirations are most common among Gen Z respondents in India?

```sql
SELECT Option, COUNT(Option) AS respondents
FROM career_aspirations
WHERE Country = 'India'
GROUP BY Option
ORDER BY COUNT(Option) DESC;
```

# Results

| Career Aspiration |             |Respondents |

| Design and Creative Strategy |    | 1,815 |
| Business Operations |             | 1,623 |
| Build and develop a Team |        | 1,464 |
 
# Key Insights

- Work flexibility: 46% prefer hybrid work, while 33% prefer remote work and 21% prefer office-based work.
- Manager expectations:57% want managers who explain expectations and provide support.
- Company values: 76% would not work for a company whose mission does not align with their values.
- Salary expectations: About 29% expect more than 50k per month in the first three years.
- Long-term salary expectations: 22% expect above 151k per month after five years.
- Learning and rewards: 52% want employers who challenge them, support learning, and reward their efforts.

# Business Recommendations

1. Offer flexibility: Clearly communicate hybrid and remote work options in job descriptions when available.
2. Improve management: Train managers to set clear expectations and support their teams.
3. Communicate company values: Explain the company's mission during recruitment.
4. Provide salary transparency: Share salary ranges and explain career-based pay progression.
5. Support career growth: Offer mentoring, learning opportunities, and regular career discussions.

#What I Learned

Through this project, I learned how to clean survey data, analyse it using SQL, and build dashboards in Excel and
Power BI.I also learned how to turn numerical findings into business insights and practical recommendations.

