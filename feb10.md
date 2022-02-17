# February 10

## Pre-class discussion
- Shannon's paper was complete upon publish
- What does Information Theory try to explain?
  - Informal: use a lot of words to say little
  - Formal: cheapness of sending S&P 500 every 0.001s
  - Speculative: data compression invention, let you on ground floor
- Binary codes
  - Codes for representing numbers
    - One form of data representation, there are others
    - Idea that number representation is distinct from the number is big
  - Codes for compressing data
    - E.g., morese / teletype
  - Codes for detecting / correcting errors in data
  - Codes for encrypting data


## Claude Shannon, *A Mathematical Theory of Communication* (1948)

### Context
- Claude Shannon
  - 20th C. American mathematician
  - "Father of information theory"
  - UMich undergrad, PhD @ MIT
  - Unicycled and juggled
- Created the term "bit" (accredits to Tukey)

### Paper

**Learnings**
- Logarithmic measure is convenient:
  - More useful since metrics vary linearly with the log of the number of possibilities
  - Feels more intuitive
  - Mathematically easier
- Five parts of a communication system:
  - Information source
  - Transmitter
  - Channel
  - Receiver
  - Destination
- Necessity for both discrete and continuous communication systems
- Used stochastic processes to model communication processes
- Entropy is a measure of the quantity of information
  - $H = -K \sum_{i=1}^n p_i log p_i$
  - High entropy means lots of information, less compressible
  - Low entropy means less information, highly compressible

**Questions**
- What was the next step after these discoveries? Who carried it along?


## Richard Hamming *Error detecting and correcting codes* (1950)

### Context
- Currently take it for granted that transmitted bits are always correct
- Old solutions:
  - Parity codes (similar to a checksum)
- Richard Hamming
  - 20th C. American mathematician
  - Manhattan Project, Bell Labs
  - Story:
    - Invented information theory when working in Bell Labs -- set a mainframe computer to run over the weekend, but a parity check failed early-on and so everything stopped
  - Hamming distance - measure of how far two codes are from one another
  - Joined academia and dedicated to education

### Paper
- Hamming describes the problem of creating a communication system and error correcting codes, and then how to solve it optimally; notes that often these problems are difficult do "do things right" at a large scale
- Key terms:
  - Systematic codes
  - Redundancy ($R = n / m$)
  - Single error detecting code
  - Double error detecting code
