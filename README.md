# Alpha Monte Carlo Tree Search

Simple Steps:

1. **Selection**: Walkdown until leaf Node

2. **Expansion**: create new Node

3. **Simulation**: Play randomly

4. **Backpropagation**

For instance, the backpropagation step can be represented by the formula:

$$ Q(s, a) = Q(s, a) + \frac{1}{N(s, a)} \cdot (R - Q(s, a)) $$

where \( Q(s, a) \) is the quality of a state-action pair, \( N(s, a) \) is the number of times that action \( a \) has been taken from state \( s \), and \( R \) is the reward.
