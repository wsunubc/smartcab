# Train A SmartCab to Drive Itself

Reinforcement Learning (Q Learning) Project of Udacity Machine Learning Engineer Nanodegree Program

Applied reinforcement learning to build a simulated vehicle navigation agent. Modeled a complex control problem. Designed a scheme to automatically learn an optimal driving strategy based on rewards and penalties.


## Project Overview

This project applies reinforcement learning techniques for a self-driving agent in a simplified world to aid it in effectively reaching its destinations in the allotted time. It consists of the following tasks: 
* Investigate the environment the agent operates in by constructing a very basic driving implementation.
* Identify each possible state the agent can be in when considering such things as traffic lights and oncoming traffic at each intersection.
* With states identified, Implement a Q-Learning algorithm for the self-driving agent to guide the agent towards its destination within the allotted time.
* Improve upon the Q-Learning algorithm to find the best configuration of learning and exploration factors to ensure the self-driving agent is reaching its destinations with consistently positive results.


## Machine Learning Theory and Concept

* Reinforcement Learning
* Q Learning


## Development Environment

* OpenSUSE Linux 42.2
* Anaconda 4.4 with Python 2.7
* pandas, numpy, sklearn, PyGame


## Background

In the not-so-distant future, taxicab companies across the United States no longer employ human drivers to operate their fleet of vehicles. Instead, the taxicabs are operated by self-driving agents, known as *smartcabs*, to transport people from one location to another within the cities those companies operate. In major metropolitan areas, such as Chicago, New York City, and San Francisco, an increasing number of people have come to depend on *smartcabs* to get to where they need to go as safely and reliably as possible. Although *smartcabs* have become the transport of choice, concerns have arose that a self-driving agent might not be as safe or reliable as human drivers, particularly when considering city traffic lights and other vehicles. To alleviate these concerns, your task as an employee for a national taxicab company is to use reinforcement learning techniques to construct a demonstration of a *smartcab* operating in real-time to prove that both safety and reliability can be achieved.

