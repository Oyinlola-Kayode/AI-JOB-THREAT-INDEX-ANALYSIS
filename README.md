# AI Job Threat Index Analysis

## Overview

The AI Job Threat Index Analysis examines how artificial intelligence (AI) impacts a wide array of job roles across different industries. It explores the extent to which AI is automating tasks and how this automation varies by domain, helping organizations plan for workforce evolution in the age of AI.

## Problem Definition

The goals of this analysis are to:

- Identify how AI affects job roles in various sectors.
- Determine which domains show the highest levels of AI task automation and AI workload ratios.
- Explore the relationship between AI impact and task distribution across job roles.

This insight will guide organizations in workforce development and strategic technological transitions.

## Data Overview

The dataset used contains job roles, their respective tasks, and the degree to which AI models have automated these tasks. Key fields include:

- Job Roles: Specific positions within various industries.
- Total Tasks: Number of tasks associated with each job.
- AI Impact: Degree of automation (AI impact score).
- AI Workload Ratio: Proportion of tasks currently handled by AI.

Visualizations such as scatter plots, bar charts, and pie charts illustrate AI’s workload impact across sectors.

## Methodology

### Data Cleaning

- Removed non-numeric characters to convert AI Impact values to numeric.
- Corrected spelling errors in job-related fields (e.g., “Net Developer”).

### Sorting and Grouping

- Sorted job roles from highest to lowest AI impact.
- Applied conditional formatting to highlight the top 10 roles most susceptible to automation.

### AI Impact Classification

Job roles were categorized into three groups using the IF function:

- High Impact: AI Impact > 0.70  
- Medium Impact: 0.30 ≤ AI Impact ≤ 0.70  
- Low Impact: AI Impact < 0.30

### Pivot Table Analysis

Created pivot tables to analyze:

- Job role distribution across domains
- Total tasks completed per domain
- AI workload distribution by domain

## Limitations

- Data Availability: Focused on roles where automation is more feasible; may exclude nuanced or complex roles.
- AI Model Specificity: Does not specify which AI models are used, limiting the depth of insight.
- Sectoral Underrepresentation: Industries like Manufacturing and Construction are underrepresented, affecting generalizability.

## Key Insights

### Total Tasks by Domain

- Hospitality, Sales & Marketing, and Construction lead with the highest levels of AI task automation, each exceeding 190,000 tasks.
- These findings highlight AI’s strong presence in operations-heavy industries.
- In contrast, Healthcare and Data & IT show lower automation levels, indicating less AI involvement or more complex, human-driven tasks.


![image](https://github.com/user-attachments/assets/67c660b3-7cae-46e4-831d-90596d40772d)


## Top 10 Jobs Most Impacted by AI

The top 10 job roles most affected by AI include:

- Communication Managers  
- Data Entry Clerks  
- Compliance Officers  

These roles are anticipated to undergo significant changes in task execution due to AI’s involvement.


![image](https://github.com/user-attachments/assets/0536adeb-ac4c-4988-a8ca-69a96b1d12d0)

## Correlation between AI Impact and Workload Ratio

A strong positive correlation exists between the AI impact score and the workload ratio. 

For example, jobs with an AI impact score above 0.90 also had an AI workload ratio close to 0.14, indicating a heavy reliance on AI systems for task completion.

In sectors such as Sales & Marketing and Administration, high workloads coupled with repetitive, process-driven tasks have seen increased automation.

However, the Healthcare and Legal sectors exhibit lower workloads relative to AI automation due to the necessity for human-centric decision-making and complex problem-solving.


![image](https://github.com/user-attachments/assets/55f41274-bed3-424d-8c5c-4ee1db7bf4cf)


## AI Impact Distribution

The distribution of AI impact across different job roles is categorized into three groups:

- Low Impact Category (83%):  
  Roles such as healthcare and legal professionals experience minimal AI automation due to the requirement for human judgment.

- Medium Impact Category (14%):  
  Roles in customer service, administration, and low-level management are moderately affected, as some tasks can be automated while still requiring human oversight.

- High Impact Category (3%):  
  Jobs like data entry clerks and telemarketers fall into this category, where most of their workload is automated by AI, leading to fewer human interventions.

![image](https://github.com/user-attachments/assets/de96e33a-34f9-4533-870e-6b708ce72863) ![image](https://github.com/user-attachments/assets/85d83eb3-009d-47ad-89ca-b4364f71da89)


## AI Models Per Domain

Job roles within domains such as Administrative & Clerical and Communication & PR demonstrate a high adoption of AI models for routine tasks like data sorting and validation.


![image](https://github.com/user-attachments/assets/38162615-2842-4d16-af30-e1aa7fe8ff65)

## Conclusion

AI is rapidly automating tasks in administrative, clerical, and communication-related roles, profoundly reshaping these sectors. While other fields like healthcare and IT are beginning to integrate AI, manual labor sectors such as Manufacturing remain relatively untouched. 

The findings indicate that AI primarily focuses on automating repetitive and structured tasks, highlighting the necessity for upskilling and reskilling among employees in these affected roles. In the long term, AI is expected to redefine the nature of work rather than outright replacing jobs, shifting human focus from routine tasks to creative, strategic, and decision-making functions. 

Companies and workers must embrace this shift to thrive in an AI-driven future.

## Recommendations

### For Organizations  
Companies in sectors with high AI adoption should prioritize upskilling their workforce to manage tasks that AI cannot automate, such as decision-making, strategy, and creativity. In industries like Manufacturing, it is crucial to explore AI applications that could enhance human labor without job displacement.

### For Employees  
Employees in highly impacted roles (such as Data Entry and Communication Managers) should consider reskilling to transition into areas where human expertise remains irreplaceable. Developing skills in AI management, data interpretation, and strategic thinking will be vital for career growth in an AI-driven future.

### Industry Focus  
Industries such as Hospitality, Sales, and Marketing should prepare for a transformation in task execution, emphasizing how AI can complement human capabilities rather than replace them.

### AI Integration in Low-Impact Fields  
Encourage AI adoption in low-impact sectors like healthcare by focusing on supportive technologies without displacing human workers.
