---
layout: post
---

how do we manage all this free space?
there is a free list that holds all the free blocks in memory. this is usally a linked list.
a block of memory should also have a header that contains metadata about the block, such as its size, the blocks prev and next to it, etc.

internal vs external fragmentation
internal frag is when a block has unused wasted space inside of it.
external frag is when the memory region has segments of allocated blocks, and the free list that remains becomes unconfortable to allocate. 
for example, if you wanted a block of size 10, but the free list only contains 2 blocks of size 5 spread out. there is space to allocate, but they are fragmented. 


what are the different memory allocation strategies?
fcfs, best fit, buddy

[table w pros and cons, internal vs external frag, etc]

buddy allocators  

