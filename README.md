# Helltaker-Solver #
 Helltaker-Solver solves Helltaker game levels (1 to 9) by generating an optimal sequence of moves to pass the level.
 
# Usage example : #
 
``` python3 Helltaker_State_Space_Search.py levels/level2.txt ```

 In order to create a new map :
 Inside a .txt file 
   -first line :
   -second line :
   -the rest is for using this 
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
 
# Credits #
this project 
supervised by Pr. Sylvain Lagrue
