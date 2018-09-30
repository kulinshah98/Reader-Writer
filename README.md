# Reader Writer

## Project Description

This is modified version of famous consumer-producer problem with N readers and 1 writer threads with a fix sized buffer.

## Compile and Run

- Compile using gcc command and then run the executable
- Input:- N . Here N = Number of posts as well as number of posts.

## Implementation
- First, I will create N threads for readers and 1 thread for writer therefore I will create total N+1 threads.
- Reader ( Consumer ) thread will call consumer function and Writer ( Producer ) thread will call Producer function. For each thread I have a mutex therefore whenever someone access block ( post ) then no one can access it.After writer can access block writer will write a post and reader can read it.

