# February 3

## John von Neumann *First Draft of a Report on the EDVAC* (1945)

### Context
- John von Neumann
  - 20th C. Hungarian-American mathematician / polymath
  - Hungary -> Switzerland -> Germany (Hilbert) -> US (1933)
  - U.S. immigrant, worked on Manhattan Project which inspired work on automatic computers
  - Proposal for EDVAC, a successor to Presper Eckert and John Mauchly's ENIAC (ballistic calculations for military)
  - Rumored that he had a photographic memory and could recite phone numbers after seeing a phone book page
- "von Neumann" architecture
  - Same structure as Turing's universal computing machine, but seems coincidental
  - Programs stored in same memory as data
  - Called "von Neumann" architecture b/c Burks (colleague) put von Neumann's name on the proposal despite that the design was by everyone
  - Presper Eckert and John Mauchly actually created the "von Neumann" architecture, sued for IP rights
- UNIVAC (1951)
- Idea of brain as computer: analogy between vacuum tubes and neurons
- Key contributions:
  - Programs and data stored in same memory
  - Binary notation
  - Memory addresses
  - Registers
  - Floating-point representation
  - Hexadecimal
- Paper published under US Military government
- Tubes extremely finnicky but also produced tons of heat (difficult to cool!)
  - 44 * 10^{24} tubes; two tubes per bit
  - Hard to tell whether a tube was broken
  - Orders of magnitude faster than any other technology (faster than existing computers)
- Transisterized computers appeared in late 50's

### Paper

**Learnings**
- Paper is highly technical and comprehensively outlines the architecture for the EDVAC
- Anthropomorphizes computers and extensively compares electronic organs to neurons
- Discusses data representation in depth
  - Uses a sign bit to denote program vs data
- Key definitions:
  - Automatic computing system
  - Organs:
    - Central arithmetical (CA)
    - Central control (CC)
    - Memory (M)
    - Recording device (R)
    - Input (I)
    - Output (I)
  - Orders (i.e., programs)
  - Data

**Questions**
- Is this where binary came from? Which came first, binary logic or binary electronics?


## Maurice Wilkes *The Best Way to Design an Automatic Calculating Machine* (1951)

## Context
- Maurice Wilkes
  - 20th C. mathematician / researcher at Cambridge
  - Turing Award in 1967
  - Summer school @ UPenn where he learned about EDVAC
  - Started work on EDSAC (Electronic Delay Storage Automatic Calculator)
  - Created concept of microcode
- Microcode - primitive micro-instructions which in combinations form an instruction; abstraction layer; recognized as "best way" to design a computer
- Evolving convergence / overlap of human and computer functionality
- Avoid anthropomorphizing machines b/c can contribute to errors (focus on intent of instructions as opposed to bugs)

## Paper

**Learnings**
- Wilkes describes how to design the EDSAC well, including defining some of the characteristics that "well" encompasses
- Design paradigms:
  - Reliability
  - Size / cost
  - Complexity (entaglement and dependencies)
  - Repetition
- Discusses registers and single-purpose registers like %rip
- Micro-operations perform low-level micr-instructions which combine to form single instructions
  - Reprogrammable by updating the rectifier matrix
  - Some operations (written as analagous x86-64 instructions): add, sub, mul, rsh, le

**Questions**
- Why specialize certain registers and not others?
