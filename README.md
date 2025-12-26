# Online-Class-Engagement-Duration-Analysis

# Project Objective:
The main goal of this project is to:
Measure engagement duration of students in online classes
Analyze how factors like attendance, camera usage, questions asked, and quiz scores affect engagement
Visualize engagement patterns using graphs and heatmaps
Provide meaningful insights that can help improve online learning effectiveness

## 🧠 Key Concepts Used:
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Engagement Ratio Calculation
Correlation Analysis
Data Visualization
Interactive UI using Gradio

### 🛠️ Technologies & Libraries Used:
Python
Pandas – data manipulation and analysis
NumPy – numerical operations
Matplotlib – basic plotting
Seaborn – advanced statistical visualizations
Gradio – interactive web-based UI
Google Colab – development environment

#### 📂 Dataset Description:
The dataset contains information about students attending online classes, including:
student_id – Unique student identifier
subject – Subject name
actual_time – Time spent in class (in minutes)
present – Attendance status (Yes/No)
camera_on – Camera usage (Yes/No)
questions_asked – Number of questions asked
quiz_score – Quiz performance score

##### 📐 Engagement Metric:
Engagement Ratio is calculated as:
Engagement Ratio = Actual Time Spent / Total Class Duration
This ratio helps standardize engagement levels between 0 and 1.

###### 📊 Visualizations Included:
Student-wise average engagement (Bar Chart)
Subject-wise engagement comparison
Engagement distribution (Histogram)
Attendance vs Engagement (Box Plot)
Camera ON vs Engagement (Box Plot)
Questions aske vs Engagement (Scatter Plot)
Quiz score vs Engagement (Scatter Plot)
Student vs Subject Engagement Heatmap

####### 🖥️ Interactive UI (Gradio):
The project also includes a Gradio-based UI that allows users to:
Upload a CSV dataset
View automated analysis results
See generated plots and heatmaps instantly
This makes the project more user-friendly and interactive.

📌 Insights Derived
Students with camera ON tend to have higher engagement
Attendance has a strong positive impact on engagement
Higher quiz scores and questions asked correlate with better engagement
Certain subjects show consistently higher engagement levels
