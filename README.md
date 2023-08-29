# MDP REPRESENTATION

## AIM:

To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:

### Problem Description

To maintain the traffic signal controls .The role of the agent is to access to change the signals colour with representative of traffics.

![tl](https://github.com/priya672003/mdp-representation/assets/81132849/dec69e63-116e-4183-ba09-5a1c6b8a8fe0)


### State Space

{ Red , Green , Yellow }  = { 0 , 1 , 2 }

### Sample State

Red 

### Action Space

{ Stop the vehicle on red signal hits , ready to go } -> { 0 , 1 }

### Sample Action

Stop the vehicle on red signal hits 

### Reward Function

R={ +1 ,ready to go gignal returns green
     0 , otherwise
  }

### Graphical Representation

![image](https://github.com/priya672003/mdp-representation/assets/81132849/4c0a837d-fcfd-44f2-9139-9d2cb0fad9c9)


## PYTHON REPRESENTATION:
```python3
P={0: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 0, 0.0, True)]},
   1: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 2, 1.0, True)]},
   2: {0: [(1.0, 2, 0.0, True)],
       1: [(1.0, 2, 0.0, True)]}
  }
```
## OUTPUT:

![image](https://github.com/priya672003/mdp-representation/assets/81132849/d8664372-74cd-4bbb-8c16-d7522cced14e)


## RESULT:

Thus, a real-world problem is represented in MDP form.

