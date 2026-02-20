# Scheduler

Built a task scheduling system in Python that organizes tasks based on duration, dependencies, and priority (fixed vs. flexible).

The algorithm uses a heap-based priority queue and dependency checks to produce a valid execution order for a full 15-hour schedule.

I also analyzed its runtime behavior and demonstrated that the implementation scales quadratically (O(N²)) due to repeated full-task scans.

Includes implementation, runtime experiments, and scaling visualizations.
