# Optimizing Park and Bike Hub Locations for Sustainable Urban Mobility

## Introduction

We aims to build Park and Bike (P&B) hubs strategically, to enhance commuter mobility, reduce urban traffic congestion, and ultimately maximize the demand for P&B hubs in the Amsterdam Metropolitan Area. In this report, we:
- Present the methodology used to solve the problem that can be applied in the future to help the operational team determine the best locations for new hubs.
- Find that the optimal hub locations, while considering opening at most seven hubs, cover a maximum demand of 9587 for the present problem.
- Conclude that the maximum possible coverage would be achieved with ten hubs with a demand of 9632.
- Show that after building the 3rd hub—with a corresponding demand of 8792—, the subsequent increases in coverage are less than 5% for each new hub with respect to the previous one, by assuming no restrictions in hub capacity.
- Verify that the longest accepted bike travel time T from a hub to a POI can be reduced from 45 to 27 and still get the optimal result of the maximum demand 9587.

### Model

<img width="921" alt="Screenshot 2024-02-25 at 19 28 07" src="https://github.com/jtjanetang/Urban-Mobility-Optimization/assets/159917017/a2f3a902-d784-4b8f-ae24-cc72611b4bff">

### Result

<img width="567" alt="Screenshot 2024-02-25 at 19 28 40" src="https://github.com/jtjanetang/Urban-Mobility-Optimization/assets/159917017/a2b4bc6f-f6de-4691-8fa9-f499c4f7083b">
<img width="742" alt="Screenshot 2024-02-25 at 19 28 48" src="https://github.com/jtjanetang/Urban-Mobility-Optimization/assets/159917017/d36598d4-b99a-456a-b401-6d3f0a594878">

### Sensitivity Analysis 
<img width="731" alt="Screenshot 2024-02-25 at 19 29 11" src="https://github.com/jtjanetang/Urban-Mobility-Optimization/assets/159917017/bfa98a5b-0a28-4446-bf66-ec4ceac36804">

## References 

- Mobian, Park & Ride System, 2017.
- Pyomo Optimization Modeling: [Pyomo Documentation](https://www.pyomo.org/)
