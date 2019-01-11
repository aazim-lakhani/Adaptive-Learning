Initially, we were not logging, whether skip-enabled is set to True or False. Here are 2 experiments we ran on the same dataset, before n after logging (saving to csv) skip-enabled. 

General Observation: 

- On pre-training, the classifier stabilizes and performs better. 
- Without pre-training, if skip more often, but over time learns from its mistakes to skip less frequently. 
- 


EXPERIMENTS 

For Reward -1 & 1 

- Different values of alpha, without skipping 
- Different values of confidence threshold & without confidence threshold for optimal value of alpha
- Performance of the skip classifier with and without pre-training. 
- Performance of learning algorithm & oracle without skipping
- Performance of learning algorithm & oracle with skipping

