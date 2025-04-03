Project Description
This project analyzes COVID-19 trends using data science and machine learning. It explores the impact of testing, vaccination, and government policies while predicting future cases.

📂Dataset Used
📄 StatewiseTestingDetails.csv – Testing Data

📄 covid_19_india.csv – COVID-19 Cases Data

📄 covid_vaccine_statewise.csv – Vaccination Data

⚙️ Tools & Technologies
🐍 Python (pandas, numpy, seaborn, matplotlib, sklearn, plotly)

🤖 Machine Learning (RandomForestRegressor)

📊 Data Visualization (Matplotlib, Seaborn, Plotly)

🖥 Jupyter Notebook / VS Code

🚀 Project Setup & Execution
1️⃣ Install Required Libraries
Run the following command:

bash
Copy
Edit
pip install -r requirements.txt
2️⃣ Download the Dataset
Ensure all dataset files are stored in the data/ directory.

3️⃣ Run the Jupyter Notebook
Execute the project step-by-step using:
open : jupyter notebook
Or if using a Python script:
python main.py

📊 Project Workflow
1️⃣ Data Preprocessing

Convert date formats.

Handle missing values.

Convert categorical data into numerical format.

2️⃣ Exploratory Data Analysis (EDA)

Visualize state-wise COVID-19 impact.

Analyze vaccine distribution effectiveness.

Study the effect of lockdown policies.

3️⃣ Feature Engineering

Calculate positivity, recovery, and fatality rates.

Normalize data using MinMaxScaler.

4️⃣ Model Training & Prediction

Train RandomForestRegressor to predict COVID-19 cases.

Evaluate using MAE, MSE, R² score.

5️⃣ Visualization & Insights

State-wise COVID impact (bar charts).

Vaccine distribution (horizontal bar chart).

Policy impact (line chart).

📌 Key Results & Insights
The recovery rate improved over time, but some states lagged.

Lockdown policies significantly reduced case growth.

Vaccine rollout was uneven across states.

 Future Improvements
✅ Improve prediction accuracy using deep learning.
✅ Integrate real-time COVID-19 data API.
✅ Enhance visualizations with interactive dashboards.

📚 References
COVID-19 India Dataset (Kaggle)

Scikit-Learn Documentation

