# 💊 MMTP: Methadone Maintenance Treatment Program
Python | Exploratory Data Analysis | Data Visualization

<p align="center">
  <img src="https://github.com/user-attachments/assets/32603387-a431-4a7e-84a7-a62cf0e1434e" 
       alt="icon" 
       width="200" />
</p>

**Developed a Python-based clinical tracking system to analyze methadone dosage patterns and patient retention in Opioid Use Disorder treatment, identifying retention trends to support data-driven clinical decision-making.**

## 🎯 Research Question
**Which treatment and dosage patterns are associated with patient retention in Methadone Maintenance Therapy Programs?**

## 🛠 Tech Stack
- **Python**
- **Pandas** (Data Manpulation and aggregation)
- **NumPy** (Numerical Operations)
- **Matplotlib / Seaborn** (Visualization)

## 🗂 Dataset
- Simulated Methadone Maintenance Treatment dataset 
- **Sample Size**: 110 Patient records
- **Key Variables**: 
  -  Patient ID
  -  name
  -  sex
  -  age
  -  race
  -  previous_opioid_use
  -  duration_previous_opioid_use
  -  date_of_service
  -  methadone_dose_mg

## 🧹 Data Preparation & Validation
- Performed manual validation to ensure data accuracy and consistency
- Confirmed dosage categorization and verified retention duration calculations
- Preserved irregular visit intervals to reflect realistic treatment engagement patterns

## 📊 Analysis & Methods 
- Performed descriptive statistical analysis of dosage distribution and retention rates
- Conducted comparative analysis of demographic variables (age, gender) and prior opioid history versus retention outcomes
- Evaluated correlations between methadone dosage category and treatment retention
- Aggregated patient records to compute summary retention metrics 
- Visualized analytical results using Matplotlib and Seaborn

## 🔍 Key Findings 
- **Higher doses** of methadone are associated with **improved treatment retention rates**
- **Older patients** demonstrated **higher retention rates** compared to younger patients
- The majority of patients (64/110) were prescribed low-dose methadone (<45 mg), reflecting a cautious prescribing approach
- Females had slightly higher retention rates than males; however, the difference was not statistically significant

## 💡 Interpretation
- The association between a high-dose methadone suggest that dosage category and early treatment stability may influence patient retention outcomes
- Low retention among younger patients may indicate differing engagement barriers or treatment adherence patterns across age groups.
- The prevalence of low-dose prescribing suggests a conservative, cautious initial dosing strategy within the dataset
- The lack of significant gender difference indicates retention outcomes may be more strongly influenced by other treatment variables than by sex alone

## 🚀 Actionable Insight 
- Enhanced monitoring and engagement strategies during early treatment phases may improve retention outcomes, particularly for younger patients
- Retention-focused interventions may be more effectively targeted by age group rather than by gender.

## ⚠️ Limitations
- Dataset was manually constructed, limiting scalability and real world variability
- Small sample size (n=110) restricts generalizability
- Limited demographic diversity (e.g. age, race, prior opioid use)
- Short timeframes limits long term retention analysis

## 📊 Clinical Outcome Analysis & Visualizations

### Higher doses of methadone are associated with improved treatment retention rates
<img src="https://github.com/user-attachments/assets/86a6bf0d-f828-499b-a1bf-4463e0db692c" alt="icon" width="500" />

### Retention Trends by Methadone Dose Category Over Time
<img src="https://github.com/user-attachments/assets/14a7de9a-76fe-4bd2-8a6c-801157031196" alt="icon" width="500" />


### Older Age Groups Show Greater Retention Stability
<img src="https://github.com/user-attachments/assets/361f4ab4-ec32-4dd5-aee4-dd146406b9a6" alt="icon" width="500" />


### Distribution of Methadone Dose Categories by Sex
<img src="https://github.com/user-attachments/assets/0e6ed888-938f-4ee4-823b-e912231afa01" alt="icon" width="500" />


