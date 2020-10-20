# News and supplementary materials 2020

### 2020.09.15
- Moore's law of cameras: [LSST 3.2 gigapixel camera photos released](https://www6.slac.stanford.edu/news/2020-09-08-sensors-world-largest-digital-camera-snap-first-3200-megapixel-images-slac.aspx)
- __HW:__ Read Ch. 1-4

### 2020.09.21
- Nature [review on Numpy](https://www.nature.com/articles/s41586-020-2649-2)
- __HW:__ Read Ch. 5-7

### 2020.09.29
- Root finding [summary slides](https://icsabai.github.io/classes/compsimf17em/Slides2019/rootFinding.pdf) (based on Numerical Recipes book)
- Root finding convergence, Newton fractal [notebook](https://nbviewer.jupyter.org/github/icsabai/simulationsMsc/blob/master/code/ch07_differentiation_roots/newton_fractal.ipynb) and zooming [movie](https://www.youtube.com/watch?v=gh6e95OmoAk)
- __HW:__ Read Ch. 8-9.


### 2020.10.06
- 2020 [Nobel prize](https://www.nobelprize.org/) in physics
  - __Roger Penrose__ invented ingenious mathematical
methods to explore Albert Einstein’s general theory
of relativity. He showed that the theory leads to the
formation of black holes, those monsters in time
and space that capture everything that enters them.
Nothing, not even light, can escape.
  - __Reinhard Genzel and Andrea Ghez__ each lead a
group of astronomers who have focused on a
region at the centre of the Milky Way since the
early 1990s. With increasing precision, they
have mapped the orbits of the brightest stars
that are closest to the centre. Both groups found
something that is both invisible and heavy,
forcing this jumble of stars to swirl around.
This invisible mass has about four million solar
masses squeezed together in a region no larger than our solar system. What is it that makes the stars
at the heart of the Milky Way swing around at such astonishing speeds? According to the current
theory of gravity, there is only one candidate – a supermassive black hole.
- If you are aspiring for Nobel prize you should take this class seriously! Estimation of the mass of the supermassive blackhole from observed positions of stars circling around it is a __nice example__ of data modelling, regression. :-)
- A nice summary [video](https://www.youtube.com/watch?v=KCADH3x56eE) (from 2009!) describing the discovery of our Milky Way's supermassive black hole and the technologies that made it possible. 
- Maximum Likelihood Estimation vs. Least Square Fit summary [slides](https://icsabai.github.io/classes/compsimf17em/Slides2019/leastSquares.pdf) and [notebook](https://nbviewer.jupyter.org/github/icsabai/simulationsMsc/blob/master/code/ch08_lineq_fitting/maximum_likelihood.ipynb)
- __Can we improve simple algorithms like multiplication?__
  - https://www.quantamagazine.org/mathematicians-discover-the-perfect-way-to-multiply-20190411/
  - https://hal.archives-ouvertes.fr/hal-02070778/document
  - Strassen method: https://en.wikipedia.org/wiki/Strassen_algorithm
  - Coppersmith–Winograd algorithm: https://en.wikipedia.org/wiki/Coppersmith%E2%80%93Winograd_algorithm)
  
### 2020.10.13
- [Chemistry Nobel Prize](https://www.nobelprize.org/prizes/chemistry/2020/press-release/) for CRISPR/Cas9 genome editing system
- Nemeth Robert's question from last class: _Where can I find a derivation for the fourth order Runge-Kutta method which follows a similar logic as the one for rk2 in Landau's book (in 9.5.2.)?_
  - __Answer__: I thought that it is presented in Numerical Recipes, but it seems that derivation of the 4th order Runge-Kutta is more tedious than I thought. It is not derived in the NR book, but I have found this "simplified" derivation: https://www.researchgate.net/publication/49587610_A_Simplified_Derivation_and_Analysis_of_Fourth_Order_Runge_Kutta_Method
- Ordinary Differential Equations - [explanation slides](https://icsabai.github.io/classes/compsimf17em/Slides2019/diffEq.pdf)
  - Predictor-Corrector Method [explanation](http://mathfaculty.fullerton.edu/mathews/n2003/abmmethod/adamsbashforthproof.pdf), local annotated [copy](https://icsabai.github.io/classes/compsimf17em/Slides2019/adamsbashforthproof.pdf)
  - Energy conservation [notebook](https://nbviewer.jupyter.org/github/ASU-CompMethodsPhysics-PHY494/PHY494-resources-2016/blob/master/08_ODEs/08_ODE-integrators-verlet.ipynb)
- __HW:__ Read Ch. 10-11

### 2020.10.20
- [Room temperature superconductivity](https://www.nature.com/articles/s41586-020-2801-z) achieved for the first time - though not at room pressure
  - <img src="https://www.nextbigfuture.com/wp-content/uploads/2020/10/diamondsuper-730x430.jpg" alt="image" width="300"/>
  - 1986: first ["high temperature"](https://en.wikipedia.org/wiki/High-temperature_superconductivity) superconducting material
- Methods for __differentiation and calculating gradients__, on emphasis on neural network weight optimization
  - [gradient methods animated figure](https://medium.com/datathings/neural-networks-and-backpropagation-explained-in-a-simple-way-f540a3611f5e)
  - [gradient methods described](http://ruder.io/optimizing-gradient-descent/)
  - [automatic differentiation](https://arxiv.org/pdf/1502.05767.pdf),  local annotated [copy](https://icsabai.github.io/classes/compsimf17em/Slides2019/automatic_differentiation_1502.05767.pdf)
  - autodiff: https://justindomke.wordpress.com/2009/02/17/automatic-differentiation-the-most-criminally-underused-tool-in-the-potential-machine-learning-toolbox/
  - [automatic differentiation short explanation](https://towardsdatascience.com/automatic-differentiation-explained-b4ba8e60c2ad)
- Visualization of multidimensional minimization [Loss Landscape](https://losslandscape.com/)
- Machine learning as a useful tool for cosmology studies: 
  - Francisco Villaescusa-Navarro et al. : The CAMELS project: [Cosmology and Astrophysics with MachinE Learning Simulations](https://arxiv.org/abs/2010.00619)  
  - Machine learning to [analyse](https://astronomycommunity.nature.com/posts/40395-learning-from-deep-learning) gravitational lensing observations
  - Machine learning to [replace](https://arxiv.org/pdf/1908.05519.pdf) N-body simulations
 - Machine learning in physics review: Carleo, G., Cirac, I., Cranmer, K., Daudet, L., Schuld, M., Tishby, N., Vogt-Maranto, L. and Zdeborová, L., 2019. [Machine learning and the physical sciences](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.91.045002). Reviews of Modern Physics, 91(4), p.045002. [arxiv](https://arxiv.org/pdf/1903.10563.pdf)
- __Fourier analysis, ch. 10__
  - [gravitational wave](https://github.com/icsabai/simulationsMsc/blob/master/code/ch10_fourier/LIGO/LOSC_Event_tutorial/LOSC_Event_tutorial.ipynb) data analysis from [LIGO Open Science Center](https://www.gw-openscience.org/)
  - Nyquist sampling theorem/ [compressive sensing](https://users.soe.ucsc.edu/~afletcher/EE293/Week1Readings/Papers_Week1_and_Week2/Baraniuk_SPMag2007.pdf)

