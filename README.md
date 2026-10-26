# CS-370: Current and Emerging Trends in Computer Science

## Pirate Intelligent Agent – Deep Q-Learning

### Project Overview

For this project, I developed an intelligent pirate agent capable of navigating a maze to locate treasure using deep Q-learning. The goal was to train the agent to find an efficient path to the treasure while avoiding obstacles. This project demonstrated how reinforcement learning and neural networks can be combined to solve pathfinding problems. The agent was trained using deep Q-learning with experience replay, an epsilon-greedy exploration strategy, and periodic target network updates. The training process used an 8×8 maze containing pathways and obstacles. During testing, the model achieved a 100% recent win rate and passed the completion check at epoch 324, demonstrating that the agent had learned to navigate from the available starting positions to the treasure.

### What Code Was Provided, and What Did I Create?

The project included starter code that established the maze environment, defined the available actions, and provided supporting functions for the reinforcement learning process. My responsibility was to complete the deep Q-learning training algorithm that allowed the pirate agent to learn how to navigate the maze.

I implemented the training logic that allowed the agent to interact with its environment, collect experiences, and improve its decisions over multiple training episodes. This included balancing exploration and exploitation, updating the neural network through experience replay, and evaluating the agent's ability to reach the treasure. Through this process, I gained a better understanding of how reinforcement learning can be applied to problems where an agent must learn from its own actions.

### What Do Computer Scientists Do, and Why Does It Matter?

Computer scientists develop solutions to problems using algorithms, programming, and computational thinking. Their work goes beyond writing code because it also involves understanding problems, evaluating possible solutions, and designing systems that are reliable and efficient.

Throughout this course, I learned how artificial intelligence and machine learning extend these capabilities by allowing systems to recognize patterns and make decisions based on data or experience. These technologies are important because they can help solve complex problems in areas such as cybersecurity, automation, healthcare, and transportation.

### How Do I Approach a Problem as a Computer Scientist?

I approach problems by first understanding the requirements and identifying what needs to be accomplished. From there, I break the problem into smaller components, determine which tools or algorithms are appropriate, and develop a solution that can be tested and improved.

This project reinforced the importance of testing and making adjustments throughout development. Training a reinforcement learning agent is not always predictable, and changes to training parameters can affect how well the model performs. Rather than assuming the first implementation will work perfectly, I learned to evaluate the results, identify potential improvements, and make adjustments based on the agent's behavior.

### What Are My Ethical Responsibilities to the End User and the Organization?

As a computer scientist, I have a responsibility to develop systems that are secure, reliable, and respectful of users. This includes protecting sensitive information, considering potential biases, and being transparent about the limitations of the technology being developed.

Artificial intelligence introduces additional ethical considerations because its decisions can be influenced by training data, reward functions, and the assumptions made during development. Developers need to evaluate these factors carefully to reduce unintended outcomes. Organizations also have a responsibility to ensure their systems are used appropriately and do not create unnecessary risks for users.

This course helped me recognize that building an effective solution is only part of the responsibility. It is equally important to consider how that solution affects the people and organizations that depend on it.
