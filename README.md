# production-planning

*Implement the Wagner-Whitin algorithm to minimize the total costs of production given a set of constraints*


# Objective
Use python to design an optimal production plan to meet customer demand and minimize the total production costs.

# Scenario

You are a production planning manager in a small factory producing radio equipment that serves local and international markets.

Customers send Purchase Orders (PO) to your commercial team with quantities and expected delivery dates.

Your role is to schedule production to deliver on time with a minimum total cost of production that includes

- Setup Costs: fixed costs you have each time you set up a production line
- Production Costs: variable costs per unit produced
- Holding Costs: cost of storage per unit per time
- In our example, the customer ordered products for the next 12 months

# Wagner-Whitin Algorithm
This problem can be seen as a generalization of the economic order quantity model that takes into account that demand for the product varies over time.

Wagner and Whitin developed an algorithm for finding the optimal solution by dynamic programming.

The idea is to understand each month if adding the current month's demand quantity to past months' orders can be more economic than setting up a new cycle of production.
