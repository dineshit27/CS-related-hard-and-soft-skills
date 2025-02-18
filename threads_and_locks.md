# Threads and Locks

## Lock

While a resource is holding a `lock` all other resources that want to acquire the `lock` must wait.

## Deadlock

Reasons for a deadlock:

1. Mutual Exclusion
   - Limited access or limited quantity of a resource
2. Hold and Wait
   - A process holding a resources acquires other resources without releasing previous resources
3. No Preemption
   - One process cannot forcibly remove another process' resource
4. Circular Wait
   - Two or more processes wait for another resource in the chain

## Thread vs. Process

| Thread                        | Process                                                                                  |
| ----------------------------- | ---------------------------------------------------------------------------------------- |
| exists within a process       | instance of a program                                                                    |
| shares process' resources     | separate address space                                                                   |
| threads share same heap space | inter-process communication to access variables of other process (pipes, files, sockets) |

## Context switch
 - Time spent to switch between processes
 - Scheduling is part of the operating system