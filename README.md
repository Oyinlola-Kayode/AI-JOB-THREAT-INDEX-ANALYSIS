# AI-JOB-THREAT-INDEX-ANALYSIS
The AI Job Threat Index Analysis provides a comprehensive examination of how artificial intelligence (AI) influences a wide range of job roles across various industries. 
Problem Definition

The objectives of this analysis are to identify:

- How AI impacts job roles across different domains.

- Which domains exhibit the highest levels of AI task adoption and AI workload ratios?

- The correlation between AI impact and workload distribution across job roles.

This analysis will help organizations and industries plan for workforce development and technological transitions driven by AI.

Data Overview

The dataset used for this analysis consists of various job roles, their associated tasks, and the extent to which AI models have automated these tasks. Visual attachments provide insight into the trends related to AI’s workload impact across sectors, using scatter plots, bar charts, and pie charts. Key fields in the dataset include:

- Job Roles: Specific roles in various industries.

- Total Tasks: Number of tasks associated with each job role.

- AI Impact: Extent of automation of tasks within a role.

- AI Workload Ratio: Proportion of tasks handled by AI models.

Methodology

Data Cleaning:

- Removed unnecessary characters to convert the AI Impact data type to numeric.

- Corrected spelling errors in fields such as “Job Title” and “Net Developer.”

Sorting and Grouping:

- The dataset was organized by AI impact, from highest to lowest. Conditional formatting highlighted the top 10 jobs most susceptible to automation.

- AI Impact Grouping: The AI impact scores were categorized into three distinct groups using the IF function:

- High Impact: Roles with an AI impact score greater than 0.70.

- Medium Impact: Roles with an AI impact score between 0.30 and 0.70.

- Low Impact: Roles with an AI impact score below 0.30.

-Pivot Tables:

- Created pivot tables for analyzing job distribution across domains, tasks completed, and AI models by domain.

Limitations

-Data Availability: The dataset focuses on roles where automation is more readily achievable, potentially overlooking industries where AI adoption is more complex or nuanced.

-AI Model Specificity: The dataset lacks detail on the specific types of AI models in use, which could provide deeper insights into the nature of task automation.

-Sectoral Underrepresentation: Fields like Manufacturing and Construction are underrepresented in the data, potentially limiting the generalizability of findings for manual labor sectors.

Findings and Insights

- Total Tasks by Domain

The Hospitality, Sales & Marketing, and Construction domains exhibit the highest levels of AI task automation, each surpassing 190,000 tasks. This underscores the extensive integration of AI in industries involving substantial operational and logistical tasks. Conversely, domains such as Healthcare and Data & IT display comparatively lower task counts.


-Top 10 Jobs Most Impacted by AI

The top 10 job roles most affected by AI include:

- Communication Managers

- Data Entry Clerks

- Compliance Officers

These roles are anticipated to undergo significant changes in task execution due to AI’s involvement.


- Correlation between AI Impact and Workload Ratio

A strong positive correlation exists between the AI impact score and the workload ratio. For instance, jobs with an AI impact score above 0.90 also had an AI workload ratio close to 0.14, indicating a heavy reliance on AI systems for task completion. In sectors such as Sales & Marketing and Administration, high workloads coupled with repetitive, process-driven tasks have seen increased automation. However, the Healthcare and Legal sectors exhibit lower workloads relative to AI automation due to the necessity for human-centric decision-making and complex problem-solving.


AI Impact Distribution

The distribution of AI impact across different job roles is categorized into three groups:

-Low Impact Category (83%): Roles, such as healthcare and legal professionals, experience minimal AI automation due to the requirement for human judgment.

-Medium Impact Category (14%): Roles in customer service, administration, and low-level management are moderately affected, as some tasks can be automated while still requiring human oversight.

High Impact Category (3%): Jobs like data entry clerks and telemarketers predominantly fall into this category, where most of their workload is automated by AI, leading to fewer human interventions.

AI Models Per Domain

Job roles within domains such as Administrative & Clerical and Communication & PR demonstrate a high adoption of AI models for routine tasks like data sorting and validation.


Conclusion

AI is rapidly automating tasks in administrative, clerical, and communication-related roles, profoundly reshaping these sectors. While other fields like healthcare and IT are beginning to integrate AI, manual labor sectors such as Manufacturing remain relatively untouched. The findings indicate that AI primarily focuses on automating repetitive and structured tasks, highlighting the necessity for upskilling and reskilling among employees in these affected roles. In the long term, AI is expected to redefine the nature of work rather than outright replacing jobs, shifting human focus from routine tasks to creative, strategic, and decision-making functions. Companies and workers must embrace this shift to thrive in an AI-driven future.

Recommendations

-For Organizations

Companies in sectors with high AI adoption should prioritize upskilling their workforce to manage tasks that AI cannot automate, such as decision-making, strategy, and creativity. In industries like Manufacturing, it is crucial to explore AI applications that could enhance human labor without job displacement.

-For Employees

Employees in highly impacted roles (such as Data Entry and Communication Managers) should consider reskilling to transition into areas where human expertise remains irreplaceable. Developing skills in AI management, data interpretation, and strategic thinking will be vital for career growth in an AI-driven future.

-Industry Focus

Industries such as Hospitality, Sales, and Marketing should prepare for a transformation in task execution, emphasizing how AI can complement human capabilities rather than replace them.

- AI Integration in Low-Impact Fields

Encourage AI adoption in low-impact sectors like health care by focusing on supportive technologies without displacing human workers.
