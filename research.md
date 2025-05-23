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
I am interested in connections between discrete (finitary) and continuous (infinitary) mathematics. I am particularly interested in relations between combinatorics and dynamical systems. I like to work with graphs, maps, measures, groups, flows, generating functions, integer sequences. This page contains some of my contributions.

___

<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Deterministic Dynamics on Graphs</span>
  <span style="color: gray; font-size: 20px;">#dynamics #graphtheory</span>
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
  <span style="font-weight: bold; font-size: 20px;">Interactive Particle Systems and Dynamic Random Graphs </span>
  <span style="color: gray; font-size: 20px;">#probability #combinatorics #dynamics</span>
</p>

[This joint work](https://arxiv.org/pdf/2410.06807) with Christian Bick and Michel Mandjes concerns discrete-time occupancy processes on a finite graph, which include various types of interacting particle systems and random graph models as special cases. Our results can be formulated in two theorems, which are stated for vertex processes, but also applied to edge process (e.g., dynamic random graphs). The first theorem shows that concentration of
local state averages is controlled by a random walk on the graph. The second theorem concerns
concentration of polynomials of the vertex states. For dynamic random graphs, this allows to
estimate deviations of edge density, triangle density, and more general subgraph densities. Our
results only require Lipschitz continuity and hold for both dense and sparse graphs.

---

<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">Systems of Equations with Graph Structure </span>
  <span style="color: gray; font-size: 20px;">#combinatorics #graphtheory</span>
</p>

In this [joint work](https://arxiv.org/pdf/2410.06840) with Eddie Nijholt, we introduce a broad class of equations that are described by a graph, which includes many well-studied systems. For these, we show that the number of solutions (or the dimension of the solution set) can be bounded by studying certain induced subgraphs. As corollaries, we obtain novel bounds in spectral graph theory on the
multiplicities of graph eigenvalues, and in nonlinear dynamical system on the dimension
of the equilibrium set of a network.

---

<p style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
  <span style="font-weight: bold; font-size: 20px;">If you are the smartest person in the room, you are in the wrong room </span>
  <span style="color: gray; font-size: 20px;">#combinatorics #algorithms</span>
</p>

[If taken seriously](https://arxiv.org/pdf/2407.08042), the advice in the title leads to interesting combinatorics. Consider $$N$$ people moving between $$M$$ rooms as follows: at each step, simultaneously, the smartest person in each room moves to a different room of their choice, while no one else moves. The process repeats. Let $$G(N,M)$$ be the directed graph with vertices representing the possible $$M^N$$ configurations and edges representing possible moves. We classify the pairs $$(N,M)$$ such that every
configuration can be reached from every other. More precisely, we prove that
the graph $$G(N,M)$$ is strongly connected if and only if $$M\geq N+1$$ (one extra
room for maneuvering is both required and sufficient). In the case $$M\leq N$$, we
explicitly describe strongly and weakly connected components. In particar, we see the emergence of a giant component. Proofs are either impossibility arguments, or explicit algorithms based on subgroups generated by derangements.


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

