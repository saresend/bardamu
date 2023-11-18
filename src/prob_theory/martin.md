# Martingales

In contrast to a lot of conventional probability theory, which takes independence as a "shield" against a lot of complex behavior to obtain results such as the strong law of large numbers and central limit theorems, Martingales, and more generally stochastic processes, are results obtained when we start relaxing assumptions about the independence of a series of random variables. 

This is motivated by the fact that a huge number of natural processes can be modeled via stochastic random processes, with varying assumptions made about the dependence of the change from one time to another in this process. 

## Filtrations 

Before defining what a martingale is, its helpful to start by explaining what a filtration means in the context of probability. Formally, a filtration is a sequence $\mathcal{F}_n$ 
of $\sigma$-algebras, that adhere to the property that $ \mathcal{F}_i \subseteq \mathcal{F}_{i+1}$

Why would we be interested in such a sequence? To motivate this definition, imagine some sequence of random variables which we observe sequentially. Say for example we are trying to understand a random walk, where at each step we step right or left a value of 1. Clearly, our position at some time t depends on the position that we were at previously, so the induced random variable (say its $S_n$), is not independent across time quanta. Before we get to analyzing these random variables, we need to define some algebra that it is measurable against. This is a filtration.

Now let's consider the $\sigma$-algebras induced by each $S_n$. At a given time step, range of values of $S_n$ induce a more "fine grained" sigma algebra than we had before. 

## What is a martingales

A martingale is a sequence of random variables that adhere to the
