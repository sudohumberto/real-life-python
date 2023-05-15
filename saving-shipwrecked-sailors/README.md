# Saving Shipwrecked Sailors With Bayes’ Rule

From Real World Python by 

# Description 

In this project, you’ll write a Python program that uses Bayes’ rule to find a solitary fisherman who has gone missing off Cape Python. As the director of the Coast Guard’s search and rescue operations for the region, you’ve already interviewed his wife and determined his last known position, now more than six hours old. He radioed that he was abandoning ship, but no one knows if he is in a life raft or floating in the sea. The waters around the cape are warm, but if he’s immersed, he’ll experience hypothermia in 12 hours or so. If he’s wearing a personal flotation device and lucky, he might last three days.
The ocean currents off Cape Python are complex, and the wind is currently blowing from the southwest. Visibility is good, but the waves are choppy, making a human head hard to spot.

In real life, your next course of action would be to plug all the information you have into the Coast Guard’s Search and Rescue Optimal Planning System (SAROPS). This software considers factors such as winds, tides, currents, whether a body is in the water or in a boat, and so on. It then generates rectangular search areas, calculates the initial probabilities for finding the sailor in each area, and plots the most efficient flight patterns.
For this project, you’ll assume that SAROPS has identified three search areas. All you need to do is write the program that applies Bayes’ rule. You also have enough resources available to search two of the three areas in a day. You’ll have to decide how to allocate those resources. It’s a lot of pressure, but you have a powerful assistant to help you out: Bayes’ rule.

# Objective 

Create a search and rescue game that uses Bayes’ rule to inform player choices on how to conduct a search.

# Requirements 

```
python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose

pip install opencv-contrib-python
```