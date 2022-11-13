Let $A$ be a set with some *structure*.

$G =$ set of a permutations of $A$ preserving the 
  structure.

Then $G$ has the following Properties:

1. $id_{A}$ is in $G$
2. $f,g$ in $G$ $\implies$ $g\circ f$ is in $G$
3. $f$ in $G$ $\implies$ $f^{-1}$ in $G$
4. if $f,g,h$ are in $G$, then 
   $f\circ(g\circ h) = (f\circ g) \circ h$ 

**Note:**
> We can understand more about $A$ and its structure if we understand $G$ and its composition rule

To understand $G$ we need to find these Properties:
- $G$ is a set
- There is a rule or operation to combine two elements of $G$ to get a third element
- $G$ has $id$
- Inverses
- The rule is associative

### Binary Operations

Let $S$ be a set. A binary operation on $S$ is a function 

$\ast: S$ x $S \to S$

Here, $S$ x $S$ = set of ordered pairs $(x,y)$ where $x,y$ are in $S$
	The image of $(x,y)$ under $\ast$ will be written as $x \ast y$ instead of $\ast (x,y)$

Example:
> $\mathbb{N}$  $\to$ set of natural numbers
> 	Consider the function
> 	$\mathbb{N}$ x $\mathbb{N}$ $\to$ $\mathbb{N}$
> 	$(x,y)$ $\mapsto$ $x+y$
> This is a Binary Operation. (addition)

**Note:**
> We have already seen a associative binary operation example
> For, Non-Associative Binary Operation
> 	$\mathbb{Z}$ defined by
> 	$(a,b)$ $\mapsto$ $a-b$
> Then, if $a,b,c$ are in $\mathbb{Z}$
> 	$(a-b)-c = a-b-c$
> 	$a-(b-c) = a-b+c$
> This is NOT Associative

#### Properties of Groups:

A group consists of a set $G$ with a given binary operation 
	$\ast$ : $G$ x $G$ $\to$ $G$
	
Such that,

>1. There exists an element $1_{G}$ in $G$ such that 
		   $1_{G} \ast f = f \ast 1_{G} = f$
		for all $f$ in $G$ 
		
>2. For any $f$ in $G$ , there exists an element $f^{-1}$ such that
		   $f \ast f^{-1} = f^{-1} \ast f = 1_{G}$
		   
>3. $\ast$ is associative

Hence,
We wirte a group as $(G, \ast)$
and not just $G$


#### Existence of Groups:

Not every group will exist if it doesnt satify every group property

For Ex,
	- $\mathbb{N}$ is not a group for the bin.operation "+" as inverses do not exist
	- $\mathbb{R}$ does not exists under the operation "x"
	  However, 
		  $\mathbb{R}^x =$ set of non-zero real numbers
		  Then, $(\mathbb{R}^{x}, x)$ is a group

#### Some Important Properties:

- Let $A$ be any set with a *distance function*
  Then, the set of [[]] of $A$ is a Group

- The set of Isometries of a regular n-Gon is called the **Dihedral Group $(D_{n})$ of order $2n$ **

--------------
[Isometries]




