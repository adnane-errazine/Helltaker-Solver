# Helltaker-Solver #
 Helltaker-Solver solves Helltaker game levels (1 to 9) by generating an optimal sequence of moves to pass the level.
 
# Usage example : #
 
``` python3 Helltaker_State_Space_Search.py levels/level2.txt ```
# Description #
 In order to create a new map :
 Inside a .txt file 
   -first line : Title / Description
   -second line : maximum cost to pass the level
   -the rest : we used this vocabulary to implement the map
H: hero
D: demoness
#: wall
  : empty
B: block
K: key
L: lock
M: mob (skeleton)
S: spikes
T: trap (safe)
U: trap (unsafe)
O: block on spike
P: block on trap (safe)
Q: block on trap (unsafe)

Example : 
```
Level 2
24
 ####   
#    ## 
#M#SS  #
 S##OOB#
  ## S #
H ## M #
####D M#
########
```
# Performance per Algorithm #
![image](https://user-images.githubusercontent.com/71216079/189544758-5f2282ee-2864-4ac4-ae24-47c8b3f4e936.png)

# Credits #
this project was
supervised by Pr. Sylvain Lagrue
