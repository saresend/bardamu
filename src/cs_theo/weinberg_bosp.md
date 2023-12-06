# Matroid BOSP Algorithm

## Introduction 

The initial exploration of prophet inequalities began with a simple, classical formulation of the problem. The problem is summarized as the following - imagine yourself a gambler, and you are given the following proposition - we will draw randomly from some sequence of distributions, call these $\mathcal{w}$, and reveal them to you one at a time. You are then given the choice to either "cash out", and select the value of $\mathcal{w}_i$ you are given, or, you can decline and keep playing with the hope of drawing a better lot later on. 

Once you've made your choice, you are weighed against a "prophet", someone who knows what all the eventual values are, and who picks the best possible option from those. Analyzing this problem by imagining yourself in competition with this prophet gives name to the topic of study.

## Mathematic formulation

Let's introduce the following notation and assumptions to clarify a rather simple, but instructive instance of the above. We consider a sequence of distributions $\mathcal{w}$, that are assumed to be independent. We can also define $\sigma$ to be the order in which the realizations of each distribution are shown (and $\sigma$ may itself be random). 

Further, we are measured against the following: for any choice $A$ that we select, it is compared against the $\mathbb{E}[\max_i w_i]$. Said another way, we should think we are playing against the expectation of the prophet. 

## 2 approximation for the simplest case




## Generalizations 

From the classic formulation, there already arise a lot of possible avenues to expand on this work. In general, we can explore what happens if we relax the assumption that $\mathcal{w}$ is mutually independent, or we can expand our selection to be more than a single element. We will explore the second generalization in the remainder of this note, with respect to some matroid constraints. 

## Relation to the classical secretary problem

