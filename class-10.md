# Error Handling & Debugging

- **Error objects** can help you find where your mistakes are and browsers have tools to help you read them.

### ERROR OBJECTS CONTINUED
  - Syntax Error
    - SYNTAX IS NOT CORRECT : This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.
  - ReferenceError
    - VARIABLE DOES NOT EXIST : This is caused by a variable that is not declared or is out of scope.

### Debugging:
  -  is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.

- The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.

- The JavaScript console is just one of severa l developer tools that are found in all modern browsers.
    - The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
- Debugging is the process of finding errors. It involves a process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.