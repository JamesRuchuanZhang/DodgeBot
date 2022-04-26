# DodgeBot

The objective of this project was to find a better way to address matchmaking and prevent LP losses from poorly matched games.

In order to run these notebooks, you will need a "keys.txt" text file that contains a valid Riot Games API key on the first line and a "igns.txt" text file that contains a list of in-game names that were volunteered to be used as training data.

buildDataSets should be run first to generate the data sets and train the models, this may take a while due to rate limits imposed by the Riot Games API. programRun should then be run to execute the program by pulling live League client data and comparing it to the models generated.
