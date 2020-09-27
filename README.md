# Agent Selector
You are given the following data for agents <br>
agent :
* is_available
* available_since (the time since the agent is available)
* roles (a list of roles the user has, e.g. spanish speaker, sales, support etc.) 

When an issue comes in we need to present the issue to 1 or many agents based on an agent selection mode. An agent selection mode can be all available, least busy or random. In “all available mode” the issue is presented to all agents so they pick the issue if they want. In least busy the issue is presented to the agent that has been available for the longest. In random mode we randomly pick an agent. An issue also has one or many roles (sales/support e.g.). Issues are presented to agents only with matching roles.

Implement a function that takes an input the list of agents with their data, agent selection mode and returns a list of agents the issue should be presented to.  

## Description
* Implemented python code for a CLI based interaction for the problem
* Used **pickle** to simulate as a simple database for storing Agents and their respective details
* To start the program, run the **main.py** script.