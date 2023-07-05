![No pooling versus hierarchical versus full pooling informational flowchart](https://github.com/beckynevin/hierarchical-pendulum-draw/blob/main/images/hierarchical_pendulum_phi.png)

![\Large a_g=G\Phi](https://latex.codecogs.com/svg.latex?\Large&space;a_g=G\Phi) where G is a constant and not part of the inference, and ![\Large \Phi=M/r^2](https://latex.codecogs.com/svg.latex?\Large&space;\Phi=M/r^2).

The goal of the inference is to infer ![\Phi](https://latex.codecogs.com/svg.latex?\Phi) using multiple pendulums located on different planets. Here only one pendulum is pictured for each planet, but in reality pendulums are grouped by planet. 

In the independent case, all planets are treated as stand-alone experiments and  ![a_g](https://latex.codecogs.com/svg.latex?a_g) and hence, ![\Phi](https://latex.codecogs.com/svg.latex?\Phi) are directly estimated for each planet. A follow-up averaging analysis happens post-facto to combine all independent estimates of ![\Phi](https://latex.codecogs.com/svg.latex?\Phi).

In the full pooling (co-dependent case, right), all pendulums on all planets are combined agnostic to which group (planet) they belong and ![\Phi](https://latex.codecogs.com/svg.latex?\Phi) is therefore estimated all at once for the entire group.

The hierarchical analysis (center) combines the strength of both approaches. Here, ![a_g](https://latex.codecogs.com/svg.latex?a_g) is inferred by group and at the same time we infer the overall distribution of ![\Phi](https://latex.codecogs.com/svg.latex?\Phi). Both inferences are linked.