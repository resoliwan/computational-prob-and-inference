<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-MML-AM_CHTML'></script>
# Introduction
Probabilites appears in eveny day life and feed into how we make decision. For example

### Definition
* If in a massive number of repeats of the experiment, the event happens roughly a fraction q of the time; more repeats of the experiment make it so that the fraction gets closer to q.
* Our only hope is to somehow model or simulate tomorrow's weather given measurements up to present time.

If it claims that there's a 30 % chane of weatcher, we could interpret this as saying that using their way of simulating tomorrow's weather, in roughly 30 % of simulated results for tomorrow's weatch, there is rain

# Two Ingredients to Modeing Uncertainty.
We model the uncertainty, We will assume that there is an underlying experments of interest.
0. Sample space Ω = Set of all possible outcomes.
>Collectively exhasutive
> > * Every possible outcome is in omega.
> > * Mutually exclusive == After experment *exactly* only one outcome in omega happens.
> > * Probabilty can be thouth of as fraction of times outcomes occur; thus, probability are nonnegative and at least 0 and at most 1.
> > * Probabilty of all outcome need to sume to 1.
> 
> ex) coin filp: Ω = {heads, tails}

0. Probability of each possible outcome.
> 
>ex) coin flip: 
> * P(heads): 1/2
> * P(tails): 1/2
> * In genral: P(S) prob of S happening

### In python 
```
model = {'heads': 1/2, 'tails': 1/2}
sample_space = Set(model.keys())
model['heads']
model['tails']
```

# Probability space / Prob model
Can be represent by Samplespace and Probabiltiy table = \\( (\Omega, P)\\)
* For each \\( \omega \in \Omega\\)
* \\( 0 \leq P(\omega) \leq 1 \\)
* \\( \sum_{\omega \in \Omega}P(\omega)=1 \\)




