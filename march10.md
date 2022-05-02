# March 10

## Gordon Moore "Cramming More Components onto Integrated Circuits" (1965)
- I still remember in CS124 when we had to run Prim's algorithm on a massive graph overnight on our computers, and then Prof. Mitzenmacher told us that due to Moore's law he'd been doubling the size of the graph every few years to test the law... all to say, it's cool to read this paper!

### Context
- Gordon Moore
  - 20-21st C. American engineer, businessman
  - Founded Intel
  - Predicted that the number of components on a chip would double yearly, and so speed would double yearly
  - The above was coined "Moore's Law," which is now generalized to general computing speeds
- Real revolution was miniaturization and invention of the transistor + photolithography
- Prescient about predictions of the invention of home computers

### Paper
- Moore discusses factors affecting computing speeds and integrated circuits as well as their potential use cases, benefits, and limitations
- Key points:
  - Home computers will be actualized (e.g., the wristwatch)
  - Reliability will allow construction of larger processing units
  - Semiconductor integrated circuits will dominate
  - Cost per component is inversely proportional to the number of components (impact of cost on computer systems)
  - Heat problem (not necessarily true)

## Corbato, Daggett, and Daley "An Experimental Time-Sharing System" (1962)

### Context
- Hopper and Backus debated about using multiple computers in parallel to accomplish multiple tasks
- Fernando Corboto
  - 20-21st C. academic / computer scientist
  - PhD in physics @ MIT, faculty, then went to IBM
  - Created the first time-sharing machine @ MIT
- Goal was to disprove skepticisms that time-sharing was possible via a MVP (yay for agile methodology!)
- Compatible Time-Sharing System (CTSS) - first time-sharing system, supplanted by MULTICS, then Unix

### Paper
- The paper discusses a summary of the problem at hand (i.e., the motivation for time-sharing), implementation problems, an explanation of a simple time-sharing system, and a scheduling algorithm
- Multi-programming vs. time-sharing: multi-programming is in regard to hardware efficiency, whereas time-sharing is the human efficiency of multiple people using a computer at the same time
- Motivation for time-sharing: e.g., debugging is a nightmare and wastes a ton of computer resources when only one person can use a computer at the same time!
- Interesting impact of time-sharing: instead of specifying decision trees in advance in a program, we can create them dynamically (compilation vs JIT languages?)
- Implementation problems:
  - Hardware: memory protection, dynamic realocation, I/O for multiple users, redundancy / back-ups, timer interrupts, memory size
  - Programming problems: how to charge users ($$$), supervisor program, system programs, language choices
  - Usage problems: terminations, debugging mechanisms / logging
- Foreground and background processes, improvements to system memory include IPC
- Scheduling algorithm is somewhat complex, I thought the graph of number of active users and service with a "saturation point" helpful
- Fascinating system design paper, which having taken CS61 feels familiar but also very unfamiliar!
