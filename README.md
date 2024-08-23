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