# AI-ML-internship-Program-

📊 Machine Learning Project Report
🔹 Task 1: Exploratory Data Analysis (EDA) on Iris Dataset
📌 Objective

To explore and understand the structure of the dataset using statistical analysis and visualizations.

📂 Dataset Used
Iris Dataset (loaded via Seaborn)
⚙️ Work Performed
Loaded dataset using pandas
Checked dataset structure using .shape, .head(), .info(), and .describe()
Performed statistical summary and feature inspection
Visualized data using:
Scatter plots
Histograms
Box plots
Pair plots
📈 Key Insights
Dataset contained no missing values and was clean
Petal length and petal width provided strong class separation
Setosa species was easily distinguishable from others
Visualization helped reveal clear relationships between features
🔹 Task 2: Short-Term Stock Price Prediction
📌 Objective

To predict the next day’s closing stock price using historical market data.

📂 Dataset Used
Apple stock data using yfinance
⚙️ Work Performed
Collected historical stock data using API
Created target variable using shifted closing prices
Selected features: Open, High, Low, Volume
Split dataset using time-based splitting
Trained a Random Forest Regressor model
Evaluated predictions using performance metrics
Visualized actual vs predicted prices
📊 Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
📈 Key Insights
Model successfully followed overall market trends
Predictions were reasonably close but not exact due to volatility
Random Forest handled non-linear patterns effectively
Stock market randomness limits perfect prediction accuracy
🔹 Task 4: General Health Chatbot (LLM-based Assistant)
📌 Objective

To build a conversational chatbot that answers general health-related queries using a large language model with prompt engineering and safety constraints.

⚙️ Work Performed
Built a Python-based chatbot using OpenAI API
Designed a structured system prompt using RTCF framework (Role, Task, Constraints, Format)
Implemented conversation memory to maintain context
Added safety filter to detect sensitive or emergency-related queries
Restricted model from giving medical diagnosis or prescriptions
Created interactive command-line chatbot interface
🛡️ Safety Handling
Detects critical keywords (e.g., emergency, overdose, severe pain)
Redirects users to seek professional medical help
Avoids medical diagnosis and unsafe advice
📈 Key Insights
Prompt engineering significantly improves response quality
Memory-based chat enhances conversational flow
Safety filters are essential for healthcare-related AI systems
LLMs are effective for general awareness but not medical decision-making
🔹 Overall Learning Outcomes

Through these tasks, I developed practical skills in:

Exploratory Data Analysis (EDA)
Data preprocessing and feature understanding
Machine learning model training and evaluation
Time-series prediction basics
Prompt engineering for LLMs
Building safe AI chatbot systems
Data visualization for insights
