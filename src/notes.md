# My takeaway from this execercise.
## Component
1. Use **'Component'** to tell React what you want to see on screen.
2. When data within a 'Component' changes, React know to update and re-render it efficiently.
3. render() returns a React element.
    * React element is light-weight.
    * It is essentially a JavaScript object that you can store in a variable or pass around in your program.
4. Each React component is encapsulated and can operate independently; this allows you to build complex UIs from simple components.


## State
1. Components can remember their state.
    * to achieve this use *setState* in their constructor.
    * States are private.
2. Component constructors start with a *super(props)* call.

## React DevTools extension
1. Allows you to probe into the props and state of your React component. 
    * Inspect elements and go to the Component or Profiler tab.
z