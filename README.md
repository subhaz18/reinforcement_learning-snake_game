Ai snake using Reinforcement Learning

Snake is a typical video game where the player maneuvers a line which grows in length, with the line itself being a primary obstacle.Our goal is to train a more efficient agent than human for Snake.To approach this goal, firstly we use pygame achieve a simple Snake game as the environment.Because Snake game have so many states that it is impossible to use tabular method represent them and human play Snake and learn it by geting the image of it. We believe that Double-DQN which is a classical algorithm of RL is suitable for our agent
training.Besides,Snake is also similar with a walking or climbing process.We note that PPO has good performance for resolving such problem by restricting the variance during training.That is why we want to compare Double-DQN with PPO in our environment.Then we use Double-DQN and PPO to train our agent.At present, we get the results in current environment.We find that Double-DQN is more stable but the peak of PPO is better.

Acknowledgments

I would like to extend my gratitude to [Patrick Loeber](https://youtu.be/PJl4iabBEz0?si=SB9xh_A1ZW2V1Rtd) for his invaluable contributions to my learning process. His informative and engaging YouTube videos have provided me with the knowledge and inspiration. Thank you, Patrick, for sharing your expertise and passion for coding!
