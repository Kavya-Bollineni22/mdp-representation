# MDP REPRESENTATION

## AIM:
To create an environment to check whether the child plays or stay at home according to the weather conditions.

## PROBLEM STATEMENT:

### Problem Description
Children looking for playing outdoor games. Action is based on the weather conditions, if it is a sunny day there is a high chance of playing or if it is a cloudy day, they simply stay at home.

### State Space
{C,W,S} -> {0,1,2}
where,

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
P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}
```

## OUTPUT:
![image](https://github.com/Kavya-Bollineni22/mdp-representation/assets/75235813/44902110-586a-4c12-b000-49951a4a5bf9)


## RESULT:
Thus, an environment to check whether the child plays or stay at home is created according to the weather conditions.


