# SNHU_CS-370_Portfolio
Portfolio for CS-370

Final Reflection:

As the goal of the Deep-Q learning implementation is to find the best possible navigation sequence that results in reaching the treasure cell, while maximizing the reward – the Deep-Q learning network was given, but the Q-training algorithm needed to be created and implemented. 
First, I had to determine an optimal number of epochs to help achieve 100% win rate, and run all the cells with Tensorflow backend to train the network. The final cell shows a test model for a game – we can see the map the pirate takes through the maze, avoiding the path obstacles. 
Specifically, the agent selects a free cell at random to start  epsilon-greedy value determines the probability that an agent should select the random action, rather than an action to maximize expected utility  agent takes the action, storing the episode, reward, and game status  if the pirate has won that game, update the win rate, else update the loss, finish when win_rate is greater than epsilon.

As a computer scientist, I must remember to approach each requirement with not only user needs in mind, but also the ethical concern for the business and society at large. I must do my best to avoid coding bias or training bias into datasets so as to avoid these ethical dillema.
