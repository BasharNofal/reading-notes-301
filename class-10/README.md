## THE CALL STACK

**Call Stack** means how interpreter manages function invocation. In JavaScript:

* When function is invoked the interpreter puts it at the top of a list (call stack).
* Executes the code inside of it.
* If there was another function inside the first one it puts it on top of the call stack above the first function.
* Executes the code inside the second function.
* When it's done it removes the second function from the call stack.
* returns to the line where the second function was invoked and continues executing the lines inside the first function until it's done and removes the first function from the call stack.

Sometimes an **stack overflow** error occurs when there is function is being invoked inside of itself, which basically causing an infinite loop.

![call stack](https://i.ytimg.com/vi/2ZH_1d8TYVg/maxresdefault.jpg)