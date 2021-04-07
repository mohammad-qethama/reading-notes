# Call Stack

* Call stack is a mechanism that keeps track of functions execution when function provoked in other function

* Function added to call stack when called/provoked ,once its done and the execution continuos to the line after its provoking line but before that the function will be removed from the call stack.

* we start with an empty Call Stack. Whenever we invoke a function, it is automatically added to the Call Stack. Once the function has executed all of its code, it is automatically removed from the Call Stack. Ultimately, the Stack is empty again.

* Call Stack uses LIFO(Last In First Out) to temporarily store and manage function invocation .

* Temporarily store: When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame.

* A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

* Types of error:
  1. Reference errors (something not declared / not declared probably )
  2. Syntax errors (parsing somthing wrong / error in `(),{},[]` most of the times)
  3. Range errors (try to manipulates out of range elements)
  4. Type errors (accessing data type while they are incompatible )

* chrome devloper tools can be used to set breaking points thus debugging error

* by using `try catch` you can see better errors massage a fallback to a default state of our application in case of an error rather than stopping the execution vaguely.

* Tools to avoid runtime errors
   1. quokka
   2. eslint
   3. TypeScript

* call stack in error massages is the path that your program has taken to reach the point were you set a breaking point or were you have an error.
