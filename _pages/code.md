---
title: "Deep Time Biology Lab: Code"
layout: textlay
excerpt: "Deep Time Biology Lab: Code"
sitemap: false
permalink: /code/
---

# Code

We host our code on GitHub [here](https://github.com/ChrisOrgan). Code under active develop are in private repos, but please drop us an <a href="mailto:organ@montana.edu">email</a> if you are interested in testing or collaborating.

### Sci-Phy (Science with Phylogenies)

![]({{ site.url }}{{ site.baseurl }}/images/respic/sciphyMCMC.gif){: style="width: 500px; float: left; border: 20px"}

Sci-Phy is a python library for phylogenetic comparative analysis. Sci-Phy can read in standard phylogenetic formats like nexus and Newick, as well as strings and sets. The library can be used to manipulate sets of trees (e.g., a Bayesian posterior samples) and comparative data, conduct simulations, and create evolutionary models for categorical and numeric (continuous) data. It uses standard data science Python resources, like Pandas and NumPy, which can be scaled for high performance computing clusters using Dask. We are designing SciPhy to be developed by the computational biology community managed through GitHub under an MIT license. Sci-Phy is being developed in collaboration with [Andrew Meade](http://www.reading.ac.uk/biologicalsciences/about/staff/a-meade.aspx).

*The Sci-Phy logo to the left demonstrates a Bayesian MCMC sampler using [PyMC3](https://docs.pymc.io/) and [imcmc](https://github.com/ColCarroll/imcmc) (5 chains -- each chain is a different color, 8000 iterations).*

### Canopy

![]({{ site.url }}{{ site.baseurl }}/images/respic/Canopy.png){: style="width: 500px; float: right; border: 20px"}

[Canopy](https://github.com/ChrisOrgan/Canopy) is a free desktop app for viewing, editing and publishing evolutionary trees. It opens the common tree formats (Newick, NEXUS and phyloXML) and lets you build a figure layer by layer. You can add tip labels, support values, clade highlights, heatmaps of trait data, a geologic timescale, or animal silhouettes fetched automatically from PhyloPic. You edit the tree by clicking and dragging: reroot it, rotate or collapse clades, move a clade by dropping it on another branch, or copy a clade from one tree to another. For Bayesian or bootstrap analyses, Canopy can step through every tree in a sample, overlay them as a DensiTree, and build consensus or maximum clade credibility trees with their support values. Clicking any node shows its species and their data, along with tree-shape measures such as the Colless index and γ. When the figure is ready, it exports at publication quality as TIFF, PNG, SVG or PDF, sized for journal columns. Canopy runs on Windows, macOS and Linux and was built in Rust with the help of Claude Code.

