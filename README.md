# FantasyFootballProject

Fantasy Football Model Using Past Years To Predict Future Scores (PPR Scoring Format)

Model takes input of past years' stats and outputs predicted average points per game for the following season. TensorFlow is used for the machine learning aspects and BeautifulSoup is used to pull the data from the FantasyPros website.

Abstract:

For the past four years, I had missed the playoffs in my fantasy football league. The other members of my league would not let me forget this for even a moment. I wanted to find a way to use my new knowledge of coding to remedy this cycle of losses.
After reading about the creation of WalterPicks, an app that provides sports insights using machine learning and AI, I was inspired to create my own machine learning algorithm to predict fantasy football scores using data from previous seasons.
In this talk, I will discuss how we automated the data collection process, the details of feature selection, the model used, and how we trained, tested, and tuned the model. 
For the 148 players overall, the model overprojected points per game by an average of 2.4225.
Thanks to the software I created (and maybe a little bit of luck), I ended up winning my fantasy football league.

Accuracy:

The model overprojected points for quarterbacks by an average of 2.233301 in a sample set of 26 players. The model overprojected points for running backs by an average of 1.079124 in a sample set of 38 players. The model overprojected points for wide receivers by an average of 3.15299322 in a sample set of 63 players. The model overprojected points for tight ends by an average of 2.896139 in a sample set of 21 players.

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
