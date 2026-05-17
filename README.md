# CSC331-Project4
Build a set-associative cache simulator, study the traffic trace, and analyze the relationship between the miss rates, block size, cache size and associativity.

Part 1: Simulator

For this part, we implement a set-associative cache with parameters. We just needed to complete the LRU part in the given code. 

Part 2: Memory Access Patterns

We used 4 patterns: Sequential, Stride, Conflict, Working Set Patterns, using Byte Address

Part 3: Experiment 

We used these sizes of Caches and Blocks, as well as describe the Associatives: 

Cache Size: 256 bytes

Block Size: 16 bytes

Associatives: 1,2,4 (which means directly mapped, 2 Way Associativity, 4 way associativity)

Project Outcome

a) if the program executes correctly or not

After completing the Java Code, it seems to print out perfectly. With no issues it prints out the Sets, Accesses, Hits, Misses, and Miss Rate. 


b) if yes, five screenshots showing the successful execution of your program,

c) anylaze how cache associativity affects cache miss rate under various memory access pattern. 
