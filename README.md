1. What is JSX, and why is it used?
   Ans: JSX means javascript XML. it uses to same writting HTML coding syntax.It looks just like HTML, but it's actually a convenient system for writing HTML within JavaScript. It is used because it makes the code easier to read and makes building React components cleaner.

2. What is the difference between State and Props?
   Ans: (a) State is a hook that contains a component's own data, which changes over time.
   (b) Props are data sent from Parent => Child from outside, which the component can only read and cannot modify.

4. What is the useState hook, and how does it work?
   Ans: useState is a type of Hook in React that allows us to create and update state inside a component. const [Card, setCard] = useState([]); here, count is the state value, and setCount is the function to change that value.
   
6. How can you share state between components in React?
   Ans:State is usually kept in the parent component and then sent to child components via props. This is commonly known as Lifting State Up.
    
8. How is event handling done in React?
   Ans: Event handling in React is just like in HTML, but we have to use camelCase. In React, two types of event handling are used, which are
a. Click Me
b. <button onClick={()=>handleClick()}>Click Me</button>
Here, onClick is the event, and handleClick is the function that will run when clicked.
