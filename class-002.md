## React lifecycle

**render() method**
- render() is the most used method for any React powered component which returns a JSX with backend data. It is seen as a normal function but render() function has to return something whether it is null. When the component file is called it calls the render() method by default because that component needs to display the HTML markup or we can say JSX syntax.
- Remember, you can not define setState() inside render() function. Why??? Because setState() function changes the state of the application and causing a change in the state called the render() function again. So if you write something like this then calling the function stack will go for infinity and application gets the crash.

- You can define some variables, perform some operation inside render() function, but never use the setState function. In general cases, We are logging out some variable’s output in the render() method. It is the function that calls in mounting lifecycle methods.

**componentDidMount() method**
- after all the elements of the page is rendered correctly, this method is called. After the markup is set on the page, this technique called by React itself to either fetch the data from An External API or perform some unique operations which need the JSX elements.

- componentDidMount() method is the perfect place, where we can call the setState() method to change the state of our application and render() the updated data loaded JSX. For example, we are going to fetch any data from an API then API call should be placed in this lifecycle method, and then we get the response, we can call the setState() method and render the element with updated data.

**componentWillMount() method**
- is the least used lifecycle method and called before any HTML element is rendered. If you want to see then check out the example mentioned above, we just need to add one more method.

**constructor**
- The constructor() method is called before anything else, when the component is initiated, and it is the natural place to set up the initial state and other initial values.

- The constructor() method is called with the props, as arguments, and you should always start by calling the super(props) before anything else, this will initiate the parent's constructor method and allows the component to inherit methods from its parent (React.Component).

**getDerivedStateFromProps** 

- The getDerivedStateFromProps() method is called right before rendering the element(s) in the DOM.

- This is the natural place to set the state object based on the initial props.

- It takes state as an argument, and returns an object with changes to the state.

**render**
- The render() method is required, and is the method that actually outputs the HTML to the DOM.

**Updating**
- The next phase in the lifecycle is when a component is updated.

- A component is updated whenever there is a change in the component's state or props.

- React has five built-in methods that gets called, in this order, when a component is updated:

  - getDerivedStateFromProps()
  - shouldComponentUpdate()
  - render()
  - getSnapshotBeforeUpdate()
  - componentDidUpdate()
- he render() method is required and will always be called, the others are optional and will be called if you define them.

**getDerivedStateFromProps**
- Also at updates the getDerivedStateFromProps method is called. This is the first method that is called when a component gets updated.

- This is still the natural place to set the state object based on the initial props.
