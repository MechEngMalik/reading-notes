# Error Handling & Debugging

 Errors, bugs, and therefore debugging are a part of life for a programmer. Error handling is a combination of coding and methodology that allows your program to anticipate user and other errors.It allows you to create a robust program
 JavaScript is often described as a synchronous, single-threaded language. Essentially meaning that it can only perform one function at a time and if a function takes some time to finish, such as an HTTP request, it would literally block the user from interacting with the webpage. Click events would be delayed until the blocking function finally finishes, for example. Of course, this would be a bad user experience. So how exactly does JavaScript work around this? How is it able to perform asynchronous tasks? “Callback functions!” “Promises!” “Async!” Yup, you got it. I guess there is nothing else to say… All kidding aside, JavaScript, again, is a synchronous language. To understand how it can perform asynchronous tasks, we will have to take a peak at what is going on ‘under the hood’ of the browser .
The JavaScript engine has two main components — the heap which is used for memory allocation and the call stack which is our ‘single thread’. We will focus on the call stack and how it interacts with the other pieces of the execution order which include the web APIs, the task queue, and the event loop.
**ORDER OF EXECUTION**

![pic](https://miro.medium.com/max/3630/1*ddKOVPd0nh4-3l9QisgJnQ.png)

## Execution contex

Execution context (EC) is defined as the environment in which the JavaScript code is executed.By environment, I mean the value of this , variables, objects, and functions JavaScript code has access to at a particular time.

### What is a stack JavaScript?

Stacks are data structures that follow the Last-In-First-Out (LIFO) principle, meaning the last item inserted into a stack is the first one to be deleted. In other words, a stack is a list of elements that are accessible only from one end of the list, which is called the Top of Stack (ToS).
The regular Array structure in Javascript is a Stack (first in, last out) and can also be used as a Queue (first in, first out) depending on the calls you make.

- push() method:
The push() method allows you to add one or more elements to the end of the array. The push() method returns the value of the length property that specifies the number of elements in the array.
If you consider an array as a stack, the push() method adds one or more element at the top of the stack. The following example creates an empty array named stack and adds five numbers, one by one, at the end of the stack array. It is like to push each number into the top of the stack.
- pop() method :
- The pop() method removes the element at the end of the array and returns the element to the caller. If the array is empty, the pop() method returns undefined.

### JavaScript has 7 different types of errors

1. RangeError:A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String.
2. ReferenceError: This error is thrown when a reference made to a variable/item is broken. That is the variable/item doesn’t exist.
3. SyntaxError : This is the most common error we encounter. This error occurs when we type code that the JS engine can understand.
This error is caught by the JS engine during parsing. There are different stages in the JS engine our code is put through before we see those results on the terminal.
4. TypeError :The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type. A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function.
5. URIError : The decodeURIComponent() function decodes a Uniform Resource Identifier (URI) component previously created by encodeURIComponent or by a similar routine.
6. EvalError : The EvalError object indicates an error regarding the global eval() function. This exception is not thrown by JavaScript anymore, however the EvalError object remains for compatibility.
7. InternalError : his error occurs internally in the JS engine, especially when it has too much data to handle and the stack grows way over its critical limit.
This occurs when the JS engine is overwhelmed by too many recursions, too many switch cases, etc.

### try, catch, finally statements

The try statement allows you to define a block of code to be tested for errors while it is being executed. The catch statement allows you to define a block of code to be executed, if an error occurs in the try block. The finally statement lets you execute code, after try and catch, regardless of the result.
![pic2](https://cdn.javascripttutorial.net/wp-content/uploads/2019/12/javascript-try-catch-1-1.png).
