# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- The onclick handler is invoked.
- The dispatch function is invoked.
- The addOne function is invoked.
- The reducer function is invoked.
- The reducer function receives the action from the addOne function and state from App.js
- The reducer function returns a new state which updates the state in App.js.
- TotalDisplay shows the total plus 1.
