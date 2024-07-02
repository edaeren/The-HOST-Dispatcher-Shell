This project is focused on a multi-programming system with a four-level priority process dispatcher operating under limited available resources. It involves designing, implementing, and discussing a dispatcher system in the context of an operating systems course.
Features
Four-Level Priority Dispatcher: Includes real-time processes with the highest priority, and three levels of user processes managed by a feedback scheduler.
First-Come-First-Serve (FCFS): Immediate execution for real-time processes (priority 0) until completion without interruption.
Feedback Scheduler: For normal user processes with a base time quantum of 1 second, involving three priority levels.
Round Robin: Utilized when all processes are at the lowest priority level.

Process Simulation
Process Life Cycle: Processes are simulated by the dispatcher, displaying messages upon start, during execution, suspension, resumption, or termination.
Random Color Scheme: Each unique process is identified by a randomly generated color scheme for easy distinction.

Input
Process List: Specified in a text file (giriş.txt) with comma-separated values indicating arrival time, priority, and process time.
