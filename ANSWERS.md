# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**
A process is a stand-alone program that is running and has its own memory and system resources. Because processes are segregated from one another, they are more costly in terms of resource consumption but also more secure.
Within a process, a thread is a smaller unit of execution. Faster communication and more effective execution are made possible by several threads sharing the same memory area.
The primary distinction is that threads are lighter and enable quicker context change, whereas processes are heavier and need more overhead.
Because the scheduler must effectively manage several jobs, threads were employed in this project. The simulation runs more quickly and is simpler to control within a single program when threads are used.
---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**
Round-Robin scheduling assigns a fixed time quantum to every process. The process is paused and pushed to the end of the ready queue if it doesn't complete in this amount of time.
Because no process may monopolize the CPU and all processes have equal opportunities to run, this assures fairness.
Example from my output:
```
P1 completed quantum 4000ms
Remaining time: 2973ms
P1 yields CPU for context switch
```

**Explanation of example:**
This example demonstrates that process P1 did not complete within the allotted time. As a result, it was stopped and put back in the ready queue. When it has another chance, it will carry on with its execution.This conduct amply illustrates how Round-Robin scheduling preserves equity and keeps people from starving.

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**
In Java, a thread's lifecycle consists of multiple states:
1. **New**:  Although the thread has been created, it has not yet begun.
2. **Runnable**:  After invoking start(), the thread is prepared to run.
3. **Running**:The thread is using the CPU to carry out active operations.
4. **Waiting**:The use of techniques such as Thread.sleep() causes the thread to suspend its operation.
5. **Terminated**:  The thread completes its task and ends its execution.
   
As each process thread in this assignment runs, pauses during execution, and ultimately finishes, various statuses can be seen.


---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. 
2. 
3. 

**Concepts I need to study more:**
1. 
2. 
