# Team mint – Data Cleaning/EDA/Insights

## 📌 Project Overview
This project consists of a Python notebook developed by **Team mint** to perform:
- Data cleaning  
- Abstract exploratory data analysis (EDA)  
- Statistical and clustering analyses  

The notebook explores factors influencing employer attractiveness, perceptions, and student motivations using survey data. Insights from analysis to answer the problem statement is located in the google doc report.

---

## ⚙️ Environment Setup

This notebook is designed to be run in **Google Colab**.

### Requirements
- Google account  
- Internet connection  
- Google Colab  

No local environment setup is required.

---

## ▶️ How to Run the Notebook & Reproduce Results

1. Open **Google Colab**:  
   https://colab.research.google.com

2. Upload the notebook file:
   - Click **File → Upload notebook**
   - Upload the provided `.ipynb` file

3. Run the notebook:
   - Click **Runtime → Run all**
   

4. Ensure that:
    -  The original dataset is loaded in your google drive (/content/drive/MyDrive)
   - All cells are executed in order  
   

This will reproduce:
- Data preprocessing  
- Statistical analyses  
- Visualizations  
- Clustering results  
- Feature importance results  

---

## 📊 Key Insights & Findings

### 1. Redundancy Analysis

| Category | Related Columns |
|----------|----------------|
| Money | Compensation and Benefits, Motivation: Compensation |
| Growth | Career Progression and Development, Motivation: Career Growth Opportunities |
| Culture | Work-life Balance and Culture, Motivation: Work-life balance |

These questions are essentially asking the same concept in different ways.  
While similar results may reinforce conclusions, differing results can create ambiguity and make it difficult to identify the true deciding factor for individuals.

---

### 2. Correlation Analysis

Perception and attractiveness are highly correlated in the dataset.  
This resembles the **Halo Effect**, a cognitive bias where overall impressions of a company influence how people judge other attributes of that company.

---

### 3. Feature Importance Analysis

- Perception plays a dominant role in determining employer attractiveness.
- Employer reputation and image often outweigh objective benefits.
- Even with strong benefits, poor perception can significantly reduce attractiveness.

This reflects a modern workforce mindset:
- Compensation remains important, but it no longer outweighs the desire for:
  - Growth  
  - Meaning  
  - Well-being  

Compared to previous generations, young adults are less motivated by “staying for higher pay” and more by:
- Personal development  
- Welfare  
- Purposeful work  

Companies should therefore invest in:
- Employee development  
- Skill-building  
- Workplace well-being  
to maintain morale and retention.

---

### 4. Cluster Analysis

#### Implications for Company Branding & Recruitment
- Universal message: **“Meaningful impact”** resonates across all clusters.
- Cluster-specific focus:
  - **Cluster 0 (Mission-driven professionals):**  
    Emphasize technical innovation and societal impact.
  - **Cluster 1 (Business-minded pragmatists):**  
    Highlight career progression and job stability.
  - **Cluster 2 (Wellness-conscious generation):**  
    Promote learning culture and work-life balance policies.

#### Implications for Policy & Student Services
- Mental health support should focus on freshmen, who prioritize wellness most.
- Career services should be:
  - Exploratory for Year 1 students  
  - Placement-oriented for senior students  
- Financial literacy programs should begin from Year 2 onward, as interest in compensation and financial planning increases with age.

---

### 5. Survey Attrition Analysis & Data Segmentation

#### Survey Attrition
- Almost all partial and disqualified responses missed Question 22 (Perception).
- This question required deep personal reflection and forced-choice responses.
- Many respondents likely dropped out because:
  - Their perception did not match predefined options  
  - They wanted a quick survey and disengaged when effort increased  

#### Duration of Completion
- Partial responses: **6.1 minutes (average)**  
- Completed responses: **99.5 minutes (average)**  
- Disqualified responses: **36.8 minutes (average)**  

This suggests:
- Partial responses reflect early disengagement or accidental survey openings  
- Disqualified respondents invested time before failing qualification criteria  

#### User Agent (Device Type)
- Mobile users accounted for:
  - 88–89.5% of partial/disqualified responses  
  - 78.2% of completed responses  

This supports the idea that:
- Mobile environments increase distractions  
- Smaller screens reduce completion likelihood  
However, device type is a contributing factor rather than the primary cause.

#### Qualification Filtering
- The survey targeted only Bachelor’s degree holders.
- Respondents with:
  - Master’s  
  - Doctorate  
  - MBA  
were automatically disqualified.

This created:
- A narrow target demographic  
- Systematic exclusion of overqualified respondents  
- One anomalous Master’s response among partial submissions  

---

## 🧪 Reproducibility Notes
- Always run all cells from top to bottom.
- Do not skip preprocessing steps.
- Ensure the dataset is loaded correctly before analysis cells.
- Running on Google Colab ensures consistent package versions.

---

## 👥 Team mint
Darren Tan Zhi Jie, Low Kan Yui, Wang Jianning, Ryan Lee Han Ping
