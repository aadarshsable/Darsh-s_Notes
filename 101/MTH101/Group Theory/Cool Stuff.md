## Finding If a Group is Cyclic

#### Primitive root modulo m
The Multiplicative Group $U(n)$ is Cyclic $iff$ the n is equal to $2,4,p^{k},2p^{k}$  where $p$ is a prime number and and $k \geq 1$

[***Proof of the Theorem***](https://www.maa.org/sites/default/files/269059834797.pdf](https://www.maa.org/sites/default/files/269059834797.pdf "https://www.maa.org/sites/default/files/269059834797.pdf")

## Finding Generators of a Cyclic Group

For any Group we have to Brute force atleast one generator to find other generators of the group $U(m)$

Now we will take help of the Theorem below to find the other generators

##### Theorem:
Finding generators of a cyclic group depends upon the order of the group. If the order of a group is $8$ then the total number of generators of group $G$ is equal to positive integers less than $8$ and co-prime to $8$.
The numbers $1 , 3, 5, 7$ are less than $8$ and co-prime to $8$, therefore if $a$ is the generator of $G$, then $a^{3}, a^{5}, a^{7}$ are also generators of $G$. Hence there are four generators of $G$.

[Source](https://math.stackexchange.com/questions/786452/how-to-find-a-generator-of-a-cyclic-group#:~:text=Finding%20generators%20of%20a%20cyclic,and%20co-prime%20to%208)

Now lets try to understand this with the help of an example

Check the cyclicity of $U(27)$ and find all its generators

