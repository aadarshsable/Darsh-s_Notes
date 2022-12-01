Let $H$ be a a subgroup of $G$. If $g$ is any element of $G$, the set
$gH = \{ \:gh  \: | \: h \in H \: \}$
is called a **Left Coset** of $H$
The set of all the Left cosets is denoted by $G/H$

Similarly, the set 
$Hg = \{\: hg \: | \: h \in H \: \}$
is called a **Right Coset** of $H$ 
The set of all Right cosets is denoted by $H/G$

***Theorem***
> Given Left Cosets $g_{1}H$ and $g_{2}H$ of H,
> either
> $g_{1}h \subseteq \: g_{2}H = \phi$
> OR
> $g_{1}H = g_{2}H$

***Proof:***
>Suppose $g_{1}H \subseteq \: g_{2}H \neq \phi$
>Then, $g_{1}h_{1} = g_{2}h_{2}$
>So, $g_{1}=g_{2}h_{2}h_{1}^{-1}$
>Then for some $h \in H$ 
>	$g_{1}\cdot h=g_{2}(h_{2}h_{1}^{-1}\cdot h) \in g_{2}H$
>So,
>	$g_{1}H \subseteq g_{2}H$
>So, $g_{2}=g_{1}h_{1}h_{2}^{-1}$
>Then for some $h \in H$ 
>	$g_{2}\cdot h=g_{1}(h_{1}h_{2}^{-1}\cdot h) \in g_{2}H$
>So,
>	$g_{2}H \subseteq g_{1}H$
>Thus,
>	$g_{1}H=g_{2}H$

***Note***
> 1.The union of all left cosets of $H$ is $G$
>   Similarly for the right cosets
> 2. Two distinct left cosets do not intersect

Hence the left cosets of $H$ gives a partition of $G$

----------------------------------------

### Cardinality of Cosets

If $H$ is finite, we see that
$$
|gH| = |H|
$$
for any $g \in G$

***Theorem***
> Let $G$ be a finite group and $H$ be a subgroup of $G$
> Then $|H|$ divides $|G|$

***Proof***
>As $G$ is a finite set, the set $G/H$ is also finite
>$G$ is the union of all the left cosets of $H$. Any two distinct cosets are disjoints.
>For any coset $gH$, we have 
>	$|gH| = |H|$
>	$|G| = |G/H| \cdot |H|$
> So, $|H|$ divides $|G|$

-------------------------

### Visualizing Cosets

Let $G=D_{6}$
The elements are
$$\begin{align}
1 \: \rho \: \rho ^{2} \: \rho ^{3}& \: \rho ^{4} \rho ^{5}  \\
\tau \:\:\rho \tau \:\: \rho ^{2}\tau \:\: \rho ^{3}\tau & \:\: \rho ^{4}\tau \:\:\rho ^{5}\tau
\end{align}

$$
We also have
$\rho ^{6}=1$ , $\tau ^{2}=1$ , $\rho \tau = \tau \rho ^{-1}$

Left Cosets of $H=\{1, \tau \}$

![[Pasted image 20221127145434.png]]

Right cosets of $H=\{1 , \tau \}$

![[Pasted image 20221127145534.png]]

***NOTE***
> 1. Both left and right cosets give partitions of the group.
> 2. Right cosets of a group may be very different from the left cosets.

-------------------------------

#### SubGroups of $\mathbb{Z}$

We know that if $m$ is any integer, the set 
	$m\mathbb{Z} = \{ \:mx \: | \: x\in \mathbb{Z} \}$
is a subgroup of $\mathbb{Z}$

----------------------------------------------

### Well Ordering Principle

Any non-empty set of positive integers has a smallest member

***Non-Examples***
	1. $\mathbb{R}$ has no smallest element
	2. $\mathbb{R}_{+}$ has a lower bound but no smallest element

#### Generalization

Let $S \subseteq \mathbb{Z}$ be a non-empty subset that has a lower bound
i.e, there exists some $x_{o} \in \mathbb{Z}$ such that $x \geq x_{o} \forall x \in S$ 
Then $S$ has a smallest element.

***Proof:***
> Let $T = \{x-x_{o}+1 \: | \: x \in S \}$
> Then $T$ consists of positive integers. Also, $T$ is a non-empty.
> $T$ has a smallest element $z$. Then $z=y-x_{o}+1$ for some $y \in S$
> We claim that $y$ is the smalleset element of $S$
> If not then there exists some $x \in S \rightarrow x <y$
> But $x-x_{o}+1 \in T$ and $z$ is the smallest element of $T$  ---- contradiction
> 

Thus the well-ordering principle applies to non-empty subsets of  non-negative integers as well

-----------------------------------------

### Division Algorithm

Let $a,b \in \mathbb{Z}$ , $b > 0$ 
Then there exists a unique integers $q,r$ such that
$$a=bq+r
$$
and
$$
0 \leq r < b
$$
***Note:*** 
$r$ is strictly less than $b$ and greater than equal to $0$

***Proof***
> $S= \{ a-bm \: | \: m \in \mathbb{Z} , \: a-bm \geq 0\}$
> We claim that $S$ is non-empty
> 
> Case-1
> 	$a \geq 0$
> 	$a=a-b \cdot 0 \in S$
>  Case-2
> 	 $a <0$
> 	 Then $a-b(2a)=a(1-2b)$
> 	 As $b\geq1 \implies 1-2b < 0$
> 	 Thus, $a(1-2b) > 0$
> 	 So $a-b(2a) \in S$
> 	 Hence $S$ is non-empty here
> 	 So, $S$ has a smallest element, which we denote by $r$.
> 	 As $r \in S$,
