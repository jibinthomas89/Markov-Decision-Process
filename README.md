# Markov-Decision-Process

## Optimizing Customer Service Delivery for Lenovo Data Center Group

### Summary
The Lenovo Group is one of the largest technology companies in the world. For a technology company like Lenovo, early and efficient issue resolution plays a key role in reducing costs and driving customer satisfaction. Towards this end, in collaboration with Lenovo, a decision support system was proposed to help identify the appropriate service action to resolve an issue. The scope of the project was restricted to High Performance machines in the Asia Pacific and PRC regions. The methodology of this project involved accurately identifying key factors that exhibit similar issue resolution behaviors and ultimately translating these behaviors into a consistent prediction and action scheme through a Markov Decision Process

### Methodoloy

1) Built a stochastic model to understand the probabilities of each service action resolving an issue and to isolate the common paths that customer issues took in terms of service actions before being resolved.

2) Analyzed the stochastic model to build a Markov Decision Process which helped generate the optimal set of rules for service action selection at each stage of the customer support process.

The five components of the Markov Decision Process (State space, Action space, Epoch, Transition probabilities and Cost matrix) were defined carefully to capture as much of the available information about a particular issue. After accounting for the costs and probabilities for each transition, the optimal decision policy was generated using linear programming. The linear program accounts for all potential transitions, in terms of costs and their likelihoods, and then decided which service action is the most optimal choice in terms of cost.
