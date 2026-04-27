Overview
This project focuses on predicting the total score of an IPL innings using match and player-level features. A deep learning model built with TensorFlow/Keras is trained on historical IPL data to learn patterns and estimate the final score.
The project also includes exploratory data analysis (EDA) to understand trends like top venues, batsmen, and bowlers.

🎯 Objectives
Predict the final total score of a batting team
Perform EDA on IPL dataset
Build a regression model using neural networks
Apply data preprocessing & feature scaling

📂 Dataset
Contains ball-by-ball IPL match data
Key features include:
Batting team
Bowling team
Venue
Batsman & Bowler
Runs, wickets, overs
Target variable: total runs
🏏 Top batsmen
Based on maximum runs scored
🎯 Top bowlers
Based on wickets taken
🔥 Correlation heatmap
Shows relationships between numerical features

⚙️ Data Preprocessing
Handled categorical variables using Label Encoding
Selected relevant features:
['bat_team', 'bowl_team', 'venue', 'runs', 'wickets', 
 'overs','striker','batsman','bowler']
Feature scaling using:
MinMaxScaler

🤖 Model Architecture
A feedforward neural network was used:
Input layer
Dense layer (512 neurons, ReLU)
Dense layer (216 neurons, ReLU)
Output layer (1 neuron, Linear)
Loss function:
Huber Loss (robust to outliers)

📊 Results
Model successfully learns score patterns
Loss curve visualized using training history

🚀 Tech Stack
Python
TensorFlow
Keras
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
