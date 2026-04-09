# 🚦 Smart Traffic Analytics: AI-Powered Mobility Insights

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mounibwassim/University-Projects/tree/main/Smart-Traffic-Analytics)

## 🎯 Objective
This project focuses on identifying patterns in urban traffic congestion and predicting traffic situations using advanced machine learning. By analyzing real-world datasets, the goal was to build robust models that can assist in smart city planning and real-time mobility optimization.

## 🛠️ Tools & Technologies
*   **Languages**: Python 3.10+
*   **Libraries**: scikit-learn (Random Forest, Logistic Regression), pandas, NumPy, Seaborn, Matplotlib.
*   **Platform**: Google Colab / Jupyter Notebooks

## 📊 Comprehensive Road Traffic Analysis
The project is divided into three specialized analytical workflows:

### 1. [US Traffic Congestion Analysis (2016-2022)](./1G_G9_Dataset1.ipynb)
*   **Problem**: Analyzing large-scale historical traffic events across the US to identify significant delay factors.
*   **Solution**: Implemented a Random Forest model focusing on environmental and temporal features.
*   **Key Insight**: Identified that regional weather severity had a lower impact on congestion durations than road-specific occupancy levels.

### 2. [Smart City Mobility AI](./1G_G9_Dataset2.ipynb)
*   **Problem**: Predicting traffic conditions (High/Medium/Low) based on sensor data and social sentiment.
*   **Solution**: Processed IoT-ready data including vehicle counts, speed, and sentiment scores using ensemble learning.
*   **Key Insight**: Achieved high precision by integrating non-traditional features like ride-sharing demand and parking availability.

### 3. [Predictive Traffic Situations](./1G_G9_Dataset3.ipynb)
*   **Problem**: Classifying real-time traffic levels (Normal, High, Heavy, Low) for proactive routing.
*   **Solution**: Developed a classification pipeline utilizing balanced vehicle counts (Cars, Bikes, Buses, Trucks).
*   **Key Insight**: Temporal features (Hour of day and Day of week) emerged as the most critical predictors for "Heavy" traffic states.

## 📈 Results & Impact
*   **Accuracy**: Achieved over **95% accuracy** across major classification tasks using optimized Random Forest parameters.
*   **Feature Importance**: Proved that **Vehicle Count** and **Road Occupancy** are the leading indicators for smart mobility management.
*   **Deliverable**: [Project Presentation Slides](./Presentation%20Slides.pdf) summarizing methodology and strategic recommendations.

## 🚦 How to Run
1.  Navigate to the [Smart-Traffic-Analytics](https://github.com/mounibwassim/University-Projects/tree/main/Smart-Traffic-Analytics) folder on GitHub.
2.  Click on any `.ipynb` file.
3.  Click the **"Open in Colab"** badge at the top to run the code interactively.
