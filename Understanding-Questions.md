# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- calls our event handler function
- event handler dispatches the addOne action
  *addOne action returns the case type ADD_ONE
  *reducer case type ADD_ONE returns the current state plus 1
  ...

- TotalDisplay shows the total plus 1.
