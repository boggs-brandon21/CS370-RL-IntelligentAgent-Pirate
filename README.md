# CS370-RL-IntelligentAgent-Pirate
The code featured in the Boggs_Brandon_ProjectTwo.ipynb file involves a game where an intelligent agent faces an enemy pirate and the goal of the game is to get to the treasure before the pirate does. The observation space features a maze that has to be navigated through to reach the treasure at the end. For the machine to learn how to beat the game, it requires the use of an algorithm that tracks the state of the agent within the observation space of the game, and the potential rewards gained by taking various actions from each state within the observation space. In this algorithm, the agent receives a reward for a favorable action that does not result in a game being scored as a loss. If the agent wins or loses the game, that marks the end of an episode. This algorithm loops for every specified episode within an epoch until the agent is either able to produce an average win percentage greater than the specified amount or the agent reaches the maximum number of epochs. Essentially, the agent relies on a Q-value, “where ‘Q’ stands for a quality of a given move.” (Surma, 2021). For the agent to obtain an accurate Q-value, it requires the use of deep neural networks and linear algebra while studying all of the possible states and actions within an observation space to update itself with the cumulative discounted future rewards. Essentially, the agent has to play the game over and over again until it is able to maximize the reward for taking the correct actions at each of the correct states.

# What Do Computer Scientists Do and Why Does it Matter? 
Computer scientists work in many different fields ranging from IT support to software development and several other areas. Computer scientists are responsible for the design and development of software, hardware, and computer systems. Essentially, computer scientists focus on using technology to provide solutions for complex issues across virtually all industries. Computer science is an essential field within society that is responsible for the advancement of technology and its capabilities in our world. We work to solve complex problems by leveraging technological skills such as programming, data analysis, and system design. Personally, I enjoy working through complex problems that cause me to stop and think about what I am doing on each stage of development. I enjoy having to really use my brain to come up with creative solutions for design and functionality requirements from the client. Within the development of each application, I am ethically required to protect all sensitive user/company information from potential malicious users, perform my duties to the established coding standards, and provide the user with the best product possible without creating safety risks for the company or their users. 
