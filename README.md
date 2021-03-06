# FantasyFootballProject

Fantasy Football Model Using Past Years To Predict Future Scores (PPR Scoring Format)

Model takes input of past years' stats and outputs predicted average points per game for the following season. TensorFlow is used for the machine learning aspects and BeautifulSoup is used to pull the data from the FantasyPros website.

Accuracy:

The model overprojected points for quarterbacks by an average of 2.233301 in a sample set of 26 players. The model overprojected points for running backs by an average of 1.079124 in a sample set of 38 players. The model overprojected points for wide receivers by an average of 3.15299322 in a sample set of 63 players. The model overprojected points for tight ends by an average of 2.896139 in a sample set of 21 players.

For the 148 players overall, the model overprojected points per game by an average of 2.4225.

Task Of Each File

New_Data webscrapes the data from the FantasyPros website and outputs each player and their stats in a datasheet with separate datasheets for QB, RB, and WR/TE

New_QB_Data creates a model by taking an input of the datasheet with the QB players and using Tensorflow to create the model by splitting the data into training and testing data

New_RB_Data creates a model by taking an input of the datasheet with the RB players and using Tensorflow to create the model by splitting the data into training and testing data

New_WR_Data creates a model by taking an input of the datasheet with the WR players and using Tensorflow to create the model by splitting the data into training and testing data

New_TE_Data creates a model by taking an input of the datasheet with the TE players and using Tensorflow to create the model by splitting the data into training and testing data

2020_QB runs the QB model we have created on the 2020 QB players to predict points for 2021

2020_QB runs the RB model we have created on the 2020 RB players to predict points for 2021

2020_QB runs the WR model we have created on the 2020 WR players to predict points for 2021

2020_QB runs the TE model we have created on the 2020 TE players to predict points for 2021

Results/Predictions can be seen in the 2020 files for each position
