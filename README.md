# Super4PCS
---
## Intro
Basicly it's the amazing algorithm by Nicolas Mellado, Dror Aiger, which solves pointsets registration in linear time.  
See more here: https://github.com/nmellado/Super4PCS
## Some modifications
1. A time display fuction is added, which shows which part of the alogrithm takes the most time.
2. The original algorithm is aimed at Point cloud reconstruction, so its input pointsets are generally on the same scale. 
I want to use it to match a part with a pile of parts, so I make it accept different number of sampling for 2 input pointsets. 
