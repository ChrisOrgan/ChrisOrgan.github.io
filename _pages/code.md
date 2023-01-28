---
title: "Deep Time Biology Lab: Code"
layout: textlay
excerpt: "Deep Time Biology Lab: Code"
sitemap: false
permalink: /code/
---

# Code

We host our code on GitHub [here](https://github.com/ChrisOrgan) (main) and [here](https://github.com/JDGardner94) (Jacob Gardner). Code under active develop are in private repos, but please drop us an <a href="mailto:c.l.organ@reading.ac.uk">email</a> if you are interested in testing or collaborating.

### Sci-Phy (Science with Phylogenies)

![]({{ site.url }}{{ site.baseurl }}/images/respic/sciphyMCMC.gif){: style="width: 400px; float: left; border: 20px"}

Sci-Phy is a python library for phylogenetic comparative analysis. Sci-Phy can read in standard phylogenetic formats like nexus and Newick, as well as strings and sets. The library can be used to manipulate sets of trees (e.g., a Bayesian posterior samples) and comparative data, conduct simulations, and create advanced evolutionary models for categorical and numeric (continuous) data. It uses standard data science Python resources, like Pandas and NumPy, which can be scaled for high performance computing clusters using Dask.

Our near-term goal is to build novel sequential and Hamiltonian Markov chain Monte Carlo algorithms into Sci-Phy using PyMc. We are designing SciPhy to be developed by the computational biology community managed through GitHub under an MIT license. We plan on an initial release in 2023.

Sci-Phy is being developed in collaboration with [Andrew Meade](http://www.reading.ac.uk/biologicalsciences/about/staff/a-meade.aspx).

*The Sci-Phy logo to the left demonstrates a Bayesian MCMC sampler using [PyMC3](https://docs.pymc.io/) and [imcmc](https://github.com/ColCarroll/imcmc) (5 chains -- each chain is a different color, 8000 iterations).*

