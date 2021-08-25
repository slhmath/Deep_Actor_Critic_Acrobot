# Deep_Actor_Critic_Acrobot
We train two Deep Neural Networks (DNN), which we'll refer to as the 'Actor' and 'Critic', to estimate the optimal policy for an agent playing Acrobot-v1 in OpenAI Gym.

The Actor represents the policy structure determined by one DNN, as it determines actions, while the Critic represents the approximate value function, as it 'criticizes' the actions made by the Actor.

The Actor and Critic learn during training, so that the recommended actions from the Critic maximize the agents reward.
