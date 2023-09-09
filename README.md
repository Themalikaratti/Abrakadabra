# Abrakadabra
This environment is part of the Toy Text environments. In this the agent has to perfrom some relevant actions in environment. The main goal is to reach the final destination.
The board has 4x12 matrix.
[3, 0] as the start at bottom-left
[3, 11] as the goal at bottom-right
[3, 1..10] as the cliff at bottom-center
If the agent steps on the cliff, it returns to the start. An episode terminates when the agent reaches the goal.
There are 4 discrete deterministic actions:
0: move up
1: move right
2: move down
3: move left.
Each time step incurs -1 reward, and stepping into the cliff incurs -100 reward.
