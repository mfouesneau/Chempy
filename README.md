# Chempy
Flexible one-zone open box chemical evolution modeling. Abundance fitting and stellar feedback calculation

## Installation

```
pip install 'git+ssh://git@github.com/jan-rybizki/Chempy'
```

## Authors
- Jan Rybizki (MPIA, rybizki@mpia.de)

## Collaborators
- Hans-Walter Rix (MPIA)
- Andreas Just (ZAH)
- Morgan Fouesneau (MPIA)

## Links
- [Paper on overleaf](https://www.overleaf.com/read/jypbdqqqrdnp), Arxiv link following
- An early version of Chempy is presented [here](http://nbn-resolving.de/urn:nbn:de:bsz:16-heidok-199349).

## Installing Chempy
``Chempy`` is completely written in python 2.7. and is working with the latest verion. Its dependencies are: [Numpy](http://numpy.scipy.org/), [matplotlib](http://matplotlib.sourceforge.net/), [multiprocessing](https://docs.python.org/2/library/multiprocessing.html#module-multiprocessing) and [emcee](http://dan.iel.fm/emcee/current/) (for the MCMC), and [corner](http://corner.readthedocs.io/en/latest/) (for the MCMC plots). They are all pip installable and you can also get part of it with [Anaconda](https://www.continuum.io/downloads).

``Chempy`` itself can be cloned to your computer via
```
clone https://github.com/jan-rybizki/Chempy.git
```
## Getting started
The jupyter [tutorial](https://github.com/jan-rybizki/Chempy/tree/master/tutorials) illustrates the basic usage of Chempy and can be run on your local machine or just inspected in this github repository.
