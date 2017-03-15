Toolbox: Random Bayes Network Generator
===
## Author 
[GA WU](mailto:wuga@mie.utoronto.ca), D3M Lab, MIE, University of Toronto

A Bayesian network, Bayes network, belief network, Bayes(ian) model or probabilistic directed acyclic graphical model is a probabilistic graphical model (a type of statistical model) that represents a set of random variables and their conditional dependencies via a directed acyclic graph (DAG).[Cite](https://en.wikipedia.org/wiki/Bayesian_network)

This code generates random Bayesian Network in [json format](http://www.json.org/), which corresponding to the import format of python package [libpgm](http://pythonhosted.org/libpgm/).

## Language
Python 2.7 + ipython

## Limitation
The current code only support Bayesian Network with following property:
1. Binary Variables(*)
2. Multiple Parents nodes
3. Single Child node(*)
4. Arbitrary number of nodes
Note: the stars are big limitation, please if it fits your requirement

## Instruction
Calling this module is very simple. You only need to instantiate one instance of BayesNet class and provide number of variables of the target Bayesian Network.

## Cite
```
@misc{wu_2017, 
title={TOOLBOX:Random Bayes Net Generator}, 
url={https://github.com/wuga214/TOOLBOX-Random-Bayes-Net-Generator}, 
journal={GitHub}, 
publisher={D3M Lab, MIE}, 
author={Wu, Ga}, 
year={2017}, 
month={Mar}}
```

