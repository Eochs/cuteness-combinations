# cuteness-combinations

When we are considering whether to have more children, we have to take into account the combinatorial explosion of cuteness.

To illustrate, observe different sized families, represented by "Parent 1", "Parent 2", and Children represented as nodes:
![alt text](https://github.com/Eochs/cuteness-combinations/blob/main/combinatorics-drawing.png?raw=true)

Starting at the left we have no children. 
1. Then we move to 1 child, where Parent 1 can have a direct, cute interaction with the child, or observe a cute interaction between the child and Parent 2. 
2. Next we have 2 children. In this case we start to see combinatorics at work, and while Parent 1 can interact with each individually, they can also observe pairwise interactions between the two children, and also Parent 2. Finally a cute interaction is observed by Parent 1 when all 3 interact together.
3. Even more combinations emerge, and we get choose 3 combinations, as well as all 4 interacting. 

From this we get "The law of compounding cuteness": $ C_i = i + \\sum_{k=2}^{i+1} {i+1\\choose k} $

Plotting this we see that there is a combinatorially increasing amount of cute interaction possibilities for each additional child:
![alt text](https://github.com/Eochs/cuteness-combinations/blob/main/cuteness-graph.png?raw=true)
