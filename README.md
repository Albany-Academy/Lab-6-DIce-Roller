# Lab-6-Dice-Roller

## Objective
Practice writing and using a **static method** to generate random numbers and simulate rolling dice with any number of sides.
Note:  Rolling a die should result in values from 1 to n, where n is the number of sides.
---

## Instructions

1.  - Write a **static method** called `rollDie` that:
    - Takes an integer parameter `sides` (the number of sides on the die).
    - Generates a random number between 1 and `sides` (inclusive).
    - Returns the result as an `int`.
    - You must use the Math.random() method as learned in class.
    - The method should **return** the result of the dice roll, not print it.

  Method header:
   ```java
   public static int rollDie(int sides) {
       // your code here
   }
```
2.  - In the `main` method, obtain the **number of sides** for the dice.
    -  Call the `rollDie` method **twice** to simulate rolling two dice.
    - Compute the sum of the two dice and output the results.
    - Print the results in this format:


            You rolled a pair of 8-sided dice:
            Die 1: 4
            Die 2: 6
            Sum: 10

     - Don't forget to close out your scanner!

3.  Be sure to test your program several times with different dice sizes (like 6-sided, 10 sided, or 20 sided dice).

4.  Be sure to include header documentation, method documentation (Description, Preconditions, Postconditions, Parameters and return values) and any in-line documentation to describe your code.

Sample Output:
           
            
            Enter the number of sides for your dice: 6
            You rolled a pair of 6-sided dice:
            Die 1: 2
            Die 2: 5
            Sum: 7
            
            Enter the number of sides for your dice: 12
            You rolled a pair of 12-sided dice:
            Die 1: 7
            Die 2: 10
            Sum: 17
