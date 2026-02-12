# Lab 2 Reflection

## Comfortability Score: 4/5
Felt comfortable with C programming and system calls. The /proc filesystem concept was interesting and made sense once I understood it's just files containing kernel data.

## Completeness Score: 4/5
All functions implemented correctly with proper error handling. I am missing some of the screenshots due to time constraints, but I successfully completed the implementation.

## A Win
Had a moment where I was debugging why my process count was wrong, then realized I forgot to check if directory entries were actually numbers using isdigit(). When I fixed the is_number() function and suddenly saw only actual PIDs listed instead of random /proc entries, it clicked how the kernel organizes process information.