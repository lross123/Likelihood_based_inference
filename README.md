<H1> Likelihood based inference </H1>

This repository contains several Julia codes which have been used to build a lattice-based discrete model which produces synthetic data that resemble soluble gradients and are compared to the continuum model. Then structural and practical identifiability analysis is performed against synthetic data to benchmark fit quality before costly wet-lab validation.


<H1> Case 1 </H1>


<H2> Discrete Model </H2>

The discrete model generates all of the synthetic data which is used within this study. Visualisations of the discrete model in the 2D and 3D cases are showcased in the scripts provided below. 


<H3> 2D Model </H3>

2D_DiscreteModel.jl is responsible for generating all data needed to create Figure [] and generate results for both the additive Gaussian measurement error model and the multinomial measurement error model. Figs.jl is responsible for creating Figure [] using the data.



<H3> 3D Model </H3>

3D_DiscreteModel.jl is responsible for generating all data needed to create Figure [] and generate results for both the additive Gaussian measurement error model and the multinomial measurement error model. Figs.jl is responsible for creating Figure [] using the data.

<H2>Practical Identfiability</H2>


