This folder contains the requested comparison graphs against state of the art methods. 
Additionally, regrding the scalability, we run the experiments with more agents.

## Comparison Against Other Methods
The **Table 1** shows the comparison against current state of the art methods.

The file **"merge_split.png"** presents a comparison of our method against the Merge-and-Split method. This method incurrs in energy cost (measured in micro Watts) due to the communication among agents. Our method avoids the communication cost since it is a decentralized algorithm where agents take decisions independently, thus the communication cost is zero. We present the communcation cost against the number of agents and against the distance between agents.

## Run With More Agents
The Figure **"boxplot_8agents.pdf"** shows the results of the accuracy of the method with 8 agents. The accuracy of the method is compared against 2 clustering methods, a random policy, and the tabular Q-learning method.

The Figure **"distances_histogram8_agents.pdf"** shows the change in distance between training distances and testing distances. This is to show how the agents' policies were tested on different coalitions than the ones used at training time.

