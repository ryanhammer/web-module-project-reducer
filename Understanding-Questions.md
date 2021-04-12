# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The onClick handler fires, calling the dispatch method
* The dispatch method sends the addOne function to the reducer
* The addOne function returns an action type of ADD_ONE to the reducer
* The reducer runs the action associated with ADD_ONE, which takes the original state object, spreads it out, and increases state.value by 1
*  The updated state object is returned
* TotalDisplay shows the total plus 1.
