## A. Motivation
- modelling *uncertainty* using data
- powerful tool to describe the complexities observed in the real world
	- the real world is both complex and uncertain because we *cannot measure* and model everything
## B. Applications
- $\exists\:$ many use cases for Probability and Statistics
	- takes complex processes and tries to simplify it to a simple random process

- can model a **deterministic dynamic system** using probability like a coin
	- uncertainty is present in the various quantity measurements that can be modelled probabilistically
	
1. Gas molecules (in `mol`) $\to$ **thermodynamic properties** like temperature, entropy etc. (these are statistical properties)

2. **Turbulence** (in fluids) $\to$ has multiple degrees of freedom involved

3. **Measurement Error** $\to$ when repeating an experiment $n$ times, we can obtain $\leq n$ different error values
	- error can be modelled after the normal or gaussian distribution curve
	- enables to quantify the uncertainty and measurement errors in physical systems and models

4. **Kalman filter** $\to$ merging dynamics & control with probability perspective

5. **Weather** $\to$ usually weather predictions, which is unpredictable in nature (chaotic development)

6. **Human behaviours**
## C. Some definitions
> **Probability** is assuming that we have a *known probability distribution* and we try to say something about the samples that we collect or observe in future
- allows us to **quantify the likelihood** of seeing $X$ out of $N$ outcomes

> **Statistics** is where we have *data which is known* and the *probability distribution is unknown*
- is essentially the flip side of statistics
## D. Course topic overview
1. **Introduction to Probability**
	- Examples and Intuitions
	- Counting sets of things that can occur (grouping events)

2. The **Abstraction of a Random Variable**
	- functions and distributions of random variables
	- probability of random variable $X$ with some parameters relating to that variable $\implies P(X \mid \theta_1, \theta_2, \ldots)$

	- Examples:
		- Bernoulli distribution for systems that have two outcomes only
		- Binomial distributions $\implies \sum$ independent Bernoulli variables (i.e. a bunch of coin flips)
		- Normal or Gaussian distributions $\implies \sum$ random variables
		- Poisson distribution for rare events
		- Exponential distribution

	- sometimes, the random probability distributions are **unknown** (which are machine learning problems)

3. **Functions of Random values** or Summary Statistics (how to we quantify in numbers)
	- Expected Value $E(X)$
	- Variance and Standard Deviation $\:\sigma(X)$
	- Median
	- we will be estimating these to say something about the probability distribution

4. **Central Limit Theorem**
	- point where we transition from probability to statistics instead
	- Given $X_i = 1, \: \ldots, \: n$, we have that $\bar{X} = \frac{1}{n} \sim\text{normal}(\mu, \sigma^2)$

5. **Hypothesis Testing** (Statistics)
	- already having the data collected from probabilistic events like coin flips etc., then we can test out hypothesis
	- say very quantifiable things
	- $P(\theta_1, \theta_2, \ldots \mid X) \implies$ what is the most likely model given the data

6. **Survey Sampling**
	- can we obtain population numbers just from a sample that is taken?

7. **Fitting Distributions and Estimating Parameters**