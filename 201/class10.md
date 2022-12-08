# Class 10 Notes

1 - Syntax errors are things like not wrapping a condition in parentheses or throwing in an extra curly brace. These aren't too bad because the console or your linter will tell you what you've done wrong. Logic erros though are when your program runs, but it just sucks. For example, maybe you finally got your table to load, but it only populates with NaN. That's because you did a bad job, and need to git gud. Obviously this can take more time to solve than a syntax error. 

2 - An error I make all the time is updating a variable before ever declaring. Most of the time I do this in for of loops because I forget to add the let in `for (let thing of thingsContainer)`.

3 - Honestly I have just resigned myself to making a massive number of errors and being better at troubleshooting. Maybe even learning how to use the debugger. 

1 - The debugger is like Slow-Motion Instant Replay. Just like we can see whether or not Julio Jones got the ball in the endzone we can see the exact operation that is creating my NaN problem. We can go 'frame-by-frame' to see what JS is doing.

2 - Sticking with my forced sports analogy, a breakpoint is like the point of a play we want to view in Slow-Motion. Our code will run at normal speed until it arrives at our breakpoint, where it will stop and wait for us to prod it along step-by-step.

3 - The call stack is where JS functions wait while one of their callback functions executes. A function with a callback cannot run until it's callback has executed and returned a value. This can get kind of messy with many nested functions.

## Things I want to know more about

Should I be using the debugger more and console logs less?

If I plan on using the debugger extensively are there any code changes that make that more productive/feasible?