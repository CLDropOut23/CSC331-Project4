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

<img width="959" height="490" alt="image" src="https://github.com/user-attachments/assets/1be3812b-0a3a-4b3d-99c7-a0496a8acec9" />

<img width="958" height="520" alt="image" src="https://github.com/user-attachments/assets/35b06ad9-c4f0-43c3-a5f7-1737d8bb1baf" />

<img width="959" height="515" alt="image" src="https://github.com/user-attachments/assets/8f15e296-24ec-42fc-b793-a2834c17ea25" />


<img width="959" height="521" alt="image" src="https://github.com/user-attachments/assets/94429968-5ffd-45b7-a891-ed140808fd87" />

<img width="959" height="518" alt="image" src="https://github.com/user-attachments/assets/6784d2f3-418b-4192-b7ee-ba96d37ea3b3" />


c) anylaze how cache associativity affects cache miss rate under various memory access pattern. 

Sequential Pattern: For the output of Sequential Pattern, the sequential access pattern had a miss rate of about 0.25 or 25% in direct-mapped. The block size is 16 bytes and each int/integer is 4 bytes, each block can have 4 integers. This means that each block had 1 miss and 3 accesses. The simulator made 16 misses and 48 hits out of 64 access. This shows a great spatial locality.

Stride Pattern: For the output of Stride Pattern, it had a miss rate of 1.00 or 100%. Every access had went to a different block, all of the accesses which were 16, were misses. This shows that stride patterns reduce spatial locality and increase how many cache misses there are. 

Working Set Pattern: For the output of Working Set Pattern, it had a really low miss rate of 0.0625 or 6.25%. The working set size worked perfectly with the cache, it let the data stay cached. It had 120 hits and only 8 misses. This shows that Working Set patterns have great temporal locality.

Conflict Access Pattern: 

Direct-Mapped Cache - 

2-Way Cache -

4-Way Cache- 


