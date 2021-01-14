# MuZero
My research into MuZero and AlphaGo

Original paper 
# https://arxiv.org/pdf/1911.08265.pdf

^ Trying to make sense of this by coding



# RL algorithms:
Reinforement learning algorithms,
Machine learning method, agent recieves a delayed reward in the next step to evaluate its 
previous action,
    mostly used in games (Atari), and can perform as well or better than humans

 Markov Decision Processes:
 MDPs are meant to be a straightforward framing of the problem of learning from 
 interaction to achieve a goal.

 The Markov Property states that,
 "The future is independent of the past given the present"

 Once the current state in known the history of the information encountered so far
 may be thrown away, and that state is a sufficient statistic that gives us the same 
 characterization of the future as if we have alll the history

 in mathematical terms:
 P[St+1 | St] = P[St+1 | S1, ….. , St],


A Markov Process is a memory less random process, i.e a sequence of random states S1, S2...
with the Markov property. A Markov process or Markov chain is a tuple (S, P) on state space
S, and transitiion function P. The dynamics of the system can be defined by S and P. 
When we sample from an MDP, it's basically a sequence of states or as we call it an
episode.


# The MuZero Algoritm

