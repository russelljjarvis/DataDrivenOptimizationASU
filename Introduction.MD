

# Motivation:
* Biophysically accurate models are slow. Reduced models are fast.
Efficient models: GLIF, Izhikitch.
You could make biophysically accurate models faster, or you could make reduced models more accurate. To make reduced models more accurate, you would find parameterizations of the models that let the models act as better mimics of experiments.
* Herein we investigate how well Faster models can match experimental recording waveform shapes.
* The reason why we want to investigate the match:
- Large scale simulations cant evaluate on a timescale that is meaningful, unless a large ratio of modelled cells are "reduced models"
- Reduced Models already enjoy wide spread usage. We want to investigate if reduced models can be made to be more realistic, by checking if they can mimic data better.
- If reduced models can't be made more realistic (herein we show only marginal improvements), we need to show the limitations of reduced cells, with regards to a particular set of tests.
- We need to document the approach used, and how the approach contrasts with spike time approaches to model fitting.
