# Delegates and Lambdas (in progress!)

Intermediate level task for practicing `Func`, `Predicate` and `Comparision` delegates and lambdas. 

Estimated time to complete the task - 3h.  

The task requires .NET 6 SDK installed.   

## Task Description

The task has 7 sub-tasks. Each sub-task is a small coding exercise.

<details>
<summary>

**Sub-task #1**

</summary>
      
- Open the [FunctionExtensions.cs]() file.

- Implement a [GenerateProgression]() method that generates a sequence of the elements of type T by the following recurrent formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The number of requested elements is defined by the given number.
  
- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #2**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement a [GenerateProgression]() method which generates a sequence of the elements of type T by the following recurrent formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The number of requested elements is defined by the condition.

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #3**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement a [GetElement]() method which generates a `n`s element of the sequence of the elements of type T according to the following recurrent formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #4**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement a [Calculation]() method which calculates a value as a composition of sequentially executed binary operation $`operation(x, y)`$ on the elements of the sequence by the rule:

   $`r = operation(x_1, x_2)`$, $`r = operation(r, x_3)`$,  ... , $`r = operation(r, x_n)`$

- The elements of the sequence are generated by recurrent formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The number of requested elements for the calculation is defined by the given number.

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

- Multiplication and addition operations are used as test operations.

</details>

<details>
<summary>

**Sub-task #5**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement a [GenerateSequence]() method which generates a sequence of the elements of type T by the following recurrent formula: 

   $`x_1 = a, x_2 = b, x_{n+1}=f(x_n, x_{n - 1}), n = 2, 3, ...`$

   The count of requested elements is defined by the given number.
     
- The following sequences are used as test sequences.

   $`x_1 = 1, x_2 = 1, x_{n + 1} = x_n +  x_{n - 1}, n = 2, 3, ...`$, where T - integer type;     
   $`x_1 = 1, x_2 = 2, x_{n + 1} = 6 x_n - 8 x_{n - 1}, n = 2, 3, ...`$, where T - integer type;    
   $`x_1 = 1, x_2 = 2, x_{n + 1} = x_n +  x_{n - 1} / x_{n}, n = 2, 3, ...`$, where T - real type.

</details>

<details>
<summary>

**Sub-task #6**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement the generic `FindMax` method which finds maximum from two elements of the type `T` according to comparer logic.

</details>

<details>
<summary>

**Sub-task #7**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement the generic `CombinePredicates` method which allows you to combine several predicate conditions using the logical AND operation (&&).

</details>
