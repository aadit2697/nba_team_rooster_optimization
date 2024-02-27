# NBA Team Rooster Optimization

The plan is to have 2 models.

Model1:
Target variable: Won/Lost

Ideal features: Player name, id, team_name, team_id, benched/not,three_pointers, points_scored_if_not_benched ,Won/Lost

Training data: Uses past games data for different players to predict whether them being in-game/benched resulted in a win or a loss

Test_data: Future games data


Model 2:

Target variable: Bench or Not 

Ideal features: Most of the features used to train Model1. However for this model, we will use the new column(Won/Lost) predicted from Model1 as our feature to train the model2

Training data: Cols from Ideal features in model 2.

Test data: Future seasons’ games data
