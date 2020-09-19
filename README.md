README.md

[Halite 4](https://www.kaggle.com/c/halite/) was a competitive simulation challenge run by Kaggle in 2020. It is a 4 player resource management game where teams create agents to compete against other teams' agents.

This is the solution from team "KhaVo Dan Gilles Robga Tung". In a field of 1143 teams, we placed a provisional 8th at the end of the public phase. We hope to remain in the top 10 once the private 7 day phase completes. No ML bot had finished in the top ten of the three forerunner Halite competitions.

You can read our [solution description](https://www.kaggle.com/c/halite/discussion/183312).

![](https://github.com/voanhkha/voanhkha.github.io/blob/master/images/halite_team.png?raw=true)

Our solution includes code for:
- A notebook to create a numpy dataset from episode.json's
- A notebook to train a model based on the numpy dataset
- Pretrained pytorch weights for the ML agent's model, if you don't want to train.
- A machine Llanguage driven imitation agent.

The ML solution ia to use semantic segmentation of game boards to predict best next actions for a fleet of competing ships, based on imitating thousands of previous competitor games.

If you want to train a model, first download [11GB of games](https://www.kaggle.com/robga/halitegames/).  Processing the games with the dataset notebook will create a 120GB dataset suitable for training. Training can take anywhere from 5-20 hours on a strong consumer GPU.

Our team was
Kha Vo https://www.kaggle.com/khahuras
Dan Grunberg https://www.kaggle.com/solverworld
Gilles Vandewiele https://www.kaggle.com/group16
Rob Gardiner https://www.kaggle.com/robga
Tung M Phung https://www.kaggle.com/tungmphung

![](https://github.com/voanhkha/voanhkha.github.io/blob/master/images/halite_full.gif?raw=true)

See you in Halite 5?
