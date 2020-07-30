Here I show graphs of


In a simulated experiment, existing models were instantiated using a randomly chosen model parameters.

<!--The reason for this exercise is-->

In the class of reduced neural models we are optimizing, are not arbitrary waveform generators. The models have intrinsic restrictions that prevent them from matching perfectly with experimental waveforms.

When constraints are derived from model measurements, intrinsic model restrictions no longer apply. Optimized models should match perfectly with the simulated experiments. 

* Failure to match is indicative of three things:
- Optimizer code design failure
- Conceptual Failure
- Failure to setup tractable optimization problems.
- When inverting linear equations, finding a unique solution requires that the number of constraining equations is greater than the number of free variables you are solving for:


-  N free model parameters << N_constraints
-  In our specific design this expands to:
-  (model parameters + current_value parameter) << N (indipendent and uncorrelated) constraints.
-  
For the different classes of Reduced Model we show that 