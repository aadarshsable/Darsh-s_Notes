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
