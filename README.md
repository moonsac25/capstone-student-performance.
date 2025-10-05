Capstone Project: AI & Student Performance Analysis

📌 Project Overview

This project analyzes how student habits and lifestyle factors (study hours, sleep, AI usage, social media, etc.) influence academic performance.
We use **Exploratory Data Analysis (EDA)** to uncover patterns, and **IBM Granite AI models** for classification and summarization tasks.

The project demonstrates how AI can support insights into student behavior and academic outcomes.

📊 Dataset

Source: [Student Habits and Academic Performance - Kaggle](https://www.kaggle.com/datasets/aryan208/student-habits-and-academic-performance-dataset)

The dataset contains 31 columns with demographic, behavioral, and academic attributes, such as:

* Study hours per day
* Sleep hours
* Social media usage
* Attendance percentage
* Stress level, motivation level, exam anxiety
* Exam score (numeric target variable)

🛠️ Workflow

1. Data Upload & Cleaning

   * Load dataset (CSV/ZIP) into Google Colab.
   * Handle data types and missing values.

2. Exploratory Data Analysis (EDA)

   * Distribution of exam scores.
   * Creation of performance categories (High, Medium, Low).
   * Correlation analysis of numeric features.
   * Boxplots for categorical features (e.g., gender vs exam score).

3. AI Model Integration (IBM Granite)

   * Classification: Predict student performance category based on habits.
   * Summarization: Generate natural language insights and recommendations from dataset statistics.

4. Insights & Findings

   * Study hours, sleep, and social media usage strongly correlate with exam performance.
   * Students who study >3 hours/day perform better on average.
   * Sleep deprivation (<6 hours) negatively affects exam scores.
   * Moderate AI usage in study correlates with more consistent performance.

5. Recommendations

   * Encourage balanced study habits (≥3 hours daily, with enough sleep).
   * Promote awareness of healthy screen/social media usage.
   * Provide guided AI-assisted study resources for students.

🤖 AI Support

The IBM Granite model (via Replicate API) was used for:

* Classification: Mapping raw student behavior data into performance categories.
* Summarization: Producing concise textual insights and recommendations.

 📂 Repository Contents

* `capstone_student_performance.ipynb` → Google Colab Notebook with full workflow.
* `README.md` → Project documentation.
* `slides/` → Project presentation slides (PDF/Google Slides).
* `data/` → (not included, link provided instead).

🚀 How to Run

1. Open `capstone_student_performance.ipynb` in Google Colab.
2. Upload dataset (CSV/ZIP).
3. Insert your Replicate API Token.
4. Run cells sequentially (EDA → Classification → Summarization).

