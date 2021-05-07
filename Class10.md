# Class10

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Error Handling & Debugging: 

#### ORDER OF EXECUTION: 

To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run: 

#### EXECUTION CONTEXTS: 

The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

* EXECUTION CONTEXT: Every statement in a script lives in one of three execution contexts:
 
 1. GLOBAL CONTEXT: Code that is in the script, but not in a function. There is only one global context in any page.
 2. FUNCTION CONTEXT: Code that is being run within a function. Each function has its own function context. 
 3. EVAL CONTEXT: Text is executed like code in an internal function called eval {). 

* VARIABLE SCOPE: The first two execution contexts correspond with the notion of scope:
 1. GLOBAL SCOPE: If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.
 2. FUNCTION-LEVEL SCOPE: When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

#### EXECUTION CONTEXT & HOISTING: 

* Each time a script enters a new execution context, there are two phases of activity:

1. PREPARE: 

 * The new scope is created.
 * Variables, functions, and arguments are created.
 * The value of the this keyword is determined.

2. EXECUTE: 

 * Now it can assign values to variables.
 * Reference functions and run their code.
 * Execute statements.

#### UNDERSTANDING SCOPE: 

In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object. Functions in JavaScript are said to have lexical scope. They are linked to the object they were defined within. So, for each execution context, the scope is the current execution context's variables object, plus the variables object for each parent execution context. 

#### UNDERSTANDING ERRORS: 

If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. If you are anticipating that something in your code may cause an error, you can use a set of statements to handle the error. This is important because if the error is not handled, the script will just stop processing and the user will not know why. So exception-handling code should inform users when there is a problem.

#### HOW TO DEAL WITH ERRORS: 

Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 

1. DEBUG THE SCRIPT TO FIX ERRORS: If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 

2. HANDLE ERRORS GRACEFULLY: You can handle errors gracefully using try, catch, throw, and fina1ly statements. 

#### A DEBUGGING WORKFLOW: 

Debugging is about deduction: eliminating potential causes of an error. 

* WHERE IS THE PROBLEM?: First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important.

1. Look at the error message, it tells you:

 * The relevant script that caused the problem.
 * The line number where it became a problem for the interpreter. (As you will see, the cause of the error may be earlier in a script; but this is the point at which the script could not continue.)
 * The type of error (although the underlying cause of the error may be different).

2. Check how far the script is running. Use tools to write messages to the console to tell how far your script has executed.

3. Use breakpoints where things are going wrong. They let you pause execution and inspect the values that are stored in variables. 

* WHAT EXACTLY IS THE PROBLEM?: Once you think that you might know the rough area in which your problem is located, you can then try to find the actual line of code that is causing the error.

1. When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script.

2. Break down I break out parts of the code to test smaller pieces of the functionality.

 * Write values of variables into the console.
 * Calrfunctions from the console to check if they are returning what you would expect them to.
 * Check if objects exist and have the methods I properties that you think they do.

3. Check the number of parameters for a function, or the number of items in an array. 

#### LOGGING DATA TO THE CONSOLE: 

* This example shows several uses of the console . log () method.

1. The first line is used to indicate the script is running.

2. Next an event handler waits for the user leaving a text input, and logs the value that they entered into that form field.

 3. That the user clicked submit.

4. The value in the width input.

5. The value in the height input.

6. The value of the area variable.

* MORE CONSOLE METHODS: To differentiate between the types of messages you write to the console, you can use three different methods. They use various colors and icons to distinguish them.

1. con so 1 e. info() can be used for general information.

2. consol e.warn() can be used for warnings.

3. console .er ror() can be used to hold errors. 

* GROUPING MESSAGES: 

1. If you want to write a set of related data to the console, you can use the console. group () method to group the messages together. You can then expand and contract the results.

2. When you have finished writing out the results for the group, to indicate the end of the group the console .groupEnd () method is used. 

* WRITING TABULAR DATA: In browsers that support it, the console. table () method lets you output a table showing:

 1. objects.
 2. arrays that contain other objects or arrays. 

#### BREAKPOINTS: 

You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time. 

* STEPPING THROUGH CODE: If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur, When you have set breakpoints, you will see that the debugger lets you step through the code line by line and see the values or variables as your script progresses. 

* CONDITIONAL BREAKPOINTS: You can indicate that a breakpoint should be triggered only if a condition that you specify is met. The condition can use existing variables. 

* DEBUGGER KEYWORD: You can create a breakpoint in your code using just the debugger keyword. When the developer tools are open, this will automatically create a breakpoint. You can also place the debugger keyword within a conditional statement so that it only triggers the breakpoint if the condition is met. 

* HANDLING EXCEPTIONS: If you know your code might fail, use try, catch, and finally. Each one is given its own code block.

1. TRY: First, you specify the code that you think might throw an exception within the try block. If an exception occurs in this section of code, control is automatically passed to the corresponding catch block.

2. CATCH: If the try code block throws an exception, catch steps in with an alternative set of code. It has one parameter: the error object. Although it is optional, you are not handling the error if you do not catch an error. 

3. FINALLY: The contents of the fina11y code block will run either way - whether the try block succeeded or failed. It even runs if a return keyword is used in the try or catch block. It is sometimes used to clean up after the previous two clauses. 


















