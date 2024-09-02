<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Title Tag -->
    <title> Davide Sclosa - Research</title>
    
    <!-- Description Meta Tag -->
    <meta name="description" content="Learn more about my research in combinatorics and dynamical systems and algebra and analysis.">
    
    <!-- Keywords Meta Tag -->
    <meta name="keywords" content="Davide, Sclosa, Davide Sclosa, math, graph, graphs, graph theory, dynamics, network, networks, synchronization, combinatorics, graph limits, research, finite fields, mathematics, Kuramoto, Ramsey, additive, discrete, random, manifolds, invariant, measure, groups, group theory, Amsterdam, rooms, algebra, bounded, generating, equilibria, diffusion, smartest, symmetries, analysis, ergodic, concentration, inequalities, coloring, decomposition, progressions, arithmetic, norms, rational, generating function, Bell numbers, Uppuluri-Carpenter numbers, Stirling, graphon, graphop, graphons, graphops, Lagarias, Wang, conjecture, Eulerian, simple, isogeny">
</head>

<style>
.container {
    position: relative;
}

.menu {
    position: absolute;
    top: 10px;
    right: 10px;
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.menu li {
    display: inline;
    margin-left: 10px;
}

.menu li:first-child {
    margin-left: 0;
}
</style>

<ul class="menu">
    <li><a href="index" style="text-decoration: none; color: black;">Home</a></li>
    <li><a href="publications" style="text-decoration: none; color: black;">Publications</a></li>
    <li><a href="cv.pdf" download style="text-decoration: none; color: black;">CV</a></li>
    <li><a href="mailto:davide.sclosa@gmail.com" style="text-decoration: none; color: black;">Contacts</a></li>
</ul>




# Research
I am interested in connections between discrete and continuous structures in mathematics, in particular, in combinatorics and dynamical systems. I like to work with graphs, maps, measures, groups, flows, generating functions, integer sequences. This page contains some of my contributions.

___

<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Dynamical Systems on Graphs</span>
  <span style="color: gray; font-size: 20px;">#graphtheory #dynamics</span>
</p>
Every vertex of a graph respresents a dynamical quantity and every edge represents an interaction. Think, for example, of a group of people exchanging opinions, neural network firing, a self-replicating machine in a cellular automaton, a graph with vertices turning on and off at random according to the state of the adjacent vertices. I am interested in relations between combinatorial structure of the graph and resulting dynamics. The followings are some of my findings.
The dimension of the equilibrium set can be bounded
[from above using graph homology, and from below using graph covering](https://arxiv.org/abs/2308.08311).
In contrast to a popular conjecture, finite graphs can support [infinitely many stable equilibria](https://epubs.siam.org/doi/10.1137/23M155400X).
Nilpotent equilibria in Kuramoto networks are classified by [Eulerian paths](https://arxiv.org/pdf/2112.12034).
Together with with C. Bick, I analyzed symmetries of [dynamical systems on graph limits](https://link.springer.com/article/10.1007/s10884-023-10334-7).

___

<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Algebraic Groups over Finite Fields</span>
  <span style="color: gray; font-size: 20px;">#grouptheory #algebraicgeometry #numbertheory</span>
</p>

The classification of finite simple groups, the building blocks of all finite groups, is one of the greatest achievements in mathematics.
In the classication, a central role is played by linear algebraic groups defined over finite fields.
Fix a linear algebraic group $$G$$ (for example $$\mathrm{GL}_m$$, $$\mathrm{SL}_m$$, $$\mathrm{SO}_m$$, $$\mathrm{Sp}_{2m}, \ldots$$).
Consider the sequence of finite groups $$(G(\mathbb F_{p^n}))_{n\geq 0}$$ obtained by varying the underlying field.
The "limit object" $$G(\overline{\mathbb F_p})$$, the group over on an algebraic closure, is a smooth algebraic variety.
Let $$k$$ be a *popular index* if for infinitely many $$n$$ the group $$G(\mathbb F_{p^n})$$ has a subgroup of index $$k$$.
I prove correspondence between [popular indeces and coverings of the algebraic variety](https://www.degruyter.com/document/doi/10.1515/jgth-2022-0110/html?lang=en).
This problem was presented to me by P. Corvaja.

___
<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Lagarias–Wang Finiteness Conjecture</span>
  <span style="color: gray; font-size: 20px;">#ergodictheory #combinatorics</span>
</p>

The normalized spectral radius of an $$n$$-long product of two matrices $$A$$ and $$B$$ is the $$n$$-th root of its spectral radius.
The joint spectral radius is the supremum of the normalized spectral radii among all finite products.
The *Lagarias–Wang finiteness conjecture* states that this supremum is a maximum, that is, there is a finite product of $$A$$ and $$B$$ that realizes
the maximum normalized spectral radius. This conjecture is false for real matrices and open for rational matrices.
Together with G. Panti, I prove that [this conjecture holds](https://iopscience.iop.org/article/10.1088/1361-6544/ac0484/meta) in $$\mathrm{SL}_2(\mathbb Z_{\geq 0})$$ using combinatorics on words and hyperbolic geometry.
We apply the result to the study of hyperbolic billiards.

___
<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Bounded Power Series and Generating Functions</span>
  <span style="color: gray; font-size: 20px;">#analysis #combinatorics</span>
</p>

For a power series to be bounded on the real line, think of $$\sin(x)$$, $$e^{-x^2/2}$$, or $$e^{1-e^x}$$,
infinitely many monomials have to balance each other out, uniformly, on an unbounded set.
This is a remarkable phenomenon: in contrast, bounded power series on the complex plane are constant.
I relate [coefficients of a power series](https://www.sciencedirect.com/science/article/pii/S0022247X24003706) to boundedness of the resulting function.
Such results are particularly important for bounded generating functions, like $$e^{1-e^x}$$, in which the coefficient sequence carries combinatorial meaning.
Moreover, I show that the set of real bounded power series supports three natural (but inequivalent) topologies and that the shift operator is invertible on a dense subset.
I am unable to close a certain gap, see Conjecture 2.7. Speciality coffee is offered for the solution. ☕️

___

<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Dynamic Random Graphs</span>
  <span style="color: gray; font-size: 20px;">#probability #combinatorics #dynamics</span>
</p>

To be announced.


<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

___

<style>
	p {
    text-align: justify;
}
</style>

