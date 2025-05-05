# University-Course-Timetabling-Optimization-using-Google-OR-Tools
This project models and solves a University Course Timetabling Problem (UCTP) using Google OR-Tools (CP-SAT &amp; SCIP solvers) in Python. The goal is to generate feasible and optimized course schedules that meet institutional and faculty requirements.

Key features:

Developed a constraint programming model incorporating real-world scheduling constraints (faculty workload, multi-section courses, room accessibility, time preferences).

Integrated hard and soft constraints such as one-class-per-time-slot-per-room, professor availability, and student enrollment capacities.

Optimized solver performance, reducing runtime from 23 minutes to 2 minutes through constraint reformulation and solver tuning.

Validated schedule outputs to meet institutional policies while maximizing preferences.

Contributed to UI design research for potential web-based timetable visualization.
