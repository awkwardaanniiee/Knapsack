# Knapsack
Given weights and values of n items, we need to put these items in a knapsack of a given capacity 
to get the maximum total value in the knapsack. <br>

In the <b>Fractional Knapsack Problem</b>, we can break items for maximizing the total value of knapsack. <br>

In the <b>0/1 Knapsack Problem</b>, we are not allowed to break items. We either take <i>all or nothing</i>. <br>

### The Program
This program will read in an input file that contains the max capacity of the knapsack, 
the number of objects, and each object's weight and profit. <br>

The user can choose to:
<li>Solve a fractional knapsack</li>
<li>Solve a 0/1 knapsack</li>
<li>Exit the program</li>


#### Sample Output
```
Which task do you want to run?
 1. Fractional Knapsack
 2. 0/1 Knapsack
 3. Exit
1

Object: 1	Weight: 13	Profit: 32
Object: 3	Weight: 29	Profit: 27
Object: 4	Weight: 23	Profit: 19
Object: 5	Weight: 43	Profit: 15
Object: 6	Weight: 10	Profit: 41
Object: 11	Weight: 21	Profit: 30
Object: 13	Weight: 28	Profit: 34
Object: 14	Weight: 26	Profit: 37
Object: 16	Weight: 44	Profit: 20
Object: 17	Weight: 36	Profit: 15
Object: 18	Weight: 23	Profit: 44
Object: 20	Weight: 38	Profit: 50
Max profit: 364

Which task do you want to run?
 1. Fractional Knapsack
 2. 0/1 Knapsack
 3. Exit
2

Object: 1	Weight: 13	Profit: 32
Object: 3	Weight: 29	Profit: 27
Object: 4	Weight: 23	Profit: 19
Object: 6	Weight: 10	Profit: 41
Object: 7	Weight: 30	Profit: 37
Object: 9	Weight: 18	Profit: 16
Object: 10	Weight: 36	Profit: 38
Object: 11	Weight: 21	Profit: 30
Object: 12	Weight: 17	Profit: 26
Object: 13	Weight: 28	Profit: 34
Object: 14	Weight: 26	Profit: 37
Object: 18	Weight: 23	Profit: 44
Object: 19	Weight: 30	Profit: 17
Object: 20	Weight: 38	Profit: 50
Max profit: 448

Which task do you want to run?
 1. Fractional Knapsack
 2. 0/1 Knapsack
 3. Exit
3

The program has ended.

```