# Customer Support Ticket Analysis

## Project Overview

This project analyzes customer support ticket data to evaluate ticket volume, resolution efficiency, customer satisfaction, and ticket status distribution. The goal is to identify patterns in support operations and provide actionable recommendations to improve customer experience and operational efficiency.

The project uses Python for data cleaning and exploratory data analysis (EDA), and Tableau to build an interactive dashboard for visualizing key performance indicators (KPIs) and business insights.

## Business Objectives

- Understand the distribution of support tickets by category, priority, and status.
- Analyze average ticket resolution time across priority levels.
- Evaluate customer satisfaction across support categories.
- Identify potential areas for process improvement.
- Communicate findings through clear visualizations and an interactive dashboard.

## Tools and Technologies

- **Python:** Data cleaning, validation, exploratory data analysis, and statistical analysis.
- **Pandas and NumPy:** Data manipulation and numerical analysis.
- **Matplotlib and Seaborn:** Data visualization.
- **Jupyter Notebook:** Analysis workflow and documentation.
- **Tableau:** Interactive dashboard development.
- **CSV:** Cleaned dataset storage and data exchange.

## Dataset Description

The dataset contains 25 customer support tickets and nine columns covering ticket dates, categories, priorities, statuses, resolution times, customer satisfaction scores, customer emails, and assigned support agents.

Key fields include:

| Field | Description |
|---|---|
| `ticket_id` | Unique ticket identifier |
| `date` | Date the ticket was recorded |
| `category` | Type of support issue |
| `priority` | Ticket priority level |
| `status` | Current ticket status |
| `resolution_time` | Time taken to resolve a ticket, in hours |
| `customer_satisfaction` | Customer satisfaction score on a 1–5 scale |
| `customer_email` | Customer email identifier |
| `agent_name` | Assigned support agent |

## Data Cleaning and Preparation

The following steps were performed using Python:

- Standardized column names and text values.
- Converted ticket dates to a consistent datetime format.
- Converted resolution time and customer satisfaction fields to numeric types.
- Checked for duplicate records.
- Examined missing values and retained appropriate blanks for unresolved tickets and unavailable satisfaction ratings.
- Validated satisfaction scores and resolution times.
- Performed final data-quality checks before exporting the cleaned dataset.

## Key Findings

### 1. Ticket Volume by Category
Login Issues represented the largest category, accounting for 8 of 25 tickets (32%).

### 2. Resolution Time by Priority
Low-priority tickets had the longest average resolution time at 7.42 hours, compared with 3.83 hours for High-priority tickets and 3.94 hours for Medium-priority tickets.

### 3. Customer Satisfaction
Billing had the lowest average customer satisfaction score at 2.43 out of 5, while Login Issues had the highest among the reported category results at 4.43 out of 5.

### 4. Ticket Status
Of the 25 tickets, 21 were Closed (84%), three were Open (12%), and one was In Progress (4%).

### 5. Resolution Time and Satisfaction
The Pearson correlation between resolution time and customer satisfaction was approximately -0.51, indicating a moderate negative association in this sample. This does not establish causation.

## Business Recommendations

- **Improve billing support:** Investigate recurring billing complaints and improve communication around billing resolutions.
- **Review low-priority workflows:** Examine ticket complexity, workload distribution, and resolution targets for low-priority tickets.
- **Reduce recurring login issues:** Improve self-service troubleshooting guides and investigate common login problems.
- **Monitor support performance:** Track ticket volume, resolution time, and satisfaction over a longer period to validate these findings.

## Tableau Dashboard

The interactive dashboard is designed to present the following:

- Total tickets
- Average resolution time
- Average customer satisfaction
- Closed ticket rate
- Ticket volume by category
- Average resolution time by priority
- Customer satisfaction by category
- Ticket distribution by status

**View the interactive Tableau dashboard:** 
https://public.tableau.com/app/profile/krishna.krishnaprasad/viz/CustomerSupportTicketAnalysisTableau/Dashboard1?publish=yes

## Project Deliverables

- Cleaned customer support dataset (CSV)
- Jupyter Notebook containing data cleaning, analysis, and visualizations
- Tableau dashboard
- Summary of key findings and actionable recommendations
[text](<03-Analysis  Report and Key Insights/Customer Support Ticket Analysis Report.docx>)
## Limitations

This analysis is based on a small dataset of 25 tickets covering a limited reporting period. The results are exploratory and may not represent overall customer support performance. Additional data collected over a longer period would be needed to validate the findings and identify reliable trends.

## Conclusion

This project demonstrates how data cleaning, exploratory data analysis, statistical techniques, and dashboard development can transform raw support ticket data into actionable business insights. The findings highlight opportunities to improve billing satisfaction, review resolution workflows, and reduce recurring login issues.

---

**Project Type:** Data Analytics | Exploratory Data Analysis | Customer Support Analytics

**Author:** [Your Name]
