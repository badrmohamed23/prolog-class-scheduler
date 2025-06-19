Prolog Class Scheduling System
This project implements an intelligent class scheduling system using Prolog, designed for students at the German University in Cairo (GUC) as part of the Concepts of Programming Languages course (Spring 2025).

The system generates valid weekly schedules for students based on predefined constraints such as:

No course clashes for individual students

At least 2 days off per student

Automatic detection of common assembly hours where all students are free

Supports querying individual or university-wide schedules

The core functionality is achieved through a set of custom Prolog predicates operating on a provided knowledge base (studentKB.pl), using logic-based reasoning to satisfy the scheduling constraints
