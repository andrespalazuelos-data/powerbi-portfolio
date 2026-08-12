# HR Analytics in Power BI

## Table of Contents
- [Project Background](#project-goals)
- [Data Structure](#data-structure)
- [Key Findings](#key-findings)
- [Dashboard](#dashboard)
---

## Project Goals

- Monitor key HR metrics on employees
- Understand what factors impact attrition

## Data Structure

The dataset consists of a single FACT table with **6,709 records** 

| Column | Description |
|--------|-------------|
| `PerformanceID` | Unique assessment identifier |
| `Employee_ID` | Unique employee identifier |
| `ReviewDate` | Date of assessment |
| `EnvironmentSatisfaction` | Rating 1-5 |
| `JobSatisfaction` | Rating 1-5 |
| `TrainingOpportunitiesWhitinYear` | Rating 1-5 |
| `WorkLifeBalance` | Rating 1-5 |
| `SelfRating` | Rating 1-5 |

and 5 DIMENSION tables covering Date, EducationLevel, Employee, Rating Level and Satisfied Level.

---

## Key Findings
### Overview
- Atlas Labs has employed over 1,470 people.
- Atlas labs currently employs over 1,200 people.
- The largest department by far is Technology
- The atrition rate for employees leaving the organization is 16%

### Demographics
- Majority of employees are between 20-29 years old.
- Currenlty, Atlas Labs employ 2.7% more women than men.
- Employes who identify as: 
- Non-Binary: make up to 8.5% of total employees
- White: have the highest average salary
- Mixed or multiple ethnic groups: have one of the lowest average salaries

### Attrition
- Attrition Rate is higher when people is required to do Overtime
- Also, when the company requires them to travel frequently
- From each department these are the highest roles with attrition: Sales Representative, Data Scientist and Recruiters.

## Dashboard

### Overview
![HR Summary](https://github.com/andrespalazuelos-data/powerbi-portfolio/blob/main/hr-analytics-dashboard/images/Overview.png)

### Demographics
![HR Summary](https://github.com/andrespalazuelos-data/powerbi-portfolio/blob/main/hr-analytics-dashboard/images/Demographics.png)

### Performance
![HR Summary](https://github.com/andrespalazuelos-data/powerbi-portfolio/blob/main/hr-analytics-dashboard/images/Performance.png)

### Attrition
![HR Summary](https://github.com/andrespalazuelos-data/powerbi-portfolio/blob/main/hr-analytics-dashboard/images/Attrition.png)

---


