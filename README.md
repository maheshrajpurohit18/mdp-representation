# MDP REPRESENTATION

## AIM:
The aim of this experiment is to create a Markov Decision Process (MDP) representation and implement it in Python to model the decision-making process in optimize the movement of a warehouse robot .
## PROBLEM STATEMENT:

### Problem Description
Write your answer here

### State Space
Write your answer here

### Sample State
Write your answer here

### Action Space
Write your answer here

### Sample Action
Write your answer here

### Reward Function
Write your answer here

### Graphical Representation
Write your answer here

## PYTHON REPRESENTATION:
```
mdp={
    
    1:
     {
    0:[(1,0,0,False)],
    1:[(1,0,0,False)],
    2:[(0.7,3,-5,False),(0.3,2,1,True)],
    3:[(0.3,2,1,True),(0.7,3,-5,False)],
    4:[(1,0,0,False)]},

    2:
     {
       0:[(1,2,0,True)],
       1:[(1,2,0,True)],
       2:[(1,2,0,True)],
       3:[(1,2,0,True)],
       4:[(1,2,0,True)]}, 
    
    3:
     {
       0:[(1,3,0,False)],
       1:[(1,3,0,False)],
       2:[(1,3,0,False)],
       3:[(0.95,4,10,True),(0.05,1,0,False)],
       4:[(0.05,1,0,False),(0.95,4,10,True)]}, 
    
    4:
     {
       0:[(1,4,0,True)],
       1:[(1,4,0,True)],
       2:[(1,4,0,True)],
       3:[(1,4,0,True)],
       4:[(1,4,0,True)]} 
    
     
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6c69f20f-dad1-40d8-9ac7-9407cb3dd325)


## RESULT:
Write your output here

