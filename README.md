# SkillCraft Technology - Data Science Internship: Task 03

This repository contains the work for the third task of the SkillCraft Technology Data Science Internship.

📝 Project Description

The goal of this task was to build a decision tree classifier to predict whether a customer would subscribe to a bank's term deposit. The model was trained on the UCI Bank Marketing dataset, using customer demographic and behavioral data to make predictions. The project involved data preprocessing, model training, evaluation, and visualization of the results and key data insights.

📊 Visualizations

Here are the key charts and diagrams generated from the analysis:

1. Decision Tree Visualization This detailed flowchart is a direct representation of the "rules" the model learned.
You read it from the top (root node), which asks the single most important question.
Each branch represents an answer to that question, splitting the data into groups.
This process repeats until a final leaf node is reached, which provides the model's final prediction ('Yes' or 'No') for that specific customer profile.
<img width="963" height="581" alt="image" src="https://github.com/user-attachments/assets/dd6ed4ae-7ed1-4743-b866-adc4917b3211" />

2. Confusion Matrix Heatmap This 2x2 grid provides a clear and concise breakdown of the model's prediction accuracy on the test data.

Top-Left (True Negative): Correctly predicted 'No'.

Bottom-Right (True Positive): Correctly predicted 'Yes'.

Top-Right (False Positive): Incorrectly predicted 'Yes' (it was 'No').

Bottom-Left (False Negative): Incorrectly predicted 'No' (it was 'Yes').

This visualization is essential for understanding not just the model's accuracy, but the types of errors it makes.
<img width="445" height="383" alt="image" src="https://github.com/user-attachments/assets/b32eef78-2c4c-4005-ac16-0921d437f6ae" />

🛠️ Tools & Libraries Used

    Pandas (for data loading and manipulation)
    Scikit-learn (for building and evaluating the decision tree model)
    Matplotlib & Seaborn (for plotting standard visualizations)
    Jupyter Notebook/Python (as the development environment)
