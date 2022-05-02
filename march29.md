# March 29

## "Redicubility among combinatorial problems" (1972)

### Context
- Richard Karp
  - 20-21st C. mathematician and computer scientist
  - Grew up on Boston, son of a schoolteacher
  - PhD at Harvard in digital computing
  - Went to IBM
  - Professor at Berkeley
- Introduces P, NP, polynomial-time reducibility, and NP-completeness
- Lists 21 problems that reduce to boolean satisfiability
- Caused P = NP to be an incredibly important problem

### Paper
- AHHHHHH this is so cool: I remember banging my head against the wall trying to understand reductions in CS121 not having taken a formal math course, and it is so fascinating to see their origin here
- Definition of P and P = NP problem involves heavy notation, seems very technical to explain when it really is not
- Some of the problems:
  - MST
  - Shortest path
  - Mincut
  - Satisfiability
  - 0-1 integer programming
  - Clique
  - Set packing
  - Node cover
  - Set covering
  - Feedback node set
  - ... so many more!
- Relies on Cook's theorem

### Questions:
- What was the reaction like among your peers?


## "Big omicron and big omega and big theta" (1976)
- Discusses how there was not a standardized notation, and that Knuth couldn't even find an explanation for $\Sigma(f(n))$.
- Describes formal definitions for big-O, big-sigma, little-sigma, and theta.
- Crazy to see that these definitions haven't really changed in almost 40 years!
- A lot of the paper is rationale and explanation, it is an argument
- The need for a universally established and accepted notation


## "The complexity of theorem-proving procedures" (1971)

### Context
- Jack Edmonds paper: discussed that the difference between algebraic and exponential order is often more crucial than the difference b/w finite and non-finite
- Cook defines $L_{*}$ in the paper, which means the same thing as $P$ today.
- Stephen Cook
  - Canadian-American computer scientist
  - Undergradute at UofT
  - PhD in math @ Harvard
- Paper set off the search for P = NP
- Cook-Levin Theorem: Levin had identified the same class of problems independently, an instance of simultaneous discovery

### Paper
- Discusses reductions
- Like the Karp paper, discusses languages as subsets of the set of all finite length binary strings
- Highly technical paper that formally proves several results
