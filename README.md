# Student Depression Analysis

A comprehensive data analysis project examining factors associated with depression among students and working professionals. This project uses exploratory data analysis and visualization techniques to identify patterns and correlations between lifestyle factors, academic pressure, and mental health.

## Problem Statement

Mental health, particularly depression, is a growing concern among students and young professionals. This analysis aims to understand:
- Which factors are most strongly associated with depression?
- How do lifestyle choices (sleep, diet, work hours) affect mental health?
- What patterns exist across different demographics and professions?

## Dataset Description

The analysis uses the **Student Depression Dataset** containing 27,901 records with the following features:

- **Demographics**: Gender, Age, City, Profession
- **Academic Factors**: Academic Pressure, CGPA, Study Satisfaction, Degree
- **Work-Related**: Work Pressure, Job Satisfaction, Work/Study Hours
- **Lifestyle**: Sleep Duration, Dietary Habits
- **Mental Health**: Depression status, Suicidal thoughts, Family History of Mental Illness
- **Financial**: Financial Stress

## Tools and Technologies

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **matplotlib** - Data visualization
- **seaborn** - Statistical graphics

## Key Analysis Steps

1. **Data Loading and Exploration**
   - Loaded dataset with 27,901 entries and 18 columns
   - Examined data structure and column types

2. **Demographic Analysis**
   - Gender distribution visualization
   - Age-wise depression patterns

3. **Profession and Depression**
   - Analyzed depression rates across different professions
   - Students showed lower rates (58.5%) compared to other professions

4. **Academic Pressure Impact**
   - Examined relationship between academic pressure levels (0-5) and depression
   - Higher pressure levels (3-5) showed more depression cases

5. **Lifestyle Factors**
   - Sleep duration patterns
   - Work/study hours analysis
   - Dietary habits distribution

6. **Mental Health Indicators**
   - Study satisfaction correlation
   - Financial stress impact
   - Family history of mental illness
   - Suicidal thoughts prevalence

## Key Insights

- **Age Factor**: Depression is highest among younger individuals (18-34 years) and drops significantly after age 35

- **Sleep Duration**: People sleeping more than 8 hours show lower depression rates, while those sleeping less than 5 hours have higher rates

- **Work/Study Hours**: Depression increases with longer work or study hours

- **Financial Stress**: Higher financial stress levels are strongly linked to depression

- **Dietary Habits**: Unhealthy dietary habits correlate with higher depression rates, while healthy eating habits show lower depression prevalence

- **Study Satisfaction**: Lower to medium satisfaction levels are associated with more depression cases

- **Family History**: Individuals with a family history of mental illness are more likely to experience depression

- **Profession**: Students have relatively lower depression rates (58.5%) compared to other professions like Doctors, Lawyers, and Managers (100%)

## How to Run the Project

### Prerequisites

Ensure you have Python 3.x installed along with the required libraries.

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/student-depression-analysis.git
cd student-depression-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Place the dataset file `Student Depression Dataset.csv` in the project directory

4. Run the Jupyter Notebook:
```bash
jupyter notebook Dipression_1766829134.ipynb
```

## Project Structure
```
student-depression-analysis/
│
├── Dipression_1766829134.ipynb    # Main analysis notebook
├── Student Depression Dataset.csv  # Dataset file
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
└── .gitignore                      # Git ignore file
```

## Results and Visualizations

The notebook includes several visualizations:
- Bar charts for profession-wise depression rates
- Heatmaps showing relationships between lifestyle factors and depression
- Line plots for age-related patterns
- Pie charts for dietary habit distribution

