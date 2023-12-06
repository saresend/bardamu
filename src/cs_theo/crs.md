# Online Contention Resolution Schemes

## Introduction 

There are broad categories of problems that fall under the same, rather general format. These are problems that can be framed in the following fashion. You are given a ground set $E$, and some submodular function $f$, which we are trying to optimize subject some set of constraints on the allowed items we can select. In general, this describes a lot of interesting NP-hard problems. Different frameworks have been developed to try to tackle this class of problems in a number of different settings. Online Contention Resolution Schemes (OCRs), are one such framework, that can be developed for different classes of constraints. In particular, OCRs are designed for use in the online setting of these problems. 

## Examples of Problems 

### Maximum Coverage Problem 

The Maximum Coverage problem is one of the simplest possible optimizations of this form, and yet its still NP-hard. The problems asks for the following: given N different sets, pick $k$ of them such that the cardinality of their union is maximized. There are known approximations of $1 - \frac{1}{e}$, but in its exact form this is NP-hard. This is, essentially, the decision variant of the set cover problem. We could produce a minimum set cover algorithm that is comprised of calls to MCP, given some binary search structure. 


### Traveling Salesman 

$\textbf{TODO}$


### Online contexts

In many applications, we may not know the value of the elements we must consider in advance. For example, in the stock market we don't know whether the value of some asset will go up or down on a given day, nor by how much. We only learn that information on the day, and it is only then that we can take some action. To encode this into this general framework, we can model this through the following classical online problem.

### Bayesian Online Selection 

Consider some set of elements $E$, for which each element has an associated random weight to it, drawn from some distribution $F(x) x \in E$. 


## Problems. 

1. Show that $g_e$ is convex

## Open questions 

1. Does order agnosticism provide advantage in more general cases? 







