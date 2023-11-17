# Random Vector Generation

Underpinning some of the recents work for Contention Resolution Schemes(CRS), involves mechanisms which allow us to produce random vectors that satisfy various properties. This page collects some interesting artifacts and proofs about how we can translate properties of vectors in one space into schochastic independence to another via the use of linear maps.

## Basics 

Most of this note concerns itself with some finite field, denoted by \\( \mathbb{F}_{q} \\) 

We consider this field taken over some dimension m to be our "source" vector space, from which we can take vectors that satisfy properties, predominantly linear independence, and use this to produce stochastic independence in other vector spaces. In particular, consider the following, with X denoting a uniform distribution over {0....q-1}:

\\[ \mathcal{R} \in X^{d * m}, \phi(\sigma) = \mathcal{R}\sigma  \\]

## Result 1: A set of k-wise linearly independent can be mapped to k-wise independent vectors using \\(\mathcal{R}\\) 

### Proof: TODO


An interesting immediate corollary of this is that representable matroids in \\( \mathbb{F}_q^b \\) are actually preserved with respect to stochastic independence 
