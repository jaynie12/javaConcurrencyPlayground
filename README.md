# javaConcurrencyPlayground
TLDR: Demonstrate core concepts in concurrent and parallel programming using modern Java.

Provide clear, isolated demonstrations of threads, synchronization, thread pools, and parallel algorithms through small runnable modules. 

Users can select different “concurrency demos” through a simple menu and observe how Java schedules and coordinates concurrent tasks.

LOCKED DOWN SCOPE - NO scope creep allowed!!



**Basic Thread Demo:** Shows thread creation, naming, sleeping, and joining.

**Race Condition Demo:**  A shared counter modified by multiple threads.

**Users see incorrect results when unsynchronised vs synchronised:**  Producer–Consumer Demo (BlockingQueue)

**Classic example showing safe thread communication:**  Producers generate tasks, consumers process them.

**Thread Pool Demo (Executors + Futures):**  Demonstrates submitting multiple tasks to a fixed thread pool.

**Shows how results are collected with Future or Callable:** Parallel Computation Demo (Parallel Array Sum)

**Splits a large array into chunks and uses multiple threads to compute sum: ** Compares performance vs single-threaded.
