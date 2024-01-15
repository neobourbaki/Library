# Library

> *A library of mathematical theorems and proofs, and the definitions needed to state them*


In the modern age (particularly associated, but not exclusive to the style of N. Bourbaki), 
the most essential of our mathematical knowledge is organized into two types of data structures: 
`definition`s and `theorem`s. We are adopting a rather free (informal) interpretation 
of them, subject to the following restrictions:

- Various definitions are bundled into one if they are referring to the same object
(function, number, etc.) in the same generality, scope, etc.
- Various statements, and their various proofs, are bundled into one `theorem` if
they have the same hypothesis and conclusion; it's meant to host different proofs
that employ rather different sets of `definition`s and `theorem`s.

A third type of nodes might be `example`s, but let's make use of `theorem`s as much as possible.

## Assitance by an LLM

An LLM can be a great tool to

1. take a LaTeX file of a mathematical paper or textbook, and render all the definitions
and propositions into a graph of dependencies;

1. rephrase a `definition`, `theorem` or its proofs, if any term is unfamiliar to the user,
by replacing any mention of that term by (one of) its `definition`, and turn it into a coherent
sentence or paragraph of mathematics.
