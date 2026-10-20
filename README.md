# AI Task Priority Scheduler

This repository contains a C++ application. The application demonstrates a **Priority Queue** implemented as a **Max-Heap**. It is designed as an **AI Task Priority Scheduler**, simulating how an Artificial Intelligence system prioritizes critical tasks (like safety protocols) over background tasks (like logging data).

The application features a fully interactive, menu-driven console interface with input validation and edge-case handling.

##  Data Structure Explanation: Priority Queue / Max-Heap

A **Priority Queue** is an abstract data type where each element has a specific priority. Elements with a higher priority are served before elements with a lower priority.
In this project, the Priority Queue is implemented using a **Max-Heap**. 

1. **The Max-Heap Rule:** It is a complete binary tree where every parent node is greater than or equal to its children. 
2.  Because of this rule, the highest priority task is always located at the root (index 0).

## Emerging Technology Connection: Artificial Intelligence

In Artificial Intelligence and autonomous systems, prioritizing tasks is critical. An AI cannot process everything similtaneously.
1. **Real-World Example:** In a self-driving car, the AI must prioritize "Brake for Pedestrian" (Priority 10) over "Update GPS Map" (Priority 2).
2. **Real-World Example:** Operating Systems use priority queues to schedule CPU time, ensuring critical system processes run before background tasks.

This project demonstrates how a Max-Heap ensures that the most important AI task is always extracted and processed first in **O(log n)** time.

### Features:
1. **Add New Task:** Input a task name and assign a priority from 1 to 10.
2. **Process Highest Priority Task:** Removes and displays the task with the highest priority.
3. **View All Pending Tasks:** Displays all tasks sorted by priority (highest to lowest).
4. **Validation:** Rejects priority inputs outside the 1-10 range.

## UML Diagram




