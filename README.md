# NFL_FieldPredictor

Basic SVM-SVC field predictor written to see the relationship between QB passer rating of the game, and final game points VS if the game was played in the home field or away. 

### Tools and Data
It was created using tools from pandas, numpy, and sklearn. <br>The CSVs were downloaded from:<br>
<p>&nbsp https://www.kaggle.com/speckledpingu/nfl-qb-stats</p>

### Results
I was surprised by the results I got because there was no correlation between the types of data that I was testing. The probability was like flipping a coin (~50%). 
It was definitely better with two parameters (QB passer rating, and final points of the game) than just one parameter (QB passer rating)
