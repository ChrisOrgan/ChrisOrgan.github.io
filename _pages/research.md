---
title: "Macroevolution Lab - Research"
layout: textlay
excerpt: "Macroevolution Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

![]({{ site.url }}{{ site.baseurl }}/images/respic/Graphical_Abstract.png){: style="width: 200px; float: right; border: 10px"}

Our overarching research goal is to understand how the genotype and phenotype coevolve across major evolutionary transformations during the history of life. This is a central problem in macroevolutionary theory: the large-scale patterns and processes of evolution. We tackle this work with a wide range of data, from genomic sequencing and histology to physiology and the fossil record. Our team creates and applies bioinformatic and data science models to marry these multidisciplinary data under the principle of consilience.

### PyPhy & Comparative Methods

![]({{ site.url }}{{ site.baseurl }}/images/respic/pyphy_mcmc.gif){: style="width: 400px; float: left; border: 10px"}

PyPhy is a general purpose library for the statistical analysis, modelling, and machine learning of evolved data using phylogenetic trees (phylogenetic comparative methods). Functions include phylogenetic EDA, plotting, and modelling of continuous and categorical data in reference to evolutionary (phylogenetic) trees. Most of the solutions are Bayesian (Hamiltonian Markov chain Monte Carlo) and account for varying levels of uncertainty across the data and a tree or posterior distribution of trees. PyPhy is being developed in collaboration with [Andrew Meade](http://www.reading.ac.uk/biologicalsciences/about/staff/a-meade.aspx) at the University of Reading, UK.

*The PyPhy logo to the left demonstrates a Bayesian MCMC sampler using [PyMC3](https://docs.pymc.io/) and [imcmc](https://github.com/ColCarroll/imcmc) (5 chains -- each chain is a different color, 8000 iterations).*

### Macroevolutionary & Paleo- Genomics

![]({{ site.url }}{{ site.baseurl }}/images/respic/genome_punc.png){: style="width: 300px; float: right; border: 10px"}

Our work in this area uses macroevolutionary models to integrate genomic and fossil data. For example, our work on the coelacanth genome revealed genetic adaptations in the urea cycle during the water-to-land transition in vertebrates roughly 375 mya. We are currently interested in punctuated genome evolution in vertebrates. We have developed a novel regression model that can automatically detect different trends in data. We are using this model to find shifts between gradual and punctuated evolution across a comprehensive sampling of vertebrate gene trees. This work is part of a study on the genomes of “living fossils” (e.g., *Lingula*, *Crocodylus*, and *Eptatretus*).

*The figure to the right shows a Bayesian test for shifts in evolutionary mode in the FGF family. A). The gene family tree with FGF10 in blue and FGF22 in red. B) The means of the posterior regression lines. Center line for all the data, top (blue) is the line for FGF10, which suggests punctuated evolution and bottom (red) is the line for FGF22, which suggests gradual evolution. A shift in the mode of evolution is suggested by the gradual and punctuated lines (Bayes factor of 14).*

### Evolutionary Dynamics of Sex Chromosomes

Sex chromosome evolution is a subject of great interest across biology because it underlies health and welfare, as well as reproductive success. But how do sex chromosomes arise, and what is their relationship with environmental change over geologic time scales? In previous work, we found that the XY system (e.g., the system in mammals) is more labile and evolves faster than does the ZW system (e.g., the system in birds and snakes). We also discovered that live birth evolves only after the prior evolution of sex chromosomes, and we used this relationship to demonstrate that Mesozoic marine reptiles possessed sex chromosomes. We are expanding the trajectory of this research with a  study the evolutionary dynamics of sex chromosomes by developing a model that allows the rate of categorical traits to vary across time. Preliminary results imply that shifts in hormonal thresholds during development are the mechanism by which sex-determining systems evolve. A goal for future work focuses on leveraging these models to understand sex determination in dinosaurs.

### Evolutionary Ecophysiology: Form, Function, and Habitat

![]({{ site.url }}{{ site.baseurl }}/images/respic/phylogeo.png){: style="width: 400px; float: left; border: 10px"}

How do species adapt to new environmental challenges, ecological interactions, and balance internal constraints over geologic timescales? We apply a wide variety of quantitative statistical tests to morphological and histological data to clarify the evolution of form and function. For example, we recently showed that display structures were related to the evolution of gigantism in carnivorous dinosaurs using several methods that allow the rate of evolution to vary over time. We are now investigating the rapid evolution of gigantism in terror birds, shifts in dinosaur body size across extinction horizons, and the paleogeography of early tetrapods. We are also studying how locomotor systems evolve in Mesozoic mammals and dinosaurs.

*The figure to the left shows a spherical geographical model of evolution for Hominoidea (apes). A. A model in which the rate of geographic location ((paleo) longitude and latitude) is allowed to vary is overwhelmingly favored compared with a model in which the rate of geographic evolution (migration) is uniform. B. A phylogeny color-coded with varying rates of geographic evolution. The Google Map icons designate Hominoidea including its stem members. C. Phylogenetic estimation for the geographical origin of Hominoidea. The red icon, located at the northern border of present-day Kenya, is the estimation using a standard Brownian motion model. The green icon, located in northern Tanzania, is estimated using the global model of evolution.*