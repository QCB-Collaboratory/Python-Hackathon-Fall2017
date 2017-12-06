# Simulating the Hok/Sok genetic mechanism with the Gillespie algorithm

The Hok/Sok mechanism is an important duo of proteins that can be used as kill switch in synthetic biology. In this project, we will work on implementing the Gillespie algorithm, a Kinetic Monte Carlo method that efficiently simulates stochastic processes in continuous time.

<img src="figures/StochasticModel.png" width="600" />



### Primary goal

By the end of the Hackathon, you should have your own implementation of the Gillespie algorithm to simulate gene expression as a function of a few rate parameters.


### Technical challenges

* ...


### Guideline

1. Start by following this [notebook](GillespieProject.ipynb). It reviews the use of random numbers in Python and gives hints on how the Gillespie method works.

2.


### Resources

* A good start is the [Wikipedia page on the Gillespie Algorithm](https://en.wikipedia.org/wiki/Gillespie_algorithm).

* Are you trying to download the [notebook](GillespieProject.ipynb) to get started with the coding? To download the notebook, go to [this page](https://raw.githubusercontent.com/thmosqueiro/UCLA-Collaboratory_Hackathon/master/Materials_Resources/Problem-2/GillespieProject.ipynb), right click on the page and chose "save this page" (or something similar, depending on your browser). Then, save the file as GillespieProject.ipynb in the folder that you want to work on this project.

* Thisted, Thomas, and Kenn Gerdes. "Mechanism of post-segregational killing by the hok/sok system of plasmid R1: Sok antisense RNA regulates hok gene expression indirectly through the overlapping mok gene." Journal of molecular biology 223.1 (1992): 41-54.

* Gillespie, D.T. (1977). Exact stochastic simulation of coupled chemical reactions. J. Phys. Chem. 81, 2340–2361.

* Paulsson, J. (2005). Models of stochastic gene expression. Physics of Life Reviews 2, 157–175.

### Applications of the Gillespie algorithm:

* Dessalles, R., Fromion, V., and Robert, P. (2017a). A stochastic analysis of autoregulation of gene expression. J. Math. Biol. 1–31.

* Dessalles, R., Fromion, V., and Robert, P. (2017b). Models of protein production with cell cycle. ArXiv:1711.06378 [q-Bio].

* An [iGEM project](http://2015.igem.org/Team:Brasil-USP/Modeling/GeneExpression) that used Hok/Sok as kill switch for to control bio-engineered cells capable of degrading rubber.
