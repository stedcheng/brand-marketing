<h1>Brand Marketing Strategies and the Competition Between Two Clothing Brands</h1>

<h2>Abstract</h2>
<h3>Introduction and Literature Review</h3>
To influence customer decision-making, appropriate marketing strategies must be implemented. This can be determined through studying market behavior. The current study aims to create a model simulating clothing brand distribution, which can lead to investigating factors, both on the customer side and the brand side, that affect market behavior. Ultimately, these simulation results will be used to recommend the most effective marketing strategies. In the simplest case, factors such as product awareness, exposure rate (probability of being aware of a product), usage rate (probability of purchasing the product), and brand loyalty. The current study expands this by taking into account the impact of external factors, i.e., microinfluencers, macroinfluencers, geographical advertising (billboards), first-hand experience (shops). Appropriate parameters are also extracted or calculated from related literature.

<h3>Methods</h3>
An agent-based model, particularly the Boids flocking model, was used for the simulation process. It assumes that the agents (also known as Boids) fly towards the center off the position of their neighbors, keep distance from their neighbors, align their velocity with their neighbors, and change direction when near the border. Ordinary agents, which are the consumers in the clothing market, have eight states, depending on product awareness and usage. The state transition table shows the rules on what happens to the states of two agents when they meet. Micro- and macroinfluencers differ in terms of influence radius, while billboards and shops differ in terms of size and duration. For example, if an influencer of product B meets someone who knows and uses product A, then the probability of the consumer switching is related to the usage, influencer, and loyalty parameters. The simulation was run for 365 timesteps. 

<h3>Results</h3>
The output of each simulation is five line graphs containing the proportion of people who (1) know and use product A, (2) know and use product B, (3) know both and use product A, (4) know both and use product B, and (5) use neither. After performing baseline simulations with only one product having an external factor, these external factors were compared with each other. For example, the microinfluencer-billboard pairing (i.e., one product has microinfluencers and the other has billboards) revealed that the billboards create an initial head start, but adding the number of microinfluencers for the other product reduces it. Further simulations were performed, where more marketing resources were added to the "losing" product until it surpasses the "winning" product. This was to determine the relationships between competing external factors. For example, the effect of one billboard is greater than that of one microinfluencer but less than that of two, while the effect of one macroinfluencer is between that of two and three billboards. Brand switching tendencies were also noted through the graphs. 

<h3>Conclusion</h3>
Ranking the four external factors, macroinfluencers are slightly better than shops, followed by billboards, and then finally microinfluencers. Recommendations include considering demographics, assuming different popularity levels, changing time intervals for influencers and billboards, moving the location of the billboard or shop, and implementing more trials per simulation. 

<h2>Files</h2>
<ul>
  <li><code>Slide Deck.pdf</code>: Slide deck used to present the research.</li>
  <li><code>Simulation</code> folder: Contains the <code>Simulation.ipynb</code> file, which are the codes used to perform agent-based modeling.</li>
</ul>

<h2>Credits</h2>
This project was created by Michaela Agan, Sted Cheng, and Nicole Palo, and submitted as a requirement for the course <b>CSCI 115: Computer Simulation and Modeling</b> taken in the second semester of AY 2022-2023 in Ateneo de Manila University. 


