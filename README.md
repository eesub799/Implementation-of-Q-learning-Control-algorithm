# Implementation-of-Q-learning-Control-algorithm
## Aim

To implement the Q-Learning Control Algorithm using the FrozenLake environment in Reinforcement Learning and learn the optimal policy through interaction with the environment.

---

# Algorithm

### Q-Learning Algorithm

1. Import the required libraries.
2. Create the FrozenLake environment.
3. Initialize learning parameters:
   - Learning rate (`alpha`)
   - Discount factor (`gamma`)
   - Exploration rate (`epsilon`)
4. Initialize the Q-table with zeros.
5. For each episode:
   - Reset the environment.
   - Choose an action using the epsilon-greedy policy.
   - Execute the action and observe:
     - Next state
     - Reward
   - Update the Q-value using:

\[
Q(s,a)=Q(s,a)+\alpha \left[r+\gamma \max Q(s',a')-Q(s,a)\right]
\]

6. Decay epsilon after every episode.
7. Store rewards for performance analysis.
8. Print the learned Q-table and optimal policy.
9. Plot reward vs episodes graph.

---

# Program

```python


```

---

# Output

```text

```

---

# Result

Thus, the Q-Learning Control Algorithm was successfully implemented using the FrozenLake environment. The agent learned the optimal policy through exploration and exploitation, and the performance improved over episodes with a high success rate.
