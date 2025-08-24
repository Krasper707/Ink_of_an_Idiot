## Markov Chains

- Recently came across the term Markov Chains in my self studies pursuit.
- Assumptions that markov chains take: Future state Depends only on current state not the state before the current state. i.e. $$P(X_n | X_1,X_2,..,X_{n-1}) = P(X_n|X_{n-1})$$

- And a beautiful aspect that I just realised is the following:
  - This transition between states can be shown using a transition matrix; Say P. where each row gives the probabilities of moving from one state to another.
  - The long-term behavior (steady state distribution) of the Markov chain comes from solving: $$\pi P = \pi$$ where $$\pi$$ is the stationary distribution. ($$\lambda =1$$) ; $$\pi$$ is left eigenvector of P with eigenvalues equal to 1!
  - Fascinating!
 

 A state in which we start from, but the probability of coming back to it is less than 1 is called transient state ; since we transition from one to another using it.

 Recurrent state:
 - A state in which the probability of coming back to it is 1 is called a recurrent state


A markov chain in which we can go from any state to any other state is called  a irreducible chain.


[Another rabbit hole](https://en.wikipedia.org/wiki/Gambler%27s_ruin)


 Will have a deep dive soon into this.
