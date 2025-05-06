---
title: "Summer School"
description: "The 26th Conference on Integer Programming and Combinatorial Optimization"
featured_image: '/images/JHU.jpeg'
omit-header-text: true
type: page
menu:
  main:
    weight: 1
---

# Summer School 

The IPCO summer school will take place before the conference on June 9-10 2025.

## Program

Monday, June 9:
- 8:00 — 8:45: Registration and breakfast
- 8:45 — 9:00: Opening Remarks
- 9 — 10am: [Thomas Rothvoss](#thomas-rothvoss) -- [Introduction to Lattices](#lecture-1---introduction-to-lattices)
- 10 — 10:30: Coffee break
- 10:30 — 11:30am: [Daniel Dadush](#daniel-dadush) -- [Straight-line complexity of linear programs](#title-straight-line-complexity-of-linear-programs)
- 11:30 — 1:30pm: Lunch break
- 1:30 — 3:00pm: [Aida Khajavirad](#aida-khajavirad) -- [Binary polynomial optimization through a hypergraph theoretic lens: theory, algorithms, and applications](#title-binary-polynomial-optimization-through-a-hypergraph-theoretic-lens-theory-algorithms-and-applications)
- 3 — 3:30pm: Coffee break.
- 3:30 — 4:30pm: [Thomas Rothvoss](#thomas-rothvoss) -- [The Reverse Minkowski Theorem](#lecture-2---the-reverse-minkowski-theorem)

Tuesday, June 10:
- 8:30 — 9: Breakfast
- 9 — 10am: [Thomas Rothvoss](#thomas-rothvoss) -- [The Subspace Flatness Conjecture and Faster Integer Programming](#lecture-3---the-subspace-flatness-conjecture-and-faster-integer-programming)
- 10 — 10:30: Coffee break
- 10:30 — 11:30am: [Daniel Dadush](#daniel-dadush) --  [Straight-line complexity of linear programs](#title-straight-line-complexity-of-linear-programs)
- 11:30 — 1:30pm: Lunch break
- 1:30 — 3:00pm: [Aida Khajavirad](#aida-khajavirad) -- [Binary polynomial optimization through a hypergraph theoretic lens: theory, algorithms, and applications](#title-binary-polynomial-optimization-through-a-hypergraph-theoretic-lens-theory-algorithms-and-applications)
- 3 — 3:30pm: Coffee break.
- 3:30 — 4:30pm: [Daniel Dadush](#daniel-dadush) --  [Straight-line complexity of linear programs](#title-straight-line-complexity-of-linear-programs)

## Speakers and Abstracts

### Daniel Dadush
{{< figure src="images/dadush.jpg" alt="Daniel Dadush" height="400" >}}
Daniel Dadush is a senior researcher at CWI in Amsterdam and a part time full professor at Utrecht university. He completed his PhD at Georgia Tech within the Algorithmics, Combinatorics and Optimization program in 2012, and was a Simons postdoctoral fellow at the Courant Institute at NYU before joining CWI in 2014. He is a recipient of the 2015 A.W. Tucker prize for best thesis in mathematical optimization, as well as an ERC Starting Grant in 2019. His research focuses on the analysis and development of algorithms for linear and integer programming, both in the worst-case and beyond. 

#### Title: Straight-line complexity of linear programs

Path following interior point methods (IPM) together with the simplex
method are the two most popular techniques for solving linear programs. While
the length of a traversed simplex path has long been viewed as a good
combinatorial complexity measure for the simplex method, such a complexity
measure for IPM's has been missing until relatively recently. In this lecture
series, I will introduce the notion of straight line complexity (SLC) for linear
programs, which provides strong good combinatorial bounds on the iteration
complexity of IPMs.

In the first lecture, I will present an abstraction of IPMs that lends itself naturally
to an analysis via SLC, and explain the general properties of SLC and its
relation to the simplex method. In the second lecture, I will present upper
bounds on SLC based on well-known linear programming condition measures
and the structure of the constraint matrix, as well as highlight a worst-case
exponential lower bound. In the last lecture, I will present a primal-dual IPM
whose iteration complexity is upper bound by SLC up to a polynomial factor in
the number of inequalities.

### Aida Khajavirad
{{< figure src="images/khajavirad.jpg" alt="Aida Khajavirad" height="400">}}
Aida Khajavirad is an Assistant Professor of Industrial and Systems Engineering at Lehigh University. Before joining Lehigh, she worked at Rutgers University, University of Texas at Austin and IBM TJ Watson Research Center. She received her PhD from Carnegie Mellon University in 2012. Aida's research goal is to advance the state-of-the-art in Mixed-Integer Nonlinear Optimization (MINLP) at theoretical, algorithmic, and software levels. Recently, she has become interested in developing optimization algorithms with performance guarantees for data science applications. Her work has been recognized by the 2017 Young Researchers Prize by INFORMS Optimization Society and 2023 INFORMS Computing Society (ICS) prize by INFORMS Computing Society. Aida's research has been funded by NSF, DOE, and AFOSR. 

#### Title: Binary polynomial optimization through a hypergraph theoretic lens: theory, algorithms, and applications

We define the multilinear polytope as the convex hull of a set of
binary points satisfying a collection of multilinear equations. This set
corresponds to the convex hull of the feasible region of a linearized binary
polynomial optimization problem. By introducing a hypergraph representation
framework, we relate the complexity of the facial structure of the multilinear
polytope to the acyclicity degree of the corresponding hypergraph. We then
demonstrate how different degrees of acyclicity can be used to obtain compact formulations for the multilinear polytope in the original or in an
extended space. This in turn enables us to identify several classes of
polynomial-time solvable binary polynomial optimization problems. We then
introduce the pseudo-Boolean polytope, a generalization of the multilinear
polytope that can be modeled via signed hypergraphs. This general
framework enables us to unify and extend prior results and obtain polynomial
size extended formulations for the pseudo-Boolean polytope of a large class
of signed hypergraphs whose underlying hypergraphs contain cycles. We
then present some necessary conditions for polynomial-time solvability of
binary polynomial optimization as well as lower bounds on the extension
complexity of the pseudo-Boolean polytope. Moreover, we discuss the
implications of our findings on a number of applications such as inference in
higher-order graphical models and maximum satisfiability problems. We
conclude by discussing some open questions and directions of future
research.

### Thomas Rothvoss
{{< figure src="images/rothvoss.jpg" alt="Thomas Rothvoss" height="400">}}
Thomas Rothvoss is Professor in the Department of Mathematics and the Paul G. Allen School of Computer Science & Engineering at the University of Washington. He is broadly interested in discrete optimization, convex geometry, discrepancy theory and approximation algorithms. He is a co-winner of the 2018 Delbert Ray Fulkerson Prize and the 2023 Gödel Prize.

#### Lecture 1 - Introduction to Lattices

In this lecture, we will give a brief introduction to the lattices and discuss the
seminal result
of Micciancio and Voulgaris (2010) that gives a \(2^{O(n)}\) time algorithm for
computing a closest vector.
We will also discuss the result by Dadush and Vempala (2012) to enumerate
all the lattice points
in a general convex body K in time 2^O(n) times the maximum number of
points that any translate may contain.

#### Lecture 2 - The Reverse Minkowski Theorem

We explain the Reverse Minkowski Theorem due to Regev and Stephens-
Davidowitz (2017). Formally the

result states that for any lattice Lambda that does not contain a sublattice of
determinant less than 1,
the sum of Gaussian weights satisfies rho_1/t(Lambda) <= 3/2 where t =
Theta(log n).

In particular this implies that, any such lattice contains at most a quasi-
polynomial number of vectors of length at most O(1).

The result is based on advanced concepts from convex geometry.

#### Lecture 3 - The Subspace Flatness Conjecture and Faster Integer Programming

In a seminal paper, Kannan and Lovász (1988) considered a quantity
μ_KL(Λ,K) which denotes the best volume-based
lower bound on the covering radius μ(Λ,K) of a convex body K with respect
to a lattice Λ.
Kannan and Lovász proved that μ(Λ,K)≤n⋅μ_KL(Λ,K) and the Subspace
Flatness Conjecture by Dadush (2012) claims a O(log(n)) factor suffices,
which would match the lower bound from the work of Kannan and Lovász.
We settle this conjecture up to a constant in the exponent by proving that
μ(Λ,K)≤O(log^3(n))⋅μ_KL(Λ,K).
Our proof is based on the Reverse Minkowski Theorem due to Regev and
Stephens-Davidowitz (2017).
Following the work of Dadush (2012, 2019), we obtain a (log(n))^O(n)-time
randomized algorithm to solve
integer programs in n variables. Another implication of our main result is a
near-optimal flatness constant of O(n log^3(n)).
