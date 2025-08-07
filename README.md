📦 Q-Learning AI for Warehouse Flow Optimization


This project demonstrates a Q-Learning based AI designed to optimize navigation in an e-commerce warehouse using reinforcement learning principles. It simulates an autonomous robot finding the shortest and most efficient path to high-priority locations.

⭐ SITUATION:
E-commerce warehouses often require robots to dynamically navigate and fetch products from shelves based on real-time priority. Efficient routing is essential to reduce delivery times and increase productivity.

⭐ TASK:
Design and implement an AI model that enables an autonomous warehouse robot to always determine the shortest path to the top priority product location, while optionally visiting intermediary high-priority shelves for multi-tasking efficiency.

⭐ ACTION:

-Defined the environment using a 12-node grid representing warehouse locations (A–L).

-Encoded transitions between locations using a reward matrix based on available paths and priorities.

-Implemented the Q-Learning algorithm using NumPy to learn optimal paths through repeated simulation (1000+ episodes).

-Developed a production-level route() function to return the shortest route from any starting point to a target, using the learned Q-values.

-Extended functionality with best_route() to support intermediary stopovers, optimizing multi-location delivery paths.

⭐ RESULT

-Achieved a working model that dynamically learns optimal paths to top-priority targets.

-Improved route accuracy with automated reward updates and intermediary support.

-Demonstrated practical application of Reinforcement Learning (Q-Learning) for supply chain and robotics optimization.

🧠 Key Concepts
Q-Learning: A model-free RL algorithm that updates Q-values using the Bellman equation.

Reward Matrix: Encodes environment constraints and reward structure.

Markov Decision Process (MDP): Framework used to model state transitions.

Temporal Difference (TD): Drives learning by evaluating reward + best future estimate.

