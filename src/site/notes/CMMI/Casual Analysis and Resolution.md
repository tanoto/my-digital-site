---
{"dg-publish":true,"permalink":"/cmmi/casual-analysis-and-resolution/","dgShowBacklinks":true,"dgShowToc":true}
---


[[CMMI/CAR Document\|Causal Analysis and Resolution Document]]



# 1. Scope / Intent

Processes and Products can never be considered absolute. Circumstances and situations may arise resulting in deviation from the defined and documented system. Circumstances may also exist wherein the defined system, unless changed, cannot be effectively implemented.

This procedure defines the methodology of identifying and analyzing the causes of defects and other problems during the execution of the projects and taking suitable actions to correct those types of defects and problems to prevent them from recurring.

Intent

-   Identify the causes of selected outcomes and take action to prevent the reoccurrence of undesirable outcomes or ensure the recurrence of positive outcomes.
-   Identify and address causes of selected outcomes.
-   Select outcomes for analysis.
-   Analyze and address causes of outcomes.
-   Determine root causes of selected outcomes by following an organizational process.
-   Propose actions to identified root causes.
-   Implement selected action proposals.
-   Record root cause analysis and resolution data.
-   Submit improvement proposals for changes proven to be effective.
-   Perform root cause analysis of selected outcomes using statistical and other quantitative techniques.
-   Evaluate the effect of implemented actions on process performance using statistical and other quantitative techniques.
-   Use statistical and other quantitative techniques to evaluate other solutions and processes to determine if the resolution should be applied on a broader scale.

# 2. Entry criteria

-   Size, effort, schedule, defects or cost not meeting performance objectives
-   Defects Data Trends need to be controlled.
-   Repetition of a particular problem
-   NCs from project audits
-   Process Performance Baseline
-   Control Chart Outliers
-   ANOVA analysis
-   What-If analysis

# 3. Inputs

-   Sprint Data from Jira
-   Jira
-   Audit report
-   Action Items

# 4. Value

-   Prevention of negative outcomes and increase of positive outcomes will lead to improvement in schedule adherence, quality and reduction in rework.
-   Helps to achieve business objectives.
-   Focuses efforts on the outcomes with the greatest impact on achieving objectives.
-   Reduces cost and time to more efficiently meet objectives.
-   Increases likelihood of meeting objectives by promoting successes and avoiding problems.
-   Reduces cost and time by preventing negative outcomes or producing positive outcomes.
-   Implements changes that have the most impact on increasing the likelihood of meeting objectives.
-   Recording and communicating improvement efforts across the organization can leverage savings and increase productivity.
-   Projects across the organization can take advantage of the savings and increased productivity.
-   Improves the likelihood that the project will meet its quality and process performance objectives.
-   Maximizes the likelihood of meeting quality and process performance objectives.
-   Leverages improvements across the organization to minimize cost and risk.

# 5. Key measures

Measure

Computation mechanism

Source of information

Lead Time

Lead time is the time between the start of story and the completion of testing. Lead time trend analysis and statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

Story activity data from Jira

Internal Defect Density

Internal Defect Density trend analysis and statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

Defect Log maintained in Jira

External Defect Density

External Defect Density trend analysis and statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

Defect Log maintained in Jira

Productivity

Productivity trend analysis and statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

Sprint level Data from Jira

# 6. Process Description

Causal Analysis will be done on following areas

-   Major deviations from the process performance objectives
-   Defect Trend Analysis reports
-   Productivity trend analysis
-   Non compliances found during audits

The causal Analysis will have following steps:-

-   Based on the trend analysis identify the action items
-   Assign the action items to the relevant stakeholders along with the target date
-   Project Manager to monitor the status of the action items
-   Statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

### Control chart outlier analysis

-   Do an RCA with the team using RCA template depicting 5 Why Analysis
-   Identify the root cause and action items
-   Assign the action items to the relevant stakeholders along with the target date
-   Project Manager to monitor the status of the action items
-   Statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

### Defect Analysis

-   ANOVA analysis to be done based on the type of defects captured across the lifecycle phases so as to find out recurring type of defect and take preventive actions
-   Do an RCA with the team using RCA template depicting 5 Why Analysis
-   Identify the root cause and action items
-   Assign the action items to the relevant stakeholders along with the target date
-   Project Manager to monitor the status of the action items
-   Statistical comparison to evaluate improvement in mean and reduction in SD using 2 Sample T test and F test to compare before and after improvement effects

### SEPG activities

-   Project manager to contribute project specific causal analysis to the SEPG for possible improvements across the organization
-   SEPG to monitor Statistical demonstration of improvements in Business Performance in terms of gross margin, revenue, delivered defects reduction
-   Trend analysis to be done to find out whether project performance is aligned with the NC closure and corrective actions are being taken

# 7. Exit Criteria

Successful 2 sample t test and f test before and after analysis

# 8. Outputs

-   Action items and the results
-   Statistical validations
-   RCA
-   Statistical demonstration of improvements in Business Performance in terms of gross margin, revenue, deliver defects reduction

# 9. Users of the document

Every employee concerned with implementation of quality management system and part of the SEPG Team

# 10. Formats and Guidelines

-   5 Why Analysis [Template](https://coda.io/d/_dPB_ZocZRrP/_sulJn)
-   What If Analysis