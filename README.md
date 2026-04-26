# clinical-trial-enrollment-risk-analysis
**Strategic Dynamics and Performance Trends in Pharmaceutical R&D**

**Project Overview**
This project analyzes a large-scale dataset of clinical trials to support managerial decision-making in pharmaceutical Research and Development (R&D). By examining patterns in enrollment size, trial phase progression, and completion outcomes, the analysis identifies which trial phases and therapeutic areas carry the highest operational and scientific risks.

**Business Problem**
Pharmaceutical R&D is a high-stakes, resource-intensive process. R&D managers face significant challenges in resource allocation across complex, multi-phase trials. This project seeks to provide data-driven insights to optimize these investments by answering three core questions:
1. How does average enrollment size vary across clinical trial phases?
2. What are the operational outcomes (completion vs. termination) of these trials?
3. Which therapeutic conditions show the highest volume of clinical trial activity?
   
**Dataset Information**
The analysis utilizes the “Pharmaceutical R&D: Clinical Trial Data Overview” dataset, which includes:
- Total Trials: 13,749 unique clinical trials.
- Key Variables: Trial phase, enrollment size, start dates, therapeutic conditions, and trial status.
- Format: Trial-level data suitable for analyzing overall strategic performance patterns.

**Analytics Workflow**
The project follows a structured five-step Python-based workflow:
1. **Data Overview:** Initial exploration of the 13,749 entries.
2. **Enrollment by Phase:** Analysis of participant volume as trials progress.
3. **Enrollment Distribution:** Identifying skewness in participant data.
4. **Top Clinical Conditions:** Mapping the therapeutic landscape.
5. **Trial Status & Completion Rates:** Quantifying operational success and failure.

**Key Findings**
- Enrollment Scaling: Later phases show significantly higher enrollment. Phase 3 trials average nearly 800 participants, compared to approximately 51 in Phase 1.
- Data Skewness: Enrollment data is highly skewed, with a mean of 431 and a maximum of 84,496, indicating that a few large-scale studies drive the majority of resource demands.
- Strategic Concentration: Activity is heavily concentrated in chronic conditions, led by Type 2 Diabetes (529 trials), Breast Cancer (388), and Hypertension (338).
- Operational Success: The overall completion rate for trials is 76.75%, while 9.38% are terminated early.

**Managerial Implications**
The analysis highlights "Transitional Phases" as critical decision points for managers. While Phase 4 trials have a high completion rate of 82.3%, transitional stages like Phase 1/Phase 2 (54.0% completion) and Phase 2/Phase 3 (64.3% completion) carry the highest risk of failure. This underscores the need for enhanced evaluation and resource allocation during these intermediate stages.

**Technologies Used**
- Python: Primary language for data processing and analysis.
- Libraries: pandas for data manipulation, and matplotlib and seaborn for visualization.
- Environment: Google Colab / Jupyter Notebook.


_A presentation summarizing key findings is included in this repository: Clinical_Trial_R.ppxt_

--------------------------------------------------------------------------------
Author: Shantelle Richardson
