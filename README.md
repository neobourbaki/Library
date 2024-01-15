# Library
A library of mathematical theorems and proofs

In homage to N. Bourbaki, the entire body of mathematical knowledge is organized into two types of 
data structures: `definition`s and `theorem`s. We are adopting a rather free (informal) interpretation of them, 
subject to the following restrictions:

- Various definitions are bundled into one if they are referring to the same object (function, number, etc.) in the
same generality, scope, etc.
- Various statements are bundled into one theorem if they have the same hypothesis and conclusion. It's meant to illustrate
group different proofs that employ different sets of `definition`s and `theorem`s.

A third type of nodes might be `example`s, but let's see if we could make use of `theorem`s.

## Assitance by an LLM

An LLM can be a great tool to

1. take a LaTeX file of a mathematical paper or textbook, and render all the definitions
and propositions into a graph of dependencies;

1. rephrase a `definition` or `theorem` if any term is unfamiliar to the user, by replacing
any mention of that term by (one of) its `definition`, as a coherent sentence.
