# February 8

## Pre-class discussion
- Hilbert was "master of the mathematical universe" in 1900 and Turing was a nobody
- Was Hilbert / Turing speaking as creatures of their times / stations, or just doing math?
- Which of Hilbert's broad statements do you think are wrong?
- Read Cantor's Diagonal Argument before reading Turing 1936


## David Hilbert's *Mathematical Problems* (1900)

### Context
- David Hilbert
  - 19-20th C. German mathematician
  - Optimist for the solvability of all propositions
  - Proposed 23 unsolved problems, challenge of solving all basic questions known as as Hilbert's Program
- Kurt Godel
  - 20th C. German logician / mathematician
  - Incompleteness theorem proved that no system of logic can be both complete and sound
    - Showed that system like that of *Principia Mathematica* was not complete if it was sound
    - Used diagonalization argument
- 2000 Clay Mathematics Institue created Millennium Prize problems ($1M reward) as follow-on to Hilbert's list
- Problems:
  - 2 - prove soundness of recursive axioms
  - 10 - calculate integer solution to diophantine equations
- Lewis argues that Hilbert's optimism mirrors society's optimism at the start of the 19th C., and that Godel's incompleteness theorem and Turing's studies of the limits of computers mirrored the pessimism in 1930's

### Paper

**Learnings**
- Hilbert self-advocates for the importance of mathematics and the benefits of pure research in mathematics, concluding with proposing 23 questions that he argues will propel mathematics coming into the turn of the 20th C.
- Idea that proofs are for the people (should be able to explain them simply)
- Hilbert discusses tensions between basic and applied research, and argues that pursuing problems for their own sake is worthwhile
- "We hear within us the perpetual call: There is the problem. Seek its solution. You can find it by pure reason, for in mathematics there is no *ignorabimus*"

**Questions**
- What would Hilbert think of the 3-color proof? (Proof of the 3-color problem, which relied heavily on computers and was a brute force ugly proof)


## Alan Turing's *On Computable Numbers, with an Application to the Entscheidungsproblem* (1936)

### Context
- Alan Turing
  - 20th C. British mathematician and computer scientist
  - Math @ Cambridge, PhD @ Princeton (under Alonzo Church)
  - Worked on code-breaking during WWII
  - Forcibly chemically castrated (alternative was prison), died of cyanide poisoning
  - Pardoned in 2014 by Queen Elizabeth, put on 50 pound banknote
  - Big ideas:
    - Program is a finite binary string (countably many programs)
    - Real number between 0 and 1 is infinite binary string (uncountably many)
    - Thus more real numbers than programs
    - Computable number is a real number for which some program left to run forever returns all bits in order
    - Therefore most real numbers are uncomputable
    - The number whose `k`'th bit is 1 iff the `k`'th program halts is uncomputable
- von Neumann architecture redux
  - What's importance of programs as data?
    - Eckert-Mauchly (1944) easier information retrieval
    - Turing - made diagonalization possible
    - Made software possible
  - Self-reference is a very old idea
    - Epimenides - "all Cretans are liars"
    - Cantor - "I can give you a real number not in any list of real numbers"
    - Russell & Whitehead - "Oops! $S \in S$ causes problems"
    - Godel - "F is not provable"
- Entscheidungsproblem == decision problem (German)
- Terminology:
  - *m*-configuration - state of the machine
  - Configuration
  - Circular machine
  - Circle-free machine
  - Universal machine

### Paper

**Learnings**
- Turing defines Turing machines, notion of computability, and the Entscheidungsproblem (Halting Problem)
- Defines computability of a number as "its decimal can be written down by a machine"
  - This is equivalent to whether the number differs by an integer from a number computed by a circle-free machine

**Questions**
- Does Turing describe a proof by reduction?
