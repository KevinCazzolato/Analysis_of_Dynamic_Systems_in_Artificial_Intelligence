## Anharmonic Oscillator: Analysis of Dynamic Systems in Artificial Intelligence

This project, titled **"Anharmonic Oscillator: Analysis of Dynamic Systems for Artificial Intelligence"**, is an exploration into the behavior and stability of an anharmonic oscillator, conducted as part of the AIDA 2023 course. The central aim is to analyze and understand the dynamics of a Hamiltonian system where non-linear forces are considered, thereby deviating from the idealized harmonic scenario.

### Equations of Motion and System Dynamics

The analysis begins by deriving the equations of motion from the Hamiltonian of the system. The Hamiltonian is given by:

**H = p² + ax² + x⁴**, where *p* represents the momentum and *x* represents the position. The corresponding equations of motion are derived as:

- **ẋ = 2p**
- **ṗ = -2ax - 4x³**

The system is examined under these dynamic equations, which illustrate how the state evolves over time. Graphs of the evolution of *x*, *p*, and energy are presented to visualize how these variables oscillate, demonstrating the interdependence between kinetic and potential energy. The conservation of energy, a crucial characteristic of Hamiltonian systems, is confirmed by showing that the Hamiltonian value remains constant over time for different initial conditions.

### Phase Portrait and Energy Conservation

A key focus of this study is the phase portrait of the system, which illustrates the trajectories of state variables (*x* and *p*) in phase space for various initial conditions. By analyzing the phase portraits, the project categorizes the different qualitative behaviors of the system depending on the parameter *a*, which can take negative, zero, or positive values. For each scenario, the corresponding orbits and level curves of the Hamiltonian are depicted, highlighting how different initial conditions influence the overall trajectory and stability of the system.

The study also involves a verification of energy conservation by calculating the time derivative of the Hamiltonian, **dH/dt**, and showing that it is always zero for all values of *x* and *p*, thereby mathematically confirming energy conservation in the system.

### Fixed Points and Stability Analysis

The stability of the system is further investigated by identifying the fixed points and analyzing their stability properties. Fixed points are determined by setting both **ẋ** and **ṗ** equal to zero, resulting in distinct equilibrium points depending on the value of *a*. For negative values of *a*, three fixed points are identified: (0, 0), and two symmetric points, while for non-negative values, only (0, 0) is found.

The stability of these fixed points is studied using two complementary approaches: the Jacobian matrix analysis and potential analysis. The Jacobian matrix is used to assess the nature of the fixed points, including saddle points, centers, and unstable nodes, by evaluating the eigenvalues at each fixed point. Meanwhile, a graphical analysis of the potential function **V(x) = ax² + x⁴** provides further insight into the stability characteristics, with the different types of fixed points observed visually from the graph of the potential.

### Separatrices and Dynamical Regimes

The study also discusses the separatrices and dynamical regimes of the system. Depending on the value of *a*, the system exhibits different separatrices which divide distinct regions of motion. For *a >= 0*, these are represented as ellipses derived from the potential analysis, whereas for *a < 0*, the separatrices are identified through the eigenvectors of the fixed point (0, 0). The resulting phase portrait reveals various dynamical behaviors, including elliptic and saddle-like trajectories, providing a detailed picture of how the system evolves under different energy levels.

### Summary

This project provides an in-depth analysis of the anharmonic oscillator, showcasing the complex behavior that emerges from the non-linear terms in the Hamiltonian. Through a combination of analytical derivation, graphical representation, and stability analysis, it offers valuable insights into the dynamics of systems with non-linear potentials. Such studies are crucial in understanding complex dynamical systems, especially those used in artificial intelligence where stability and energy conservation play key roles.

The results demonstrate that the anharmonic oscillator, depending on the parameter *a*, can exhibit a range of behaviors, including stable and unstable equilibria, periodic orbits, and complex separatrices that govern the flow in phase space. This contributes to the broader understanding of how non-linear systems behave, an essential aspect when designing and analyzing algorithms in artificial intelligence.

