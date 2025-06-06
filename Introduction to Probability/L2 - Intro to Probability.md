## A. Coin Flips
> The probability of an event $A$, denoted $P(A)$ is given by the formula: $P(A) = \frac{\text{\# ways that A can happen}}{\text{total \# things that can happen}}$
- Probability is how to calculate the *likelihood* of a certain event
	- coin flips and dice rolls assume a uniform probability of all the events occurring
#### Using the counting method
- exhaustively list out all possibilities in both the event $A$ and the sample space $S$
>[!example] Example 1
> If I flip a coin twice, what is the probability:
> - $A =$ that I have at least one head
> - $B =$ there are no heads
> 
> $S = \{HH, HT, TH, TT\}$
> Then we have that $A =\{HH, HT, TH\} \implies P(A) = \frac{3}{4} = 0.75$
> 
> We also have: $B = \{TT\} \implies P(B)= 1 - P(A) =\frac{1}{4} = 0.25$
## B. Dice Rolls
>[!example] Example 2
> If I roll $2 \times$ fair six-sided dies and each roll is **independent** of the previous, then what is the probability that at least one of these die is a $5$?
> 
> $S = \{11, 12, 13, \ldots, 66\} \text{ and } \lvert S \rvert = 36$
> $A = \{15, 25, 35, 45, 51, 52, 53, 54, 55, 56, 65\} \text{ and } \lvert A \rvert = 11$
> $\therefore \: P(A) = \frac{11}{36} = 0.305 \quad \text{(to 2 d.p.)}$
#### Using the tree method
- can use the "tree" method to list out all the possibilities

#### Quantifying with formulas
$$
\begin{aligned}
P(A) &= P(D_1 = 5) + P(D_1 \neq 5) \cdot P(D_2=5) \\
&= \frac{1}{6} + \frac{5}{6} \times \frac{1}{6} \\
&= \frac{11}{36}
\end{aligned}
$$
## C. Randomness
- case where $\not \exists$ uniform probabilities (all outcomes may not have an equal chance)
- random is the idea that the outcome or event in question is **not deterministic** or hard to model deterministically $\implies$ requires a probabilistic model because it is **too hard to predict** with the current amount of information at hand

- have some situations which are actually random (i.e. the decay of a radioactive element)

**End note:** Probability is about modelling and counting what can happen, while Statistics is about matching the model with the data that was produced