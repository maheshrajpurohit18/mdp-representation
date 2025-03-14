# MDP REPRESENTATION

## AIM:
The aim of this experiment is to create a Markov Decision Process (MDP) representation and implement it in Python to model the decision-making process in optimize the movement of a warehouse robot .
## PROBLEM STATEMENT:

### Problem Description
Design an RL agent to optimize the movement of a warehouse robot to efficiently pick up and deliver items while avoiding obstacles, minimizing time, and conserving energy.

### State Space
![image](https://github.com/user-attachments/assets/5fb06340-6525-459d-99e4-2c5bfcc45332)


### Sample State
![image](https://github.com/user-attachments/assets/dd71157f-1c8f-41e7-a6d4-1cca7eaa01e8)


### Action Space
![image](https://github.com/user-attachments/assets/a0ce5275-4149-4f30-b80f-0a4fe752bb29)


### Sample Action
![image](https://github.com/user-attachments/assets/ef1e1395-da82-4c43-9ad5-764e460e3f57)


### Reward Function
![image](https://github.com/user-attachments/assets/1910d7ea-3695-4a62-a4be-9a27737b4cf9)


### Graphical Representation
![image](https://github.com/user-attachments/assets/3e671914-4b2d-4607-8e28-cf0ed3b41204)


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
Thus, The MDP Represntation of reaching a college from home without any traffic is successfully executed.

