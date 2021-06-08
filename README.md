# Inventory-Management

## Overview

The objective of this project is to provide a possible solution to large retail firms
which manufacture products in their factory and transport the same to different
warehouses.It is focused on Stock and demand optimization, with multiple
locations, transportation issues, seasonal demand changes, and manufacturing
costs such that the total cost involved is minimised and the demand from various
warehouses is met.It is also focused on finding a policy that prescribes a pricing
action based on the current state in a way that the total profit is maximized.

## The overall project is divided into 2 parts:

### • Stock and Demand Optimization:
State: The State vector to include all current stock levels and demand
values for all warehouses.
Action: The action vector consists of the production and shipping control
to all the warehouses.
Reward: The reward consist of 4 components, revenue, production cost,
total storage cost and the transportation cost.

### • Price Optimization:
State: The state of the environment at any time step t as a vector of
prices for all previous time steps concatenated with one-hot encoding of
the time step itself.
Action: The action a for every time step is just an index in the array
of valid price levels.
Reward: Reward r is the profit of the seller.

## Implementation using reinforcement learning techniques:

1.(S,Q) - Policy
2. DQN Algorithm
