# Probability
## Table of Contents
- [Section 10: Combinatorics](#section-10-combinatorics)
- [Section 11: Bayesian Inference](#section-11-bayesian-inference)
- [Section 12: Distributions](#section-12-distributions)
***
### Section 10: Combinatorics

| Type | Without Repetition | With Repetition |
|------|-------------------|-----------------|
| Permutation: Arrange | $P_n = n!$ |  |
| Variation: Arrange + Pick | $V_{n,p} = \frac{n!}{(n-p)!}$ | $V_{n,p}^{\bar{}} = n^p$ |
| Combination: Pick (order doesn't matter) | $C_{n,p} = \frac{n!}{p!(n-p)!}$ | $C_{n,p}^{\bar{}} = \frac{(n+p-1)!}{p!(n-1)!}$ |

> Note: $n$ = number of objects, $p$ = number of objects to pick
> $C = \frac{V}{P!}$ if there is no repetition

### Section 11: Bayesian Inference

This section is covering the main probabilities formulas then the Bayer's theorem.

| Event Type | Notation | Description | Notes |
|------------|----------|-------------|-------|
| Union | $A \cup B$ | Events A **or** B occur |
| Intersection | $A \cap B$ | Events A **and** B occur together |
| Mutually Exclusive | $P(A \cap B) = 0$ | Events cannot occur together | Complements ⟹ mutually exclusive |


| Formula Type | Expression |
|-------------|------------|
| Independent Events | $P(A \cap B) = P(A) \times P(B)$ |
| Dependent Events | $P(A \cap B) = P(A) \times P(B\|A)$ |
| Conditional Probability | $P(A\|B) = \frac{P(A \cap B)}{P(B)}$ <br> $P(B\|A) = \frac{P(A \cap B)}{P(A)}$ |
| Law of Total Probability | $P(A) = P(A\|B) \times P(B) + P(A\|\overline{B}) \times P(\overline{B})$ |
| Additive Rule | $P(A \cup B) = P(A) + P(B) - P(A \cap B)$ |
| Multiplicative Rule | $P(A \cap B) = P(A) \times P(B\|A)$ <br> $P(A \cap B \cap C) = P(A) \times P(B\|A) \times P(C\|A \cap B)$ |
| Bayes' Theorem | $P(A\|B) = \frac{P(B\|A) \times P(A)}{P(B)}$ |

### Sectin 12: Distributions

Distribution: the possible value a varaibale can take and how frequently it occurs.

#### Discrete Distributions
For finite number of possible outcomes

| Distribution | Notation | Notes |
|--------------|----------|-------------|
| Uniform | U(a,b) | all values are equally likely <br> μ and σ² are not interpretable <br> \(\rightarrow\) no predictive
| Bernoulli | B(p) | 1 success, 0 failure 
| Binomial | B(n,p) | n independent trials, each with success probability p 
| Poisson | P(λ) | λ = frequency of events

#### Continuous Distributions
For infinite number of possible outcomes

| Distribution | Notation | Notes |
|--------------|----------|-------------|
|Normal|N(μ,σ²)|μ = mean, σ² = variance <br> observed in nature 
|Standard normal|N(0,1)|μ = 0, σ² = 1 <br> standardized version of normal distribution
|Student T|T(k)|k = degrees of freedom <br> for small sample size
|Chi-squared|χ²(k)|k = degrees of freedom <br> for hypothesis testing and CI
|Exponential|E(λ)|λ = frequency of events <br> e.g. views on youtube
|Logistic|L(μ,s)|μ = mean, s = scale <br> the scale parameter determines the spread of the distribution








