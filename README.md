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

<!-- After 200 rounds with two Nobel against two Lord_Voldemort, Nobel recieved a mean of 4.4 points (4.9 without punishment for slowness) vs the 3.5 points of Lord Voldemort, however Nobel was consistently one order of magnitude slower. -->

<!-- Same setup against TheImitator, after 50 round Nobel achieved 5.3  (5.8 without punishment for slowness) vs the 2.2 of TheImitator, while taking about three times as long to choose actions. -->

<!-- Same setup against The_Jester, after 280 round Nobel achieved 3.2  (3.7 without punishment for slowness) vs the 2.8 of The_Jester, while taking about three times as long to choose actions. -->

In a setup of Nobel vs. Lord_Voldemort vs. TheImitator vs. The_Jester, after 250 rounds they achieved mean points of 4.86 vs. 3.78 vs. 1.70 vs. 3.50 per round, respectively. Nobel clearly outperformed the other agents, even though it was punished for consistently being the slowest agent.<!-- Round: 250, Scores: [1214, 946, 425, 875] -->

# Other agents on GitHub

Lord_Voldemort https://github.com/DanHalperin/Bomberman_rl

TheImitator https://github.com/AaronDavidSchneider/bomberman_RA

The_Jester https://github.com/malteprinzler/bomberman_AI

final_agent https://github.com/flo-he/RL-for-bomberman

farting_simulator https://github.com/MadoScientistu/Bomberman-A.I.-Uni-Heidelberg-FML-WS-2018-19

lukas_agent https://github.com/phaetjay/ifml_project
