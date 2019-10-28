Reference:
1. [A hands on experience to Deep Q-Learning](https://www.analyticsvidhya.com/blog/2019/04/introduction-deep-q-learning-python/)
---
2. Based off of [Simple reinforcement learning with tensorflow Q-learning with tables and neural networks](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0)  
    
      **What do policy gradients try to achieve?** - They attempt to learn functions which directly map an observation to an action.  
      **How are Q-learning attempts different?** - Q-learning attempts to learn the value of being in a given state and taking specific action there.  
      **What is OpenAI gym?** - provides an easy way for people to experiement with their learning agents with the toy games.  
      Updates to the Q-table are done using **Bellman Equation which states that the expected long-term reward for a given action is equal to the immediate reward from the current action combined with the expected reward from the best future action taken at the following state**
