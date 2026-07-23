# A-Game-Theory-Simulation-of-the-US-Iran-conflict
An accompaniment of the paper "A Computational Game-Theoretic Framework for Modelling Repeated Asymmetric Strategic Interactions, Demonstrated Using the US-Iran Conflict as a Case Study", this project uses an attrition-based game to model the US-Iran conflict. 

## Model Structure and Methods
* Each agent uses probabilistic strategies to increase their payoff
* Once, an agent's reserves reach a certain threshold, they are forced to follow a single, pre-determined strategy
* Key parameters such as "MAX_ROUNDS", "INITIAL_US_RESERVES", "INITIAL_IRAN_RESERVES", "IRAN_COST_MULTIPLIER", "US_P_DEFECT_AFTER_IRAN_COOP", AND "IRAN_P_DEFECT_AFTER_US_COOP" can be adjusted by the user

## Tech Stack
* **Language:** Python
* **Computation & Modeling:** `numpy`, `scipy`
* **Data Visualization:** `matplotlib`
