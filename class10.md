*JavaScript book*
*Ch. 10, “Error Handling & Debugging”*

## ORDER OF EXECUTION 
### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run
## EXECUT.ION CONTEXTS
### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 

### ERROR OBJECTS CONTI NUED :
* Syntax Error:SYNTAX IS NOT CORRECT (This is caused by incorrect use of the rules of the language. It is often the result of a simple typo. )
* Refrane Error :VARIABLE DOES NOT EXIST (This is caused by a variable that is not declared or is out of scope. )
### JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 
### If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 