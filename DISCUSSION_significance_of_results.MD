# Poor model Performance.

* Within a reasonable parameter range conductance based models are usually close to experimentally observed measurements.

# Patterns of poor model performance in Phenomenological Models.
* many reduced neural models are far from optimal at any point in parameter space. Optimizing does not significantly improve agreement. Optimizing does not bring model and experiment close to `Z=0`.

There is an order of magnitude difference. Between agreement in Rheobase values between the conductance based models and the experimental models. 


## What does it mean.

* In methods I discussed an approach to verifying the optimizer.
- Specifically, we showed efficient optimizer convergence, when constraints were derived from simulating experiments.

When the optimizer setup is cogent because appropriate models and test combinations have been chosen, and because 

N free_params <= N constraints

The optimizer finds a varied set of compromised solutions.

* In order to verify our approach we also re-implemented our code using BluePyOpts select best algorithm, and NSGA2.
