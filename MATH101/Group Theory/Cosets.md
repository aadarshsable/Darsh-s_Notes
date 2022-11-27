Let $H$ be a a subgroup of $G$. If $g$ is any element of $G$, the set
$gH = \{ \:gh  \: | \: h \in H \: \}$
is called a **Left Coset** of $H$ or $G/$

Similarly, the set 
$Hg = \{\: hg \: | \: h \in H \: \}$
is called a **Right Coset** of $H$

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

