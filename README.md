 # Own Dataset Creation and  Titanic Dataset Analysis (Google Colab)

## Project Overview
This project explores the famous Titanic dataset using **pandas only** in Google Colab.  
It demonstrates a complete data analysis workflow:
1. Uploading and exploring the dataset
2. Cleaning missing values
3. Analyzing survival patterns
4. Filtering subsets of passengers
5. Summarizing insights

The notebook is structured step‑by‑step for clarity and reproducibility.

---

##  Requirements
- Python 3.x
- Google Colab (or Jupyter Notebook)
- pandas library

---

##  Workflow

### Part 1: Custom Dataset
- Upload and explore a small  dataset (practice exercise).

### Part 2: Titanic Dataset
- **Step 1: Exploration** → `.head()`, `.info()`, `.describe()`  
- **Step 2: Data Cleaning** → handle missing values (`Age`, `Embarked`), drop `Cabin`, remove duplicates  
- **Step 3: Data Analysis** → survival rates by gender, class, age groups  
- **Step 4: Filtering** → subsets for females, children, and first‑class survivors  
- **Step 5: Insights** → summarize findings clearly

---

## Key Insights
- **Gender**: Women had a much higher survival rate than men.  
- **Class**: First‑class passengers were more likely to survive than second or third class.  
- **Age**: Children (under 12) had better survival chances.  
- **Combination**: Female passengers in 1st class had the highest survival probability.

---

##  Repository Contents
- `task3.ipynb` → Main notebook with analysis
- `Titanic-Dataset.csv` → Dataset file (must be uploaded or placed in repo)

---

##  How to Run
1. Open the notebook in Google Colab (link included in repo).  
2. Upload `Titanic-Dataset.csv` when prompted.  
3. Run cells step‑by‑step to reproduce the analysis.  

---

## Constraints
- Used **pandas only**  
- Clean, readable code  
- Proper handling of missing values

