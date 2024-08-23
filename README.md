# webbrowser-local


How Js keeps track of what to run when?
Call Stack
When you call a function in JavaScript all the instructions within that function get loaded into a
Stack.
Javascript then executes the instructions in each function by popping them from the stack.
Callback queue
It’s a one more data structure that Js to add next code to execute.
Such code are called tasks, since they need more time to execute.
Tasks are added to the queue whenever Js finds a function which will take some time to execute
like setTimeout


You're explaining the basics of JavaScript asynchronous programming and data types. Here's a summary:

Asynchronous Programming:

- JavaScript is synchronous by nature, executing one line of code at a time.
- To avoid blocking code execution, we use Web Browser APIs to convert synchronous code to asynchronous code.
- Web Browser APIs provide methods like:
    1. setTimeout
    2. setInterval
    3. Local Storage
    4. fetch
- The event loop stack works as follows:
    1. Stack (synchronous code execution)
    2. Web API (browser)
    3. Queue (asynchronous code execution)
    4. Stack (synchronous code execution)

Data Types:

- Primitive Data Types (Pass by Value):
    - Store exact values (immutable)
    - Cannot change internal elements
    - Examples:
        1. Number
        2. Boolean
        3. String
        4. Null
        5. Undefined
- Non-Primitive Data Types (Pass by Reference):
    - Store addresses (mutable)
    - Can change internal elements
    - Examples:
        1. Array
        2. Function
        3. Object
