LAB 1: Welcome to Machine Learning
Student Information:

Name: Tanni Akther
ID: 20245103081
Course: Machine Learning Laboratory (BUBT)
📌 Problem Idea
The primary objective of this project is to explore foundational machine learning concepts through exploratory data analysis (EDA). We examine various behavioral and academic factors—such as daily study hours, sleep patterns, class attendance, and auxiliary habits—to identify hidden correlations and evaluate student academic outcomes (pass/fail performance).

📊 Current Dataset Status
The dataset utilizes a structured, introductory sample containing records of multiple students. It serves as a practical baseline for executing NumPy array manipulations, Pandas DataFrame filtering, statistical summarization, and verifying model reproducibility through controlled random seeding.

🛠️ Lab Activities Overview
1. Activity A — Meet the Notebook
Task: Created a Python notebook, added Markdown cells for title, student info, and objectives, and tested basic print statements.
Error Analysis Insight: Experimented with an unclosed quotation mark to observe syntax errors, which helped identify how precise the Python parser is regarding string literal boundaries.
2. Activity B — NumPy: The Array Gym
Operations Performed:
Calculated minimum marks and standard deviation using NumPy.
Applied vectorized operations to add bonus marks (+5) without altering the original array.
Counted passing students using conditional array indexing.
Reshaped a 1D marks array into a 
2
×
3
 matrix.
3. Activity C — Pandas: The Dataframe Detective
Data Analysis & Findings:
Features: study_hours, sleep_hours, attendance, snacks
Label: passed
Dataset Scope: 6 samples and 6 columns.
Filtering & Sorting: Filtered students with at least 80% attendance and sorted records in descending order of attendance.
Causation vs. Correlation: Analyzed that a tiny dataset showing correlations (e.g., snack purchases vs. failure) does not prove causation; it is merely an exploratory clue rather than concrete proof.
4. Activity D — Reproducibility Experiment
Experiment Findings: Evaluated seeded (random.seed(42) / np.random.seed(42)) versus unseeded runs. Demonstrated that seeded executions yield identical, reproducible outputs, which is vital for fair model comparisons across different groups.
🚀 How to Run the Notebook
Open the repository and locate the notebooks/ML_Lab01_050_Mim.ipynb file.
Open it in Google Colab.
Run the code cells sequentially to view dataframes, statistical summaries, and filtering results.
📝 Statement of Results
Note: All results presented in this lab are preliminary and intended strictly for educational demonstration and foundational exploratory data analysis.
