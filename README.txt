User Interests Analysis & Recommendation System
Project Description
This project generates synthetic user data with their interests and activities, analyzes the distribution of interests, checks for statistical dependencies between interests, and implements a simple interest-based recommendation system.

Key Features
Generation of 100 users with fake names, ages, lists of interests, and activities.

Conversion of interests into binary features for easier analysis.

Visualization of interest distribution.

Statistical analysis of relationships between interests (chi-square test).

A basic recommender suggesting activities based on user interests.

Visualization of recommendation distribution across categories.

Technologies & Libraries Used
Python 3.x

pandas

numpy

Faker

seaborn

matplotlib

scipy

scikit-learn (though cosine_similarity is imported, it is not directly used)

Code Structure
Importing libraries and setting up the environment.

Generating synthetic user data.

Data transformation and interest visualization.

Statistical analysis of interest dependencies (chi-square test).

Interest-based recommendation system.

Visualization of recommendation distribution.

How to Run the Project
Install the required libraries:

bash
pip install pandas numpy faker seaborn matplotlib scipy scikit-learn  
Run the script (e.g., in Jupyter Notebook or a Python file).

Check the visualizations and results in the console.

Potential Improvements
Add more detailed user features (age, activity level, time patterns).

Enhance the recommendation system by using cosine similarity to find similar users.

Add functionality to save results to a file or database.