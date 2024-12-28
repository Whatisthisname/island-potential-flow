### Repository

The notebook contains:
- a small height-map based island generator
- [multiscale] [iterative] potential-flow solver with Dirichlet / Neumann boundary conditions
- visualization and image generation

### Example outputs
Below are some islands and associated flows. The seed is fixed in these examples, and I am carving out landmass to yield interesting water flow.

Water flow enters from the top and leaves at the bottom. 
Wind blows from right to left.

<p float="left">
  <img src="1_terrain.png" width="200" />
  <img src="1_current_traces.png" width="200" /> 
  <img src="1_wind_traces.png" width="200" />
</p>

<p float="center">
  <img src="2_terrain.png" width="200" />
  <img src="2_current_traces.png" width="200" /> 
  <img src="2_wind_traces.png" width="200" />
</p>

<p float="left">
  <img src="3_terrain.png" width="200" />
  <img src="3_current_traces.png" width="200" /> 
  <img src="3_wind_traces.png" width="200" />
</p>

### Purpose
I hope to use this as a simulator for a later path planner and controller for an autonomous sailboat 🤖⛵️.
