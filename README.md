### What is react?

React is open source javascript library used to:
  - Build UI.
  - Create components.
  - Handle state and props.
  - Utilize event listeners and certain life cycle methods to update data as it changes.
  - Create its own `JSX` markup language to combine HTML with JavaScript functionality.
  
### What is JSX?

Markup language to combine HTML with JavaScript functionality that allows us to write HTML directly within JavaScript. This has several benefits. It lets you use the full programmatic power of JavaScript within HTML, and helps to keep your code readable. For the most part, JSX is similar to the HTML that you have already learned, however there are a few key differences that will be covered throughout these challenges.
JSX code must be compiled into JavaScript. The transpiler Babel is a popular tool for this process.

### What is ReactDOM
React's rendering API used ti render JSX to the HTML.
ReactDOM offers a simple method to render React elements to the DOM which looks like this:
`ReactDOM.render(componentToRender, targetNode)`, where the first argument is the React element or component that you want to render, and the second argument is the DOM node that you want to render the component to.
As you would expect, `ReactDOM.render()` must be called after the JSX element declarations, just like how you must declare variables before using them.
