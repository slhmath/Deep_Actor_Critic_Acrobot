# Deep_Actor_Critic_Acrobot
We train two Deep Neural Networks (DNN), which we'll refer to as the 'Actor' and 'Critic', to estimate the optimal policy for an agent playing Acrobot-v1 in OpenAI Gym.

The Actor represents the policy structure determined by one DNN, as it determines actions, while the Critic represents the approximate value function, as it 'criticizes' the actions made by the Actor.

The Actor and Critic learn during training, so that the recommended actions from the Critic maximize the agents reward.

The agents 'goal' is to swing its two limbs so that the intermediate joint breaches the horizontal bar directly above it.
Here is a sample of the agent performing during the training phase: 


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/DeepQ_Acrobot_Training.gif" width="200" height="200">


After training is complete, the Deep Q-Network has discovered an approximately optimal policy. Below are examples of how the trained agent peforms on the first 4 test runs:


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_1.gif" width="200" height="200">


(Run 1. Steps: 111)


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_2.gif" width="200" height="200">


(Run 2. Steps: 82)


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_3.gif" width="200" height="200">


(Run 3. Steps: 96)


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_4.gif" width="200" height="200">


(Run 4. Steps: 83)
