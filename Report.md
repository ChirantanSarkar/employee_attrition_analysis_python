# Employee Attrition Report
___
## Executive Summary

This project analyzes employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. The objective is to identify the key factors contributing to employee turnover and provide actionable insights that can help organizations improve employee retention.

___

# KPI Dashboard

| KPI                                | Value      |
| ---------------------------------- | ---------- |
| Total Employees                    | 1,470      |
| Employees Left                     | 237        |
| Active Employees                   | 1,233      |
| Attrition Rate                     | 16.12%     |

---

# Key Findings

## 1. Overtime is the Strongest Driver of Attrition

Employees working overtime leave the company at nearly three times the rate of employees who do not work overtime.

| Overtime Status | Attrition Rate |
| --------------- | -------------- |
| No              | 10.44%         |
| Yes             | 30.53%         |

### Business Impact

Excessive workload and long working hours significantly increase the risk of employee turnover.

### Recommendation

* Monitor overtime hours regularly.
* Improve workforce planning.
* Promote work-life balance initiatives.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Attrition_vs_overtime.png)
___

## 2. Younger Employees Leave More Frequently

Employees who left the organization are younger on average.

| Category             | Average Age |
| -------------------- | ----------- |
| Employees Who Left   | 33.6        |
| Employees Who Stayed | 37.6        |

### Business Impact

Early-career professionals are more likely to explore external opportunities.

### Recommendation

* Develop structured career growth plans.
* Introduce mentorship programs.
* Increase internal mobility opportunities.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Tenure-wise_attrition.png)
___

## 3. Lower Compensation is Associated with Higher Attrition

Employees who left the company earned substantially less than retained employees.

| Category             | Average Monthly Income |
| -------------------- | ---------------------- |
| Employees Who Left   | $4,787                 |
| Employees Who Stayed | $6,833                 |

### Business Impact

Compensation plays a critical role in employee retention.

### Recommendation

* Review salary structures.
* Benchmark compensation against market standards.
* Introduce performance-based rewards.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Attrition_vs_income.png)
___

## 4. Sales Department Experiences Highest Attrition

| Department             | Attrition Rate |
| ---------------------- | -------------- |
| Sales                  | 20.63%         |
| Human Resources        | 19.05%         |
| Research & Development | 13.84%         |

### Business Impact

Customer-facing roles may experience greater pressure and turnover.

### Recommendation

* Investigate workload and incentive structures.
* Improve employee engagement within sales teams.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Department_vs_attrition.png)
___

## 5. Sales Representatives Have the Highest Turnover

| Job Role              | Attrition Rate |
| --------------------- | -------------- |
| Sales Representative  | 39.76%         |
| Laboratory Technician | 23.94%         |
| Human Resources       | 23.08%         |
| Sales Executive       | 17.48%         |
| Research Scientist    | 16.10%         |

### Business Impact

Sales Representatives represent the most vulnerable employee segment.

### Recommendation

* Improve onboarding and training.
* Create clearer career progression pathways.
* Review compensation and incentive models.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Attrition_vs_jobrole.png)
___

## 6. Job Satisfaction Directly Influences Retention

| Job Satisfaction Level | Attrition Rate |
| ---------------------- | -------------- |
| 1 (Lowest)             | 22.84%         |
| 2                      | 16.43%         |
| 3                      | 16.52%         |
| 4 (Highest)            | 11.33%         |

### Business Impact

Higher job satisfaction significantly reduces employee turnover.

### Recommendation

* Conduct employee satisfaction surveys.
* Address workplace concerns proactively.
* Strengthen employee recognition programs.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Attrition_vs_satisfection.png)
___

## 7. Poor Work-Life Balance Increases Attrition

| Work-Life Balance Rating | Attrition Rate |
| ------------------------ | -------------- |
| 1 (Poor)                 | 31.25%         |
| 2                        | 16.86%         |
| 3                        | 14.22%         |
| 4                        | 17.65%         |

### Business Impact

Employees with poor work-life balance are twice as likely to leave.

### Recommendation

* Encourage flexible work arrangements.
* Reduce excessive workloads.
* Support employee wellness initiatives.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Attriton_vs_work-life-balance.png)
___

## 8. Gender-Based Attrition Difference is Minimal

| Gender | Attrition Rate |
| ------ | -------------- |
| Male   | 17.01%         |
| Female | 14.80%         |

### Business Impact

Gender is not a major factor influencing attrition compared to overtime, compensation, and satisfaction.

### Chart
![alt text](https://github.com/ChirantanSarkar/employee_attrition_analysis_python/blob/main/Charts/Gender_vs_attrition.png)
___

# Conclusion

The analysis reveals that employee attrition is primarily influenced by:

1. Overtime workload
2. Compensation levels
3. Job satisfaction
4. Work-life balance
5. Department and job role

The attrition rate can be reduced significantly by improving employee well-being, offering competitive compensation, and creating clear career development opportunities. The highest-risk employee segment identified in this analysis is Sales Representatives working overtime with lower income levels and lower satisfaction scores.
___
