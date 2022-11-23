Let $(G, \ast)$ be a group. A subgroup of $G$ is a subset $H  \subseteq  G$ such that $\ast$  gives a binary operation on $H$ , which gives $H$ the structure of a group.

#### Properties of a Subgroup

- $1_{G}$ is in $H$
- $x, y$ in $H$  $\implies$ $x \ast y$ in $H$
- $x$ in $H$ $\implies$ $x^{-1}$ in $H$

**Note**
> Any subgroup of $G$ that is not equal to the whole of $G$ is called a ***proper*** subgroup of $G$

-----------------------------------------

***Example***
	Let $G$ be a group and let $x$ be any elemebnt of $G$.
	Then, the set
$$
\begin{align}
<x> &= \{x^{n} | \textrm{ n is an integer } \} \\
&=\{ 1_{G}, x, x^{-1}, x^{2}, x^{-2} \dots \}
\end{align}
$$
	is a subgroup of $G$
	
------------------------------------------------------

***Example***
	Let $m$ be any interger.
	Define $m\mathbb{Z}$ to be the set of all integer multiples of $m$
	Then, $m\mathbb{Z}$ is a subgroup of $\mathbb{Z}$ as,
		it has a **inverse**
			$-x = m(-d)$
		it has $1_{g}$
		it has the same binary operation
			If, $x$ and $y$ are in $m\mathbb{Z}$
			Then, $x+y$ are in $m\mathbb{Z}$
$$
\begin{align}
x &= md_{1} \\
y &= md_{2} \\
x+y &=m(d_{1}+d_{2})
\end{align}
$$

-----------------------------------------

### A Test for Subgroups

Let $G$ be group. Let $H$ be a non-empty subset of $G$. 
Then $H$ is a subgroup of $G$ $iff$ for any $x, y$ in $H$
The element $xy^{-1}$ is in $H$

***Proof:***
> Suppose $x,y$ are in $H$
> Then, $y^{-1}$ is also in $H$
> Thus $xy^{-1}$ is in $H$

