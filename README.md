# Policy-Gradient-Reinforce
Policy gradient methods are a type of reinforcement learning techniques that rely upon optimizing parametrized policies with respect to the expected return (long-term cumulative reward) by gradient descent.

Policy Based agents directly learn a policy (a probability distribution of actions) mapping input states to output actions.

•	Effective in high-dimensional or continuous action spaces

Policy gradient RL is a method for training the agent to make decisions by adjusting the parameters of its policy, which maps states to actions.

The Policy Gradient Theorem guides how to adjust the policy parameters to increase the likelihood of taking the optimal action in each situation, in order to maximize the reward. 

The robotic arm trained using policy-based methods based on the policy gradient theorem will generate a direct mapping from states to actions. This mapping, called the policy, is updated by adjusting its parameters based on the results of the actions taken by the arm. The policy gradient theorem calculates the gradient, or slope, of the policy’s performance with respect to its parameters. The policy is then updated in the direction of this gradient to increase the expected reward. This continuous improvement allows the robotic arm to smoothly and efficiently navigate its environment, gradually discovering the actions that lead to the highest expected reward.

Policy Based agents directly learn a policy (a probability distribution of actions) mapping input states to output actions. Along training this probabiity distribution are updated and gives more probability to actions that maximizes the reward in the long-term. The agent will take the actions with the maximum probability distribution. Whereas in Value- based methods the agent follows the max Q-value in order to take the best action and those Q-values are updated through training as well. 
