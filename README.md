# IFML-Bomberman

Clone of https://github.com/ukoethe/bomberman_rl.git.

We added some minor changes we made to the environment, and our own agent.

# Our agent

NOBEL-COIN is a version of our agent that can only collect coins, however it is quite good at it.

NOBEL-CRATES is a version that can deal with bombs and crates, but was not trained with enemies.

NOBEL-SEMIFINAL is a version that can play the full game. It is a preliminary version from which we continued training.

NOBEL-FINAL is a version that can play the full game. It is the final version we submitted for the competition.

NOBEL is a version that does not load a trained model. However, it contains the raw files from which all our plots were generated, and the functions to generate those plots.

Our agent requires keras and tensorflow.

# Comparison to other agents on GitHub

After 200 rounds with two Nobel against two Lord Voldemort (agent from https://github.com/DanHalperin/Bomberman_rl), Nobel recieved a mean of 4.4 points (5.4 without punishment for slowness) vs the 3.5 points of Lord Voldemort, however Nobel was consistently one order of magnitude slower.

Same setup against TheImitator (https://github.com/AaronDavidSchneider/bomberman_RA), after 50 round Nobel achieved 5.3  (6.3 without punishment for slowness) vs the 2.2 of TheImitator, while taking about three times as long to choose actions.

Same setup against The_Jester (https://github.com/malteprinzler/bomberman_AI), after 280 round Nobel achieved 3.2  (4.2 without punishment for slowness) vs the 2.8 of The_Jester, while taking about three times as long to choose actions.

In a setup of Nobel vs. Lord_Voldemort vs. TheImitator vs. The_Jester, after 400 rounds they achieved mean points of 4.36 vs. 4.04 vs. 1.47 vs. 3.73 per round, respectively. Nobel clearly outperformed the other agents, but got deducted one point every round because it was also clearly the slowest, i.e. ignoring the punishment for slowness Nobel would have achieved a mean score of 5.36 points per round.
