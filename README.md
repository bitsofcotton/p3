# p3
Generic predictor based on some of the smooth surfaces.

# Description
If we can take multiplication invariant on f, S f(x) dx == S det(J((1,g\_0,...)/(1,x\_0,...))) dx\_0 ...

So we take first hypothesis as g\_0, ... is simple enough in f's addition, multiplication meaning.
(This is (g\_0 x y\) == (h\_0 x ...) simple enough meaning.)

So analogy to this, we take \[\[1, 1, ...\], \[g\_0, ...\], \[\parial g\_0/\partial x, ...\], ..., \[\partial^N g\_0/\partial x^N, ...\]\] for pseudo integration core.

However, to take whole integration multiplication invariant, we can shirk the integration to geometrics as det(...) == 0. So we should fit them.

We should list up simple function as g\_k first, then, we fit some of the jacobians next.

Also, with randtools General Tips AN, we should collect the viewpoint start points as {(1, f_k, g_k)}_k=1^k=n as such functions.

# Concept only in eternal
We don't implement this because we don't need them now.
So this is a concept only document.

# Flatten N
If original processor has infected on invariants, we might get better result with this 'one of a approximation with simple enough is the best' algorithm.
But in general, they might come from the software/hardware infection in low layers, so in their case, we cannot vanish them.

# Problem this calls
The description on this calls some of the problems s.t. det(J((1,g\_0,...)/(1,x\_0,...)))==0 when we're thinking about S f(x) dx.
The problem can be regarded as grid point on g\_0, ... the x\_0, ... produces can be in N^n or not.

# Multiple layer on this
We can use the ancestor of p3 as p0 because it's {1,x,x^2,...} series depends on {cis(t),cis(2t),...} seires.
So we might need some after layer on this on some of the complex structures this cannot handle. (eg. the series they doesn't converges.)

# Tips on continuous
This predictor inserts continuous part correctly.

Since p0 inserts continuous part as fixed and only one exist, they causes analytical singular point as nearly fixed places doesn't depend on input stream.

Also p1 inserts continuous part as the shrinked variable number structure itselves. This can slips by observation, nor this cannot treat the input stream structure as simple enough.
Since p1's numerical error of the linear invariant take depends on the structure complexity, either the structure also depends on higher dimension non tuned invariant structure, they needs to have analytical meaning correct, the p1 is not enough if input data stream size isn't enough. However, if we treat input status length long enough and multiple of the p1 apply, we might get same order result on the prediction differed this p3, so we don't need this now.

Either, ongoing deep learnings on some where we can find has enough meaning around continuity, however, doesn't touch the simplicity the learned function have, instead of simplicity, they have copy structure error tolerance rate.

