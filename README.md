# Mental Health Analysis Project

This project explores a dataset containing mental health indicators to identify patterns and build predictive solutions.

## Dataset Overview

The dataset (`data/Mental Health Dataset.csv`) includes features such as:
- **Demographics:** Gender, Country, Occupation, Self-employment status.
- **Mental Health Indicators:** Family history, previous treatment, mental health history, mood swings.
- **Behavioral Patterns:** Days spent indoors, growing stress, changes in habits, coping struggles, work interest, social weakness.
- **Professional Context:** Mental health interviews, awareness of care options.

## Potential Solutions & Use Cases

### 1. Predictive Analysis (Machine Learning)
*   **Treatment Prediction:** Build a model to predict whether someone is likely to seek mental health treatment based on their `family_history`, `Occupation`, and `Mental_Health_History`.
*   **Stress & Habit Analysis:** Predict `Growing_Stress` or `Changes_Habits` using features like `Days_Indoors` and `Occupation`.
*   **Mood Swing Classifier:** Use behavioral indicators (`Coping_Struggles`, `Social_Weakness`, `Work_Interest`) to classify the severity of `Mood_Swings`.

### 2. Workplace Mental Health Dashboard
*   Create an interactive dashboard (using Streamlit or Dash) to visualize:
    *   The correlation between Occupation and stress levels.
    *   Global trends in mental health awareness across different Countries.
    *   How Work_Interest and Social_Weakness vary by gender and self-employment status.

### 3. "Check-In" Recommendation Tool
*   Develop a logic-based tool that takes user input and provides a "Mental Health Snapshot," suggesting whether they should explore available care options or seek a mental health interview.

### 4. Behavioral Research Analysis
*   Perform a statistical deep dive into the "Indoors Effect": Analysis of how the number of days spent indoors impacts coping struggles or mood swings.
