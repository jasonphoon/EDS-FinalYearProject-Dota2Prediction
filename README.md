# Dota2 Games Results Data Set 

Data Set Information:

Dota 2 is a popular computer game with two teams of 5 players. At the start of the game each player chooses a unique hero with different strengths and weaknesses. The dataset is reasonably sparse as only 10 of 113 possible heroes are chosen in a given game. All games were played in a space of 2 hours on the 13th of August, 2016

URL: https://archive.ics.uci.edu/ml/datasets/Dota2+Games+Results

Attribute Information:

Each row of the dataset is a single game with the following features (in the order in the vector):
1. Team won the game (1 or -1)
2. Cluster ID (related to location)
3. Game mode (eg All Pick)
4. Game type (eg. Ranked)
5. end: Each element is an indicator for a hero. Value of 1 indicates that a player from team '1' 
played as that hero and '-1' for the other team. Hero can be selected by only one player each game. 
This means that each row has five '1' and five '-1' values.

Radiant = 1, Dire = -1