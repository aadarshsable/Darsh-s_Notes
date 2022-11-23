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

***Proof:***
> Suppose $x,y$ are in $H$
> Then, $y^{-1}$ is also in $H$
> Thus $xy^{-1}$ is in $H$
> 
> 1. For $1_{g}$:
> 	   Let $x$ be any element of $H$.
> 	   Thus, $x\cdot x^{-1} = 1_{g}$ is in $H$
> 2. For Inverses:
> 	   As $1_{G}$ and $x$ are in $H$
> 	   Then, 
> 		   $1_{G}\cdot x^{-1} = x^{-1}$ 
> 	   is in $H$
> 3. For Products (binary operation):
>    We know $y^{-1}$ is in $H$
>    So, 
> 	   $x\cdot (y^{-1})^{-1} = xy$
> 	Is in $H$.
> 	
> Thus $H$ is subgroup of $G$


---------------------------------------------------

### Order of a Group:

Let $G$ be a group. The cardinality of the set $G$ (number of elements) is called the order of $G$

#### Finite Groups:

Let $G$ be a finite group.
then, $<x>$ (the subset of $G$) will also be a finite set.

***Theorem***
> Let $G$ be a finite group. Then, for any element $x$ of $G$, there exists a positive integer $d \leq |G|$ such that $x^{d} = 1$

***Proof***
> Let $|G| = r$
> In {$1, x, x^{2}\dots x^{r}$} all elements cannot be distinct.
> So, for some positive integers 
$$
\begin{align}
m&<n \\ \\

x^{m} &= x^{n} \\
x^{n-m} &= 1_{G} \\ \\

n \leq r &\implies n-m \leq r
\end{align}
$$
