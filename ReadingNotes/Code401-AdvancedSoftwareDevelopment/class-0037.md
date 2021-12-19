# ***React 1***


## Introducing JSX

JSX may remind you of a template language, but it comes with the full power of JavaScript.


React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.


## Rendering Elements

An element describes what you want to see on the screen

Unlike browser DOM elements, React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements.


Let’s say there is a <div> somewhere in your HTML file:
```
<div id="root"></div>
```
We call this a “root” DOM node because everything inside it will be managed by React DOM.

Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

To render a React element into a root DOM node, pass both to ReactDOM.render()


```
const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

## Components and Props
Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components. You can find a detailed component API reference here

Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.

## State and Lifecycle

In applications with many components, it’s very important to free up resources taken by the components when they are destroyed.

We want to set up a timer whenever the Clock is rendered to the DOM for the first time. This is called “mounting” in React.

We also want to clear that timer whenever the DOM produced by the Clock is removed. This is called “unmounting” in React.

We can declare special methods on the component class to run some code when a component mounts and unmounts:
```
class Clock extends React.Component {
  constructor(props) {
    super(props);
    this.state = {date: new Date()};
  }

  componentDidMount() {
  }

  componentWillUnmount() {
  }

  render() {
    return (
      <div>
        <h1>Hello, world!</h1>
        <h2>It is {this.state.date.toLocaleTimeString()}.</h2>
      </div>
    );
  }
}
```
## Handling Events
Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:
* React events are named using camelCase, rather than lowercase.
* With JSX you pass a function as the event handler, rather than a string.



# Next.js


Enter Next.js, the React Framework. Next.js provides a solution to all of react problems. But more importantly, it puts you and your team in the pit of success when building React applications.

Next.js aims to have best-in-class developer experience and many built-in features, such as:

* An intuitive page-based routing system (with support for dynamic routes)
* Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis
* Automatic code splitting for faster page loads
* Client-side routing with optimized prefetching
* Built-in CSS and Sass support, and support for any CSS-in-JS library
Development environment with Fast Refresh support
* API routes to build API endpoints with Serverless Functions
* Fully extendable


Next.js is used in tens of thousands of production-facing websites and web applications, including many of the world's largest brands.
