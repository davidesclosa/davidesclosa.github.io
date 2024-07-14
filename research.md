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
I am broadly interested in relations between discrete and continuous structures.
This page presents some of my contributions.


<p style="display: flex; justify-content: space-between; align-items: center;">
  <span style="font-weight: bold; font-size: 20px;">Dynamical Systems on Graphs </span>
  <span style="color: gray; font-size: 20px;">#graph_theory #dynamical_systems</span>
</p>
Graph dynamical systems are given by a set of vertices, each representing some dynamical quantity, and a set of edges representing interactions among them.
The goal of this theory is relating the underlying combinatorial structure with the resulting dynamical phenomena.
I proved false a conjecture by constructing finite graphs supporting [infinitely many stable equilibria](https://epubs.siam.org/doi/10.1137/23M155400X).
I related [graph homology, graph coverings,](https://arxiv.org/abs/2308.08311) and [Eulerian paths](https://arxiv.org/pdf/2112.12034) to set of equilibria and stability.
Together with with C. Bick, I analyzed symmetries of [dynamics on graphons and graphops](https://link.springer.com/article/10.1007/s10884-023-10334-7).


<p style="display: flex; justify-content: space-between; align-items: center;">
  <span style="font-weight: bold; font-size: 20px;">Algebraic Groups over Finite Fields </span>
  <span style="color: gray; font-size: 20px;">#group_theory #algebraic_geometry</span>
</p>
Fix a linear algebraic group $$G$$ (for example $$\mathrm{GL}_m$$, $$\mathrm{SL}_m$$, $$\mathrm{SO}_m$$, $$\mathrm{Sp}_{2m}, \ldots$$).
By varying the underlying field we obtain a sequence of finite groups $$(G(\mathbb F_{p^n}))_{n\geq 0}$$.
The "limit object" $$G(\overline{\mathbb F_p})$$ (defined on an algebraic closure) is a smooth algebraic variety.
We call $$k$$ a *popular index* if for infinitely many $$n$$ the group $$G(\mathbb F_{p^n})$$ has a subgroup of index $$k$$.
I prove correspondence between [popular indeces and coverings of the limit object](https://www.degruyter.com/document/doi/10.1515/jgth-2022-0110/html?lang=en).
This problem was presented to me by P. Corvaja.


<p style="display: flex; justify-content: space-between; align-items: center;">
  <span style="font-weight: bold; font-size: 20px;">Bounded Power Series and Generating Functions </span>
  <span style="color: gray; font-size: 20px;">#analysis #combinatorics</span>
</p>
For a power series to be bounded on the real line, think of $$\sin(x)$$, $$e^{-x^2/2}$$, or $$e^{1-e^x}$$,
infinitely many monomials have to balance each other out, uniformly, on an unbounded set.
This is remarkable: in contrast, bounded power series on the complex plane are constant.
I relate [coefficients of a power series]((https://www.sciencedirect.com/science/article/pii/S0022247X24003706)) to boundedness of the resulting function.
This is particularly important in the case of bounded generating functions, like $$e^{1-e^x}$$, in which the coefficient sequence carries combinatorial meaning.
Moreover, I show that the set of real bounded power series supports three natural (but inequivalent) topologies and that the shift operator is invertible on a dense subset.
I am unable to close a certain gap, see conjecture 2.7.


<p style="display: flex; justify-content: space-between; align-items: center;">
  <span style="font-weight: bold; font-size: 20px;">Lagarias–Wang Finiteness Conjecture </span>
  <span style="color: gray; font-size: 20px;">#dynamical_systems #combinatorics</span>
</p>
The normalized spectral radius of an $$n$$-long product of two matrices $$A$$ and $$B$$ is the $$n$$-th root of its spectral radius.
The joint spectral radius is the supremum of the normalized spectral radii among all finite products.
The *Lagarias–Wang finiteness conjecture* states that this supremum is a maximum, that is, there is a finite product of $$A$$ and $$B$$ that realizes
the maximum normalized spectral radius. This conjecture is false for real matrices and open for rational matrices.
Together with G. Panti, I prove that [this conjecture holds](https://iopscience.iop.org/article/10.1088/1361-6544/ac0484/meta) in $$\mathrm{SL}_2(\mathbb Z_{\geq 0})$$.
We apply the result to the study of hyperbolic billiards.


<p style="display: flex; justify-content: space-between; align-items: center;">
  <span style="font-weight: bold; font-size: 20px;">Dynamic Random Graphs </span>
  <span style="color: gray; font-size: 20px;">#probability #combinatorics #dynamical_systems</span>
</p>
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

