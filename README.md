# User Interests Analysis & Recommendation System

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![pandas](https://img.shields.io/badge/pandas-✔-brightgreen)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-✔-orange)

A Python project that generates synthetic user data, analyzes interest distributions, checks statistical dependencies, and provides a simple recommendation system.

## 📌 Features

- **Synthetic Data Generation**: Creates 100 fake users with names, ages, interests, and activities.
- **Data Preprocessing**: Converts interests into binary features for analysis.
- **Visualizations**: Plots interest distributions and recommendation trends.
- **Statistical Analysis**: Uses chi-square tests to find correlations between interests.
- **Basic Recommender**: Suggests activities based on user interests.

## ⚙️ Technologies

- **Python 3.x**
- **Libraries**:
  - `pandas`, `numpy` (data handling)
  - `Faker` (fake data generation)
  - `seaborn`, `matplotlib` (visualizations)
  - `scipy` (chi-square test)
  - `scikit-learn` (cosine similarity _[unused in current version]_)

## 🚀 Quick Start

1. **Install dependencies**:

   ```bash
   pip install pandas numpy faker seaborn matplotlib scipy scikit-learn


   Run the script (e.g., in Jupyter Notebook or a Python file).
   Check the visualizations and results in the console.
   ```

📂 Project Structure
+-------------------------------------------------------+
|                Personalized Content Generator         |
+-------------------------------------------------------+
                               |
       +-----------------------------------------------+
       | 1. Import Libraries & Setup                  |
       +-----------------------------------------------+
                               |
       +-----------------------------------------------+
       | 2. Generate Synthetic User Data               |
       | - User profiles with attributes               |
       | - Interests, activity logs                    |
       +-----------------------------------------------+
                               |
       +-----------------------------------------------+
       | 3. Data Preprocessing & Analysis             |
       | - Convert interests to one-hot               |
       | - Exploratory data analysis                  |
       | - Visualize distributions                     |
       +-----------------------------------------------+
                               |
       +-----------------------------------------------+
       | 4. Statistical Analysis (Chi-Square)         |
       | - Test distribution significance             |
       +-----------------------------------------------+
                               |
       +-----------------------------------------------+
       | 5. Recommendation Engine                     |
       | - Compute user similarity                     |
       | - Generate personalized suggestions          |
       +-----------------------------------------------+
                               |
       +-----------------------------------------------+
       | 6. Visualization                             |
       | - Visualize recommended interests            |
       | - User interest heatmaps                      |
       +-----------------------------------------------+
                               |
       +-----------------------------------------------+
       | 7. Conclusions & Next Steps                  |
       +-----------------------------------------------+

🔧 Potential Improvements
Add more detailed user features (age, activity level, time patterns).
Enhance the recommendation system by using cosine similarity to find similar users.
Add functionality to save results to a file or database.

Author
[Illia Andriienko]
