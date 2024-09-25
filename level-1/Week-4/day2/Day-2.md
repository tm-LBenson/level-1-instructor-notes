# Day 2: Deep Dive into Conditional Logic

## Overview

Today, we'll explore conditional logic in detail. We'll understand what conditionals are, how they function in programming, and see various examples that illustrate their use in decision-making processes.

## Objectives

- Understand the role of conditional statements in programming.
- Learn different types of conditional statements.
- Apply conditional logic to solve problems through hands-on exercises.

## What is Conditional Logic?

Conditional logic is used in programming to perform different actions based on different conditions. It allows programs to make decisions and react accordingly.

## Types of Conditional Statements

- **If Statements**: Perform a block of code if a specified condition is true.
- **Else Statements**: Execute a block of code if the condition in the if statement is false.
- **Else if Statements**: Specify a new condition to test, if the first condition is false.
- **Switch Statements**: Specify many alternative blocks of code to be executed.

## Detailed Explanation

### If Statement
```
IF condition THEN
    // Code to execute if the condition is true
ENDIF

```


### If-Else Statement
```
IF condition THEN
    // Code to execute if the condition is true
ELSE
    // Code to execute if the condition is false
ENDIF

```

[[Real Example If|Real Example: Droid Access Control]]

### If-Else If-Else Statement
```
IF condition1 THEN
    // Code if condition1 is true
ELSE IF condition2 THEN
    // Code if condition2 is true
ELSE
    // Code if neither condition1 nor condition2 is true
ENDIF

```
 [[Real Example Else-If|Real Example: Navigating the Starship's Control System]]
### Switch Statement
```
SWITCH expression
    CASE value1:
        // Code to execute when the expression equals value1
    CASE value2:
        // Code to execute when the expression equals value2
    DEFAULT:
        // Code to execute if no case matches
ENDSWITCH

```
[[Real Example Switch|Real Example: Responding to Different Alien Species]]
