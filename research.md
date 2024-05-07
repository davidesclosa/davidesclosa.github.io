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
    <li><a href="research" style="text-decoration: none; color: black;">Research</a></li>
    <li><a href="publications" style="text-decoration: none; color: black;">Publications</a></li>
    <li><a href="mailto:davide.sclosa@gmail.com" style="text-decoration: none; color: black;">Contact Me</a></li>
</ul>




# Research
I am broadly interested in connections between discrete and continuous structures, like
[finite graphs and dynamical systems](https://link.springer.com/article/10.1007/s10884-023-10334-7),
[finite groups and algebraic geometry](https://www.degruyter.com/document/doi/10.1515/jgth-2022-0110/html?lang=en),
[combinatorial sequences and analytic functions](https://www.sciencedirect.com/science/article/pii/S0022247X24003706),
[matrix semigroups and hyperbolic surfaces](https://iopscience.iop.org/article/10.1088/1361-6544/ac0484/meta).
I this page I present my contribution to these areas.

### Dynamical Systems on Finite Graphs and Graph Limits
Graph dynamical systems naturally occur as models of physical phenomena: vertices represent dynamical quantities and edges represent interactions between them.
There are fascinating relations between *combinatorial properties* and *collective behavior*. These are my contributions: contrary to popular belief, finite graphs can support [infinitely many stable equilibria](https://epubs.siam.org/doi/10.1137/23M155400X); the dimension of the equilibrium set
depends on the [number of cycles with common edges](https://arxiv.org/abs/2308.08311); nilpotent equilibria
are related to [Eulerian paths](https://arxiv.org/pdf/2112.12034); and (joint work with C. Bick) the theory of graph symmetries, a fundamental tool in the finite case, generalizes
to [dynamics on graphons and graphops](https://link.springer.com/article/10.1007/s10884-023-10334-7).

### Algebraic Groups Over Finite Fields
	
Linear algebraic groups over finite fields play a crucial role in the classification of finite simple groups.
Fix a linear algebraic group $$G$$ (for example $$\mathrm{GL}_m$$, $$\mathrm{SL}_m$$, $$\mathrm{SO}_m$$, $$\mathrm{Sp}_{2m}, \ldots$$).
By varying the underlying finite field we obtain a sequence of finite groups $$(G(\mathbb F_{p^n}))_{n\geq 0}$$.
On the other hand the "limit object" $$G(\overline{\mathbb F_p})$$ living on an algebraic closure is a smooth algebraic variety.
Let us call $$k$$ a *popular index* if for infinitely many $$n$$ the group $$G(\mathbb F_{p^n})$$ has a subgroup of index $$k$$.
I prove correspondence between [popular indeces and coverings](https://www.degruyter.com/document/doi/10.1515/jgth-2022-0110/html?lang=en) of the limit object.
This problem was presented to me by P. Corvaja.


### Bounded Power Series and Generating Functions

The existence of power series bounded on the whole real line, like $$\sin(x)$$ and $$e^{-x^2/2}$$,
is in itself a remarkable fact: infinitely many monomials have to balance each other out, uniformly, on an unbounded set
(in contrast, power series bounded on the complex plane are constant).
I study the set of [bounded power series on the real line]((https://www.sciencedirect.com/science/article/pii/S0022247X24003706)) and, in particular,
obtain necessary conditions on the coefficient sequence; this is particularly important in the case of bounded generating functions, like $$e^{1-e^x}$$, in which the coefficient sequence carries combinatorial meaning. On this matter, I am unable to close a certain gap, left as a conjecture.

### Lagarias–Wang Finiteness Conjecture

The normalized spectral radius of an $$n$$-long product of two matrices $$A$$ and $$B$$ is the $$n$$-th root of its spectral radius.
The joint spectral radius is the supremum of the normalized spectral radii among all finite products.
The *Lagarias–Wang finiteness conjecture* states that this supremum is a maximum, that is, there is a finite product of $$A$$ and $$B$$ that realizes
the maximum normalized spectral radius. This conjecture is false for real matrices and open for rational matrices.
Together with G. Panti, I prove that [this conjecture holds](https://iopscience.iop.org/article/10.1088/1361-6544/ac0484/meta) in $$\mathrm{SL}_2(\mathbb Z_{\geq 0})$$.
We apply the result to the study of hyperbolic billiards.

### Dynamic Random Graphs
To be announced.


<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>


<style>
	p {
    text-align: justify;
}
</style>

