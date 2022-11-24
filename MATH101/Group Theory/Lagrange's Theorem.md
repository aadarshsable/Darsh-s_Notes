Let $d$ be the smallest +ve integer such that $x^{d}=1$.
If there doesnt exists any such $d$ 
Then, we say that $x$ has **infinite order**

Order is denoted as:  $ord(x)$ or $|x|$

***Theorem***
> Let $G$ be a finite group. Then , for any $x \in G$, 
> $ord(x) \leq |G|$

-----------------------------------

***Exercise***
Find all groups of order ***n=5***

Let $x \in G$, $x \ne 1$
Then, $2 \leq ord(x) \leq 5$

- If $ord(x)=2$
  > let $y \in G$ such that $y \notin <x>$
  > Our List: $1$ $x$
  >               $y$
  > $yx=1 \implies y=x^{-1}=x$                    ----contradiction
  > $yx=x \implies y=1$                              ----contradiction
  > $yx=y \implies x=1$                              ----contradiction
  > 
  > So, $yx$ is a new element
  > Our List Now: 1  $x$
  >                        $y$  $yx$
  >                        $z$
  >$z$ exists as $|G|=5$ 
  >
  >$zx=1 \implies z=x^{-1}=x$                ----contradiction
  >$zx=x \implies z=1$                          ----contradiction
  >$zx = y \implies z=yx^{-1}=yx$            ----contradiction
  >$zx=yx \implies z=y$                        ----contradiction
  >$zx=z \implies x=1$                         ----contradiction
  >
  >So $zx$ needs to be a new element but $|G|$
  >Thus $ord(x)\neq 2$

- If $ord(x)=3$
  >Our List: $1$  $x$  $x^{2}$
  >              $y$
  > The list should also contain $yx$ as theres $x$ and $y$
  > Thus now it becomes
  > Our List:  $1$  $x$  $x^{2}$
  >                $y$  $yx$
  > 
  > For $yx^{2}$
  > $yx^{2}=x^{n} \rightarrow y=x^{n-2}$                ----contradiction
  > $yx^{2}=y \implies x^{2}=1$                 ----contradiction
  > $yx^{2}=y \implies x=1$                  ----contradiction
  > So, $yx$ has to be a new element
  > But $|G|=5$ thus its not possible and
  > $ord(x) \neq 3$
  
- If $ord(x)=4$
  > Our List:  $1$  $x$  $x^{2}$  $x^{3}$
  >                 $y$  
  > $yx=x^{n} \rightarrow y=x^{n-1}$               ----contradiction
  > $yx=y \implies$

