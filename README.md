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
