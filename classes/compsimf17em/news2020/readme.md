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
- Project1 [ideas](https://icsabai.github.io/classes/compsimf17em/Slides2019/project1List.pdf)
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
 
### 2020.11.03
- Fourier analysis
  - Viusal interactive [explanation](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/) of Fourier analysis
  - IEEE Top 10 [algorithms](https://www.computer.org/csdl/magazine/cs/2000/01/c1022/13rRUxBJhBm) of the 20th century. Some [details](https://icsabai.github.io/classes/compsimf17em/Slides2019/TopTenAlgorithms.pdf)
  - [gravitational wave](https://nbviewer.jupyter.org/github/icsabai/simulationsMsc/blob/master/code/ch10_fourier/LIGO/LOSC_Event_tutorial/LOSC_Event_tutorial.ipynb) data analysis from [LIGO Open Science Center](https://www.gw-openscience.org/)
  - "FFT" on a sphere: [Cosmic Microwave Background radiation](https://github.com/sdam-elte/dslab2020/blob/master/projects/06-astro_CMB/AST5220_2_2011.pdf) analysis. Detailed example [notebooks](https://github.com/jeffmcm1977/CMBAnalysis_SummerSchool)
  - Nyquist sampling theorem/ [compressive sensing](https://users.soe.ucsc.edu/~afletcher/EE293/Week1Readings/Papers_Week1_and_Week2/Baraniuk_SPMag2007.pdf)
- Project2 [ideas](https://icsabai.github.io/classes/compsimf17em/Slides2019/project2List.pdf)
- __HW:__ Read Ch. 12 

### 2020.11.10
- Professional PDE codes:
  - [py-pde](https://pypi.org/project/py-pde/) (relatively simple, python)
  - Finite Volume: [OpenFoam](https://openfoam.org/) - [Python wrapper](https://pypi.org/project/PyFoam/)
  - Finite Element: [FEniCS](https://fenicsproject.org/)
- Project idea, "light saber" simulation
  - simulate electromagnetci knots, that are closed field lines of both electric and magnetic field lines
  - https://iopscience.iop.org/article/10.1088/2399-6528/aa9761
  - https://journals.aps.org/pre/pdf/10.1103/PhysRevE.101.063305
  - code 1: https://github.com/flaport/fdtd
  - code 2: [Meep](https://meep.readthedocs.io/en/latest/)
- [Fermi-Ulam-Pasta-Tsingou system](https://en.wikipedia.org/wiki/Fermi%E2%80%93Pasta%E2%80%93Ulam%E2%80%93Tsingou_problem) and original [paper](https://icsabai.github.io/classes/compsimf17em/Slides2019/FermiCollectedPapers1965.pdf)
- [Mary Tsingou's](https://icsabai.github.io/classes/compsimf17em/Slides2019/FUPT_Mary0801.1590.pdf) contribution to the Fermi-Ulam-Pasta study
- [Logistic map](https://en.wikipedia.org/wiki/Logistic_map) (nice animations)
- In 1975, [Dr. Feigenbaum](https://en.wikipedia.org/wiki/Mitchell_Feigenbaum), using the small [HP-65](https://en.wikipedia.org/wiki/HP-65) calculator discovered that the ratio of the difference between the values at which such successive period-doubling bifurcations occur tends to a constant of around 4.6692. 
- [Stretch-and-fold chaos](https://icsabai.github.io/classes/compsimf17em/Slides2019/strechAndFoldChaos.pdf) and the [horseshoe map](https://en.wikipedia.org/wiki/Horseshoe_map)
- [Coupled chaotic maps](https://en.wikipedia.org/wiki/Coupled_map_lattice)
- Chaos in [dripping faucet](https://icsabai.github.io/classes/compsimf17em/Slides2019/dripping_faucet_chaos.pdf) time series
- __HW:__ Read Ch. 13-14. 

### 2020.11.17
- Chaotic double pendulum [notebook](https://nbviewer.jupyter.org/github/icsabai/simulationsMsc/blob/master/code/ch09_ode/doublePendulum_2.ipynb)
- [Lorenz attractor](https://en.wikipedia.org/wiki/Lorenz_system) 
- Dimensionality of the underlying dynamics: [Taken's theorem](https://en.wikipedia.org/wiki/Takens%27s_theorem) and the  [Grassberger-Procaccia algorithm ](http://www.scholarpedia.org/article/Grassberger-Procaccia_algorithm) 
- make your own chaotic circuit: https://www.researchgate.net/publication/309351711_A_simple_chaotic_circuit_with_a_light-emitting_diode
- News: related to Grassberger-Procaccia algorithm and Takens theorem: 
  - 'AI Copernicus ‘discovers’ that Earth orbits the Sun' [review](https://www.nature.com/articles/d41586-019-03332-7)
  - [paper](https://arxiv.org/pdf/1807.10300.pdf)
  - Recovering Hamiltonian with machine learning [link](https://arxiv.org/pdf/1909.13789.pdf)
  - Asseman, A., Kornuta, T. and Ozcan, A., 2018. [Learning beyond simulated physics](https://openreview.net/pdf?id=HylajWsRF7).
    - real experimental [data to train machine learning](https://ibm.github.io/double-pendulum-chaotic-dataset/)
- Lotka-Volterra population dynamics [model](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations) and original hare-lynx [time series](https://www.math.uni-bielefeld.de/~sek/biomath/lotka.html)
- http://mc-stan.org/users/documentation/case-studies/lotka-volterra-predator-prey.html
- not only animal [population](https://academic.oup.com/bioscience/article/67/12/1026/4605229)
- COVID-19 ["agent based modeling"](https://www.google.com/search?q=agent+based+modeling+covid&oq=agent+based+modeling+covid) vs. [SIR model](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)
- __predator prey like systems in chemistry__: 
  - [Briggs–Rauscher oscillating reaction](https://en.wikipedia.org/wiki/Briggs%E2%80%93Rauscher_reaction) (nice video) 
  - [Belousov–Zhabotinsky reaction](https://en.wikipedia.org/wiki/Belousov%E2%80%93Zhabotinsky_reaction) (with simulation demo) and  [experiment video1](https://youtu.be/o72GGxQqWt8?t=65) , [video2](https://www.youtube.com/watch?v=jRQAndvF4sM)
  - Examples of more complex systems: [Citric acid cycle](https://en.wikipedia.org/wiki/Citric_acid_cycle) , [Metabolic pathway](https://en.wikipedia.org/wiki/Metabolic_pathway), "Google map" of [metabolic pathways](http://biochemical-pathways.com/#/map/1)
- __Chaotic simulation precision__
  - Sympletic integrators for nonlinear Hamiltonian systems: https://en.wikipedia.org/wiki/Symplectic_integrator
  - Corless, R.M., 1994. What good are numerical simulations of chaotic dynamical systems?. Computers & Mathematics with Applications, 28(10-12), pp.107-121. [link](https://www.sciencedirect.com/science/article/pii/089812219400188X)
  - Li, X. and Liao, S., 2018. Clean numerical simulation: a new strategy to obtain reliable solutions of chaotic dynamic systems. Applied Mathematics and Mechanics, 39(11), pp.1529-1546. [link](https://link.springer.com/article/10.1007/s10483-018-2383-6)
  - Boekholt, T.C.N., Portegies Zwart, S.F. and Valtonen, M., 2020. Gargantuan chaotic gravitational three-body systems and their irreversibility to the Planck length. Monthly Notices of the Royal Astronomical Society, 493(3), pp.3932-3937. [link](https://academic.oup.com/mnras/article-abstract/493/3/3932/5736044?redirectedFrom=fulltext) : _"... using the accurate and precise N-body code Brutus, which goes beyond standard double-precision arithmetic ... three massive black holes with zero total angular momentum, we conclude that up to five percent of such triples would require an accuracy of smaller than the Planck length in order to produce a time-reversible solution"_
- __Fractals:__
- [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set)
- News: [Onsager prize, Tamas Vicsek](https://physics.elte.hu/content/vicsek-tamas-lars-onsager-dijas.t.9536)
- [fractal dimension](https://en.wikipedia.org/wiki/Fractal_dimension)
  - [box counting method](https://en.wikipedia.org/wiki/Box_counting)
- [example fractal dimensions](https://en.wikipedia.org/wiki/List_of_fractals_by_Hausdorff_dimension)
- DNA fractal Peano-Hilbert globule [article](https://www.cell.com/fulltext/S0092-8674(14)01497-4) 
- Hear rate fluctuation dynamics [fractal](https://www.pnas.org/content/99/suppl_1/2466.full)
- Arnold's [cat map](https://en.wikipedia.org/wiki/Arnold%27s_cat_map)
- __HW:__ Read Ch. 15
