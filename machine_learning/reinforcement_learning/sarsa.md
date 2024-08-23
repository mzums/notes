# SARSA vs Q-Learning

### Generally:
G-Learning is off-policy TD learning of the Q function  
SARSA is on policy TD learning of the Q function

## Use cases
Q-Learning is more experimental, picks random actions (epsilon greedy alg). It is a more efficient way of learning and gives us generally better performance.  
  
SARSA chooses the best action according to the policy, so the best action it thinks there exists. It is better if we value performance during training, stability or reliability and safety. For example we don't want our RL car to suddenly turn and bump into something.