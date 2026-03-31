# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

Entry 1 - [March 24, 2026, 2:30 PM]
What I did: Explored the project and ran the program
Details:
I opened the project, read the instructions, and ran the code for the first time to see how the simulation works.
Challenges:
The code structure was a bit confusing at the beginning, especially the threading part.
Solution:
I focused on reading the comments and tried to follow the execution step by step.
Time spent: 50 minutes

Entry 2 - [March 25, 2026, 5:00 PM]
What I did: Studied the Process class
Details:
I focused on understanding how each process works and how the run() method executes.
Challenges:
It was not clear how the remaining time updates after each execution.
Solution:
I traced the values manually and followed the logic carefully.
Time spent: 1 hour

Entry 3 - [March 26, 2026, 6:30 PM]
What I did: Analyzed the scheduler behavior
Details:
I studied how the ready queue works and how processes are re-added after each quantum.
Challenges:
Understanding why processes go back to the queue was confusing at first.
Solution:
I reviewed the Round-Robin concept from lecture notes and connected it with the code.
Time spent: 2 hour

Entry 4 - [March 28, 2026, 4:00 PM]
What I did: Tested and observed program output
Details:
I ran the program multiple times and focused on how processes execute and switch.
Challenges:
The output was long and hard to follow at first.
Solution:
I focused only on important lines like execution, remaining time, and queue updates.
Time spent: 55 minutes

Entry 5 - [March 31, 2026, 2:00 PM]
What I did: Implemented all required features
Details:
I added priority to processes, implemented context switch counting, and added waiting time calculation. Then I tested everything.
Challenges:
Calculating waiting time correctly was a bit tricky.
Solution:
I used System.currentTimeMillis() and adjusted the logic until the results made sense.
Time spent: 3 hours
---

## Summary

**Total time spent on assignment**: [X hours]

**Most challenging part**: following process execution throughout the queue and comprehending how the scheduler loop operates.

**Most interesting learning**: Seeing how programs share CPU time and how Round-Robin scheduling operates in real-world scenarios.

**What I would do differently next time**: 
