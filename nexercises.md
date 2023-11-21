---
title: Exercises
layout: template
filename: nexercises
--- 


## Exercise 1

1. Write code to calculate the sum of the first 100 integers.
2. Which of the following will always return the numeric value stored in x? You can try out examples and use the help system in the R console.
   1. `log(10^x)`
   2. `log10(x^10)`
   3. `log(exp(x))`
   4. `exp(log(x, base=2))`

3. Use the accessor to extract all columns of the **murders** dataset and assign them to a variable name and after that determine their class.
4. Write a nested function that outputs the number of regions included in the region variable.
5. Load **movielens** dataset from *dslabs* package into R and answer the following questions based on this dataset:
   1. How many rows are in the dataset?
   2. How many different variables are in the dataset?
   3. What is the variable type of title?
   4. What is the variable type of genres?
   5. How many levels are in the factor genres?
  
6. Create a vector x of integers that starts at 12 and ends at 73. Determine the length of object x.
7. Create a vector containing all the positive odd numbers smaller than 100. The numbers should be in descending order.
8. Using `seq` function create a vector that contains 15 numbers with equal distance in-between 1 and 1000.
9. In **murders** dataset, access population values from the dataset and store it in a variable named **pop**. Sort the object and save it in the same object. Report the smallest population size.
10. Define the variable **i** to be the index of the smallest state. Define variable **states** to hold the states. Use the index you just defined to find the state with the smallest population.
11. Store the per 100,000 murder rate for each state in **murder_rate**. Using this variable, calculate the average murder rate in the US.
12. If the vector **x** is defined as follows: `x <- c(2, 43, 27, 96, 18)`, match the following outputs to the function that produces that output. Options include sort(x), order(x), and none of these:
      1. `1, 2, 3, 4, 5`
      2. `1, 5, 3, 2, 4`
      3. `18, 27, 43, 96`

13. Akbar, Sarah, Ali, and Nastaran all ran different distances in different time intervals. Their distances (in km) and times (in minutes) are as follows:
```
name <- c("Akbar", "Sarah", "Ali", "Nastaran")
distance <- c(0.8, 3.1, 2.8, 4.0)
time <- c(10, 30, 40, 50)
```
Write a line of code to convert time to hours. Then write a line of code to calculate the speed of each runner in km per hour. Speed is distance divided by time. Who was the fastest runner?

