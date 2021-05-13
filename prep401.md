# Get Ready for 401

## How to Solve Programming Problems

one must resist the urge of start coding when solving a problem as its a common mistake.

Steps for solving problem:

1. Read the problem completely twice.
2. Solve the problem manually with 3 sets of sample data.
3. Optimize the manual steps.
4. Write the manual steps as comments or pseudo-code.
5. Replace the comments or pseudo-code with real code.
6. Optimize the real code.

* 70% of the solving problem time must be spent on the steps 1 to 3 .
* thats might be hard to do because of the lack of trust in the proceeder , practicing it will give it this confidence.

**Extra Tip**: when tackling complicated problem , divide it and  repeat the steps above for each part.

## Pretend Your Time is Worth $1,000/Hour and You’ll Become 100x More Productive

1. Most people value their time at far, far less than it’s worth.
2. be focused not busy.
3. seize your stress.
4. do the above as mush as humanly possible.
5. If you don’t treat yourself and your time with respect, you will become unhappy, resentful, and tired.

## lessons in problem solving

1. Understand:

   >If you can’t explain something in simple terms, you don’t understand it. — Richard Feynman
2. Plan
3. Divide
4. Stuck?
   * The difference is the best programmers/problem-solvers are more curious about bugs/errors than irritated.
   * Debug
   * Reassess
   * Research
5. Practice

## 5 Whys

Sakichi Toyoda, the Japanese industrialist, inventor, and founder of Toyota Industries, developed the 5 Whys technique in the 1930s.

You can use 5 Whys for troubleshooting, quality improvement, and problem solving, but it is most effective when used to resolve **simple or moderately difficult problems.**

How to use it :

1. Assemble a Team.
2. Define the Problem
3. Ask the First "Why?"
4. Ask "Why?" Four More Times
   * Try to move quickly from one question to the next, so that you have the full picture before you jump to any conclusions.
5. Know When to Stop
   * if you're not sure that you've uncovered the real root cause, consider using a more in-depth problem-solving technique like Cause and Effect Analysis, Root Cause Analysis, or FMEA

6. Address the Root Cause.

7. Monitor Your Measures.

## The Super Mario Effect

1. focus on success not the failures and their consequences
2. approach problem solving like the way you play games don't mind the failure and how you look to other.
3. one success more if her try more.
4. reframe the learning process focus on the final cool things that can be done with that knowledge.

## Event Loop

1. js uses a call stack to execute functions.
2. async functions that takes time are handled be WebApi's of the browser.
3. when done processing/waiting for execution the api send callback function to be queued up in the callback queue.
4. event loop while sense the call Stack and push the first queued call back into it to execute it
5. render queue is time-interval based  (60 ms) queue that check if it can render things to the user periodically.
6. render queue is blocked by the call stack and have a higher priority than the  callback queue

7. be using callbacks long time process will not block the browser and make it look stuck for the user and we can reduce the callstack overflow using it.

8. node.js uses the same concept with the difference of using C++ (the glorious C++) APIs instead of web APIs
