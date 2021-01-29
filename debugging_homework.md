# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?

A breakpoint purpose is to pause at a line of the application code on which we want a debugger to kick in.


2. Does the line of code on a breakpoint run when you start debugging?

Yes, "when we debug the application, it will run as normal until it hits the breakpoint, when it reaches that line it will pause the application and launch a debugger console."


3. How do we debug the next line of code?

We debug the next line of code with the step over option.  This will run line of code, jump to next line, pause and wait before it runs that.

4. What does the step into command do?

The step into command will switch to said method and pause at the top of that method.

5. What is the difference between evaluate expression and evaluate code fragment?

Evaluate expression allows you to evaluate and run a line of code.  Calls methods on the instances of objects.

Evaluate code fragment allows you to run multiple methods on multiple lines of code and create temporary variables to stores things to test against.