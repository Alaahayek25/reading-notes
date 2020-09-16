# Error Handling debugging

JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully. 

## EXECUTION CONTEXTS

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 
Every statement in a script lives in one of three
execution contexts: 
- GLOBAL CONTEXT

Code that is in the script, but not in a function.
There is only one global context in any page

-  EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eva l {).

- GLOBAL SCOPE

If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope. 

### HOW TO DEAL WITH ERRORS 
there are two things you can do with the errors. 
1. DEBUG THE SCRIPT TO FIX ERRORS

If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.
You will find that the developer tools available in
every major modern browser will help you with
this task. In this chapter, you will learn about the
developer tools in Chrome and Firefox

2. HANDLE ERRORS GRACEFULLY

You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements.
Sometimes, an error may occur in the script for a
reason beyond your control. For example, you might
request data from a third party, and their server
may not respond. In such cases, it is particularly
important to write error-handling code. 

# Sammary 
- If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
- Debugging is the process of finding errors. It involves a
process of deduction.
- The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
- If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback. 