# Maximum-volume lattice polytopes with a prescribed number of interior lattice points

How large can the volume of a lattice polytope be if its dimension and the number of lattice points in its interior are fixed? This repository collects three papers on the Zaks–Perles–Wills volume conjecture.

## Papers

| Manuscript | Main result |
| --- | --- |
| *The Zaks–Perles–Wills volume conjecture I: three-dimensional lattice polytopes* | For $k\ge 3$ interior lattice points, the maximum Euclidean volume is $6(k+1)$. The inequality is strict for lattice width at least three. Together with the known cases $k=1,2$, this settles dimension three. |
| *The Zaks–Perles–Wills volume conjecture II: lattice simplices* | For lattice simplices in every dimension $d\ge 4$ and every $k\ge 1$, the paper proves the sharp bound and characterizes equality by counting lattice points in barycentric coordinates. |
| *The Zaks–Perles–Wills volume conjecture for lattice polytopes* | For arbitrary lattice polytopes in every dimension $d\ge 4$ and every $k\ge 1$, the paper proves the sharp bound by induction on rational sections. At equality, a long edge of a section determines the maximizing polytope. |

The first two papers are by Feihu Liu, Jinlong Tang, Sihao Tao, and Zihao Zhang.

## The sharp bound and its equality cases

Let $P\subset\mathbb{R}^d$ be a full-dimensional lattice polytope with exactly $k\ge 1$ interior lattice points, where $d\ge 3$. Write $\mathrm{Vol}_d(P)$ for its normalized volume, equal to $d!$ times its Euclidean volume in standard lattice coordinates. The bound is

$$
\mathrm{Vol}_d(P)\le (k+1)(s_d-1)^2,
$$

where $s_1=2$ and $s_{j+1}=1+\prod_{i=1}^{j}s_i$ for $j\ge 1$. The first terms of this Sylvester sequence are $2,3,7,43$.

With $e_1,\ldots,e_d$ the standard basis, the Sylvester simplex

$$
S_{d,k}=\mathrm{conv}(0,s_1e_1,\ldots,s_{d-1}e_{d-1},(k+1)(s_d-1)e_d)
$$

attains the bound. It is the unique maximizer up to affine unimodular equivalence except when $(d,k)=(3,1)$. In that case there are exactly two maximizers, $S_{3,1}$ and $\mathrm{conv}(0,2e_1,6e_2,6e_3)$, both of normalized volume $72$.
