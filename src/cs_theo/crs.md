# Contention Resolution Schemes

## Introduction 

There are broad categories of problems that fall under the same, rather general format. These are problems that can be framed in the following fashion. You are given a ground set $E$, and some submodular function $f$, which we are trying to optimize subject some set of constraints on the allowed items we can select. In general, this describes a lot of interesting NP-hard problems. 

### Maximum Coverage Problem 

One example is the MCP problem - the problem is just about the simplest possible optimization of this form, and yet its still NP-hard. The problems asks for the following: given N different sets, pick $k$ of them such that the cardinality of their union is maximized. There are known approximations of $1 - \frac{1}{e}$, but in its exact form this is NP-hard. This is, essentially, the decision variant of the set cover problem. We could produce a minimum set cover algorithm that is comprised of calls to MCP, given some binary search structure. 

### Online contexts

Historically, problems of the above form are considered in an offline context. This would mean that we are given all of the values of the elements up front, and it is up to us to find the maximal set of these elements. If we are able to compute the total structure of the set of constraints (i.e. the matroid, knapsack, or other constraint set), then this would be rather trivial. However, the fundamental challenge is that we must enumerate our search space, which in general may well be too expensive. 



## Problems. 

1. Show that $g_e$ is convex

## Open questions 

1. Does order agnosticism provide advantage in more general cases? 







