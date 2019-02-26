---
title: Virtual Memory 
categories: [Advanced Computer Architecture]
tags: Memory
---

---

* Essentially treating memory like a cache for dish 
  * Contents are a dynmaic subset of of prgrams address space 
    * Meaning that each program is assigned an address space and that content is capable of change
* Programs use virtual addresses (VA) 
  * 0 -> 2^N-1
* Memory uses physical addresses (PA)
  * 0 -> 2^M-1
  * 2^M is max physical memory machines support
* VA => PA at page granulairty/scale (VP => PP)
* Multiprogramming is a use of VM 
  * Each process is given 2N bytes of address space 
  * System maps VPs from different process to different PPs
    * This in turn prevents process from reading/writing each others memory
* Interprocess Communication is a use of VM in which map VPs in different processes to same PPs
* Protection is the mechanism to implement page-level protection 