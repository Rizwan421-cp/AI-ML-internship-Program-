# AI-ML-internship-Program-


🔹 Task 1: Exploring and Visualizing a Dataset
📌 Objective

To gain an understanding of the dataset by performing data inspection, statistical analysis, and visualization.

📂 Dataset Used
• Iris Dataset (loaded using seaborn)

⚙️ Work Performed
• Loaded dataset using pandas
• Explored dataset structure using .shape, .head(), .info(), .describe()
• Analyzed feature distributions and relationships
• Created visualizations:
o Scatter plots
o Histograms
o Box plots
o Pairplot

📈 Key Findings
• Dataset was clean with no missing values
• Petal features showed strong separation between species
• Setosa species was clearly distinguishable while others had slight overlap
• Visualizations helped in identifying patterns and relationships effectively



🔹 Task 2: Stock Price Prediction (Short-Term)
📌 Objective

To predict the next day’s closing stock price using historical market data.

📂 Dataset Used
• Stock market data fetched using yfinance (Apple stock)

⚙️ Work Performed
• Retrieved historical stock data using API
• Created target variable (Next_Close) using shifting technique
• Selected features: Open, High, Low, Volume
• Applied time-based train-test split
• Trained Random Forest Regressor model
• Generated predictions and visualized results

Evaluation Metrics
• Mean Absolute Error (MAE)
• Mean Squared Error (MSE)
• R² Score

📈 Key Findings
• Model successfully captured overall market trends
• Predictions were close to actual values with minor deviations
• Random Forest handled non-linear relationships effectively
• Market volatility limits perfect prediction accuracy


🔹 Task 4: General Health Query Chatbot (Prompt Engineering Based)
📌 Objective

To build a chatbot that answers general health-related questions using an LLM with proper prompt engineering and safety handling.

⚙️ Work Performed
• Built a Python-based chatbot using OpenAI API
• Designed a system prompt using RTCF framework (Role, Task, Constraints, Format)
• Implemented conversation history for context retention
• Added safety filter to detect sensitive or emergency-related queries
• Restricted chatbot from giving medical diagnosis or prescriptions
• Developed an interactive command-line chatbot interface

📈 Key Findings
• Prompt engineering improved response clarity and behavior
• Conversation memory helped maintain context in dialogue
• Safety filtering reduced risk of harmful responses
• Model is effective for general awareness but not medical diagnosis

🔹 Overall Learning
Through these tasks, I gained hands-on experience in:
• Data preprocessing and exploratory data analysis
• Data visualization and pattern recognition
• Machine learning model training and evaluation
• Time-series based prediction
• Prompt engineering for LLMs
• Building safe and controlled AI chatbots
