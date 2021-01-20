# Frozen-lake
The agent is trained  well enough to train and collect  the maximum number of rewards for each episode using the reinforecment learning concept.
    steps involved in setting up the frozen lake game.
import the libraries.
create the environment by just calling gym.make() 
create the Q table and initialize all the values to zeros(initially)
initialize the Q-leraning parameter.
for each episode reset the environment to initial state and for each time step within the ecah episode set the exploration rate threshold to a random number b/w 0 and 1.
Based on the exploration or exploitation take the corresponding action,update the q table,transition to the next state and collect the rewards accordingly.


Sanpshot of the Agent learning overtime to reach the goal 

![frozen lake](https://user-images.githubusercontent.com/68875720/105174375-c231ee80-5b22-11eb-9a04-0cd8badb9762.jpg)

