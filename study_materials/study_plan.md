## Level 1 Study Plan: Functions (Think Python 2e)

This plan covers the fundamentals of functions based on the provided text from *Think Python 2e*.

**Total estimated study time:** 4-6 hours

**I. Function Definition and Structure (1-2 hours)**

* **Subtopics:**
    * Defining a function using `def` (syntax, indentation).
    * Function name and parameters.
    * Function body (statements within the function).
    * Returning from a function (implicitly or using `return`).
* **Resources:** *Think Python 2e*, pages 42-43.
* **Exercises:**
    * Create a function that takes two numbers as input and returns their sum.
    * Create a function that prints a personalized greeting message based on a name input.
    * Move the function call in the example program (p. 43) to different locations and observe the results.  Analyze the error messages.
* **Important Notes:**  Pay close attention to the indentation; it's crucial in Python for defining the function's scope.  Understand how to call (execute) a function.


**II. Fruitful vs. Void Functions (1 hour)**

* **Subtopics:**
    * Fruitful functions: Functions that return a value. Examples: `math.sqrt`, `math.cos`.
    * Void functions: Functions that perform an action but do not return a value. Example: `print_twice`.
    * The `None` value and its type (`NoneType`).
* **Resources:** *Think Python 2e*, pages 46-47.
* **Exercises:**
    * Identify whether the functions you created in the previous section are fruitful or void.
    * Modify a void function to make it fruitful (if possible).
    * Write a small program that calls a fruitful function and stores its result in a variable. Print the variable's value.
* **Important Notes:**  Understand the difference between a function's *side effects* (actions like printing) and its *return value*.  A fruitful function *must* have a `return` statement to return a value.


**III. Function Calls and Flow of Execution (1-2 hours)**

* **Subtopics:**
    * Order of execution: Statements are executed sequentially, top to bottom.
    * Function calls as detours in execution flow.
    * Function definitions create function objects; the code inside isn't executed until the function is called.
    * Nested function calls: One function calling another.
    * Tracebacks: Understanding error messages and the order of function calls during errors.
* **Resources:** *Think Python 2e*, pages 43, 46.
* **Exercises:**
    * Write a program with multiple functions that call each other.  Trace the execution flow.
    * Intentionally introduce an error (e.g., calling a function before it's defined) and analyze the traceback.
* **Important Notes:**  Visualizing the flow of execution is crucial for understanding program behavior.  Practice tracing code execution by hand.


**IV. Parameters and Arguments (1 hour)**

* **Subtopics:**
    * Parameters: Variables defined in the function definition.
    * Arguments: Values passed to the function when it's called.
    * How arguments are assigned to parameters.
* **Resources:** *Think Python 2e*, page 47.
* **Exercises:**
    * Modify your earlier functions to accept parameters.
    * Experiment with passing different types of arguments to your functions.
* **Important Notes:** Understand the difference between parameters and arguments.  A function can have multiple parameters.

This plan provides a structured approach to learning the fundamental concepts of functions in Python. Remember to actively engage with the exercises to solidify your understanding.  After completing this Level 1 plan, you should be ready to move on to more advanced topics involving functions, such as using return values effectively, and handling different types of parameters.