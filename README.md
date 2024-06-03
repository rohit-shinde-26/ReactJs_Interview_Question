# ReactJs_Interview_Question
## 1. What are Higher-Order Components (HOCs)? How are they used in React?
#### A higher-order component is a function that takes a component and returns a new component with enhanced functionality. They allow you to reuse component logic across multiple components.

## 2. What is JSX in React?
#### JSX stands for javascript XML which allows to write HTML in javascript

## 3. What is real DOM
#### It is a tree representation of HTML elements <br/> It is maintained by the browser after parsing HTML elements <br/> After manipulation, it re-render the entire DOM <br/> Updates are heavyweight </br> Updates are heavyweight

## 4. What is Virtual DOM
#### It is lightweight copy of original DOM <br/> It is maintained bt javascript libraries <br/> After manipulation it only re-render changed elements <br/> Performance is faster

## 5. What are React Hooks?
#### Hooks are functions that allow you touse state and other react features in functional components, hooks are introduced in React v16.8
### List of hooks :
#### useState <br/> useEffect <br/> useContext <br/> useCallback <br/> useRef <br/> useMemo <br/> useReducer

## 6. What is React Router
#### React Router is React library that enables dynamic navigation without refreshing the entire web pages <br/> It creates fast and interactive Single page application <br/> Developers can build user friendly web apps by rendering specific components when user click on links

## 7. What is fragments in React
#### Fragment in React is used to combine the child nodes and render without creating an extra parent Node

## 8. What is controlled and uncontrolled components in react
#### In a controlled component react, state handles all the form data, whereas, in an uncontrolled component, the HTML form element data is managed by only the DOM

## 9. Features of react
#### JSX <br/> Virtual DOM <br/> Performance <br/> Conditional Statement <br/> Component Based <br/> Simplicity

## 10. What is props
#### Props is a special keyword in React that stands for properties and is used for passing data from one component to another.

## 11. What is state
#### The state is a built-in React object that is used to contain data or information about the component. A component's state can change over time; whenever it changes, the component re-renders.

## 12. How to avoid re-rendering in react
#### 1. Replacing useState() with useRef() hook. <br/> 2. Using Reselect library to create Memoized selectors <br/> 3. Using SWR a React Hooks library for data fetching <br/> 4. Memoization using useMemo() and useCallback()Hooks

## 13. What is package.json 
#### It is metadata file in nodeJs project that describe the project dependencies , scripts,configuration and other details.

## 14. How to pass props parent component to child component in React
#### Embedded child component in parent component and gives value as an argument and access in child component
