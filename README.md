# react-questions

React Basics Quiz

##1. What is a component in React?

Options:
A. A function that manages the server
B. A reusable piece of the UI ✅
C. A tool for styling elements
D. A library for handling HTTP requests

Answer: B — A reusable piece of the UI

##2. JSX in React stands for:

Options:
A. JavaScript XML ✅
B. JavaScript Extension
C. JSX Syntax
D. JavaScript Expression

Answer: A — JavaScript XML

##3. What is a key rule of JSX?

Options:
A. Multiple root elements are allowed without wrapping
B. JSX does not support JavaScript expressions
C. JSX must return a single parent element ✅
D. JSX replaces JavaScript completely

Answer: C — JSX must return a single parent element

##4. How can you add dynamic content inside JSX?

Options:
A. Using square brackets []
B. Using curly braces {} ✅
C. Using parentheses ()
D. Using angle brackets <>

Answer: B — Using curly braces {}

##5. What is the default value of props if not provided?

Options:
A. undefined ✅
B. null
C. An empty string ""
D. An empty object {}

Answer: A — undefined

##6. Which of the following is the correct way to render a list of users using map() in React?

Options:
A. {users.map(user => <li>{user}</li>)}
B. {users.map((user) => {<li>{user.name}</li>})}
C. {users.forEach(user => <li>{user.name}</li>)}
D. {users.map(user => <li key={user.id}>{user.name}</li>)} ✅

Answer: D — {users.map(user => <li key={user.id}>{user.name}</li>)}

##7. Which of the following is a valid conditional rendering technique when the first condition is false?

Options:
A. Using || (OR) operator ✅
B. Using && (AND) operator
C. Using ! operator
D. Using if-else inside JSX

Answer: A — Using || (OR) operator

##8. What is the purpose of using map() when rendering lists in React?

Options:
A. To loop through elements and return them directly to the DOM
B. To filter out specific elements from an array
C. To create a new array of elements and render them in JSX ✅
D. To modify the state of the component

Answer: C — To create a new array of elements and render them in JSX

##9. What is the main advantage of component-based architecture in React?

Options:
A. It removes the need for JavaScript
B. It replaces JS frameworks
C. It allows reusable UI pieces ✅
D. It automatically creates databases

Answer: C — It allows reusable UI pieces


## 10. In React, how do you handle an event such as a button click?

**Options:**

- A: Using addEventListener directly  
- B: By assigning an event handler in JSX like `onClick={handleClick}` ✅  
- C: By writing JavaScript inside HTML tags  
- D: By calling window.onclick  

**Explanation:**  
React handles events by assigning event handlers directly in JSX, e.g., `onClick={handleClick}`.

---

## 11. What is the purpose of the `useState` hook in React?

**Options:**

- A: To handle API calls  
- B: To manage component state in functional components ✅  
- C: To render multiple components  
- D: To connect React with HTML  

**Explanation:**  
`useState` is used to manage **state** inside functional components.

---

## 12. Which statement is TRUE about `useState`?

**Options:**

- A: It returns one value: the state variable  
- B: It returns two values: the state variable and a function to update it ✅  
- C: It can only be used inside class components  
- D: It automatically updates the DOM without re-rendering  

**Explanation:**  
`useState` returns an array: `[state, setState]`. The setter function updates the state and triggers a re-render.

---

## 13. Which concept allows React components to use special features like state and lifecycle without classes?

**Options:**

- A: Middleware  
- B: Hooks ✅  
- C: Controllers  
- D: Services  

**Explanation:**  
Hooks allow functional components to use state and lifecycle features without classes.

---

## 14. Which JavaScript syntax is often used to handle asynchronous API calls in React?

**Options:**

- A: try-catch only  
- B: switch statement  
- C: async / await ✅  
- D: do-while loop  

**Explanation:**  
Async/await is commonly used to handle API calls asynchronously.

---

## 15. What will happen if you call the state setter function (e.g., `setCount`) in React?

**Options:**

- A: The state changes, and the component re-renders ✅  
- B: Only the variable updates without re-render  
- C: React crashes  
- D: Nothing happens  

**Explanation:**  
Calling the setter function updates the state and triggers a re-render.

---

## 16. What is the new `use()` hook (React 18+) primarily used for?

**Options:**

- A: To manage local state  
- B: To load and unwrap promises directly in components ✅  
- C: To style components  
- D: To replace useState  

**Explanation:**  
The `use()` hook is used to **unwrap promises** directly in components, especially for server components and Suspense.

---

## 17. In React, why should we NOT update state directly like `count++`?

**Options:**

- A: It throws an error in JavaScript  
- B: React won’t detect the change and won’t re-render ✅  
- C: It updates too quickly  
- D: It breaks JSX syntax  

**Explanation:**  
Directly mutating state does not trigger a re-render. Use the setter function instead.

---

## 18. What is the correct way to fetch data using async/await in React (without useEffect)?

**Options:**

- A: Call async function directly in the component body  
- B: Wrap async function inside an event or useEffect ✅  
- C: Assign async to useState  
- D: You cannot use async/await in React  

**Explanation:**  
Component bodies cannot be async. Async calls should be wrapped in **useEffect** or **event handlers**.

---

## 19. Which of the following best describes “Thinking in React”?

**Options:**

- A: Writing plain JavaScript inside HTML  
- B: Breaking UI into reusable components and managing state/data flow ✅  
- C: Using only hooks for state management  
- D: Writing React code exactly like jQuery  

## 20. Which hook is commonly used to load data from an API in React?
- **A. useState**  
- **B. useEffect ✅**  
- C. use()  
- D. useData  

---

## 21. What does .catch() do when used with a fetch promise?
- A. Handles successful responses  
- **B. Handles errors in the fetch request ✅**  
- C. Converts JSON to JavaScript  
- D. Executes the API call again  

---

## 22. In React, how do you display a list of countries from an array of data?
- A. Using a for loop directly inside JSX  
- **B. Using .map() to return JSX elements ✅**  
- C. Using JSON.stringify  
- D. By creating HTML with innerHTML  

---

## 23. Which prop is required when rendering a list of elements in React?
- A. id  
- **B. key ✅**  
- C. value  
- D. ref  

---

## 24. If a flag image URL is missing, how can you display alternative text in React?
- **A. Use alt attribute in <img> ✅**  
- B. Use innerText property  
- C. Use altText prop  
- D. React does not support fallback text  

---

## 25. What does "lifting up the state" mean in React?
- A. Moving state from parent to child  
- **B. Moving state from child to parent to share data ✅**  
- C. Using global variables instead of local state  
- D. Creating state outside of React  

---

## 26. Why is array comparison in React state tricky?
- A. Because React does not support arrays  
- **B. Because arrays are compared by reference, not by value ✅**  
- C. Because arrays can only store primitive values  
- D. Because arrays auto-merge when updated  

---

## 27. Which layout technique is typically used for displaying countries in 3 columns?
- A. flex-direction: row  
- **B. grid-template-columns ✅**  
- C. position: absolute  
- D. float: left  

---

## 28. Which method is used to deploy a React app to Netlify quickly?
- A. netlify publish ./src  
- **B. Drag and drop the build folder to Netlify dashboard ✅**  
- C. npm run netlify  
- D. Upload index.js file only  

---

## 29. In a 3-column layout in React using CSS Grid, which property defines the number of columns?
- A. grid-template-rows  
- **B. grid-template-columns ✅**  
- C. display: flex  
- D. justify-content  

---

30️⃣ Why do we use fragments in React?

Options:
A. It lets you group a list of children without adding extra nodes to the DOM.
B. It lets you group a list of children by adding extra nodes to the DOM.
C. It is an HTML element.
D. It is just a different name of a div

Answer: ✅ A

31️⃣ How can we toggle the boolean state in React?
const [state, setState] = useState(false)

Options:
A. setState(!state)
B. setState(state - state)
C. setState(current => !current)
D. 1 & 3 both

Answer: ✅ D

32️⃣ What is Recharts?

Options:
A. A composable charting library built on JavaScript components
B. A composable charting library built on React components
C. A composable charting library built on material UI components
D. A composable charting library built on bootstrap components

Answer: ✅ B

33️⃣ How can we set dynamic class names in React?

Options:
A. className={isRed ? "red" : "blue"}
B. className={card-container ${isRed ? "red" : "blue"}}
C. className={{red} || {blue}}
D. Both 1 and 2

Answer: ✅ D

34️⃣ Consider a non-empty array: const data = ["a", "b"] and a callback: const myCallback = item => false. What are the return values of data.filter(myCallback) and data.map(myCallback)?

Options:
A. filter returns [], map returns []
B. filter returns [], map returns [false, false]
C. filter returns [false, false], map returns []
D. filter returns ["a", "b"], map returns [false, false]

Answer: ✅ B

35️⃣ What is Tailwind CSS?

Options:
A. A JavaScript library
B. A CSS preprocessor
C. A utility-first CSS framework
D. An animation library

Answer: ✅ C

36️⃣ React-Icons supports integration with which of the following icon libraries?

Options:
A. Bootstrap Icons
B. Feather Icons
C. Ionicons
D. All of the above

Answer: ✅ D

37️⃣ What is Axios?

Options:
A. A library for making HTTP requests from the browser
B. A database management system
C. A programming language
D. A web server

Answer: ✅ A

38️⃣ Which command will you use to install Tailwind CSS in your React application?

Options:
A. npm install -D tailwindcss/vite
B. npm install @tailwindcss tailwindcss/vite
C. npm install -D vite/tailwindcss
D. npm install tailwindcss @tailwindcss/vite

Answer: ✅ D

39️⃣ What is React Awesome Component?

Options:
A. A popular React library for managing state in functional components
B. A JavaScript framework for building single-page applications
C. A collection of high-quality, reusable React components created by the community
D. A built-in feature of React for creating dynamic UIs

Answer: ✅ C

40️⃣ How do you declare a variable in JavaScript that cannot be reassigned?

A. var
B. let
C. const ✅
D. static

41️⃣ Which operator is used to check both value and type equality?

A. =
B. ==
C. === ✅
D. None of the Above

42️⃣ What is the output of console.log([1,2,3].map(x => x * 2));?

A. [1,2,3]
B. [2,4,6] ✅
C. [1,4,9]
D. Error

43️⃣ Which hook is used to add state in a functional component?

A. useState ✅
B. useEffect
C. useReducer
D. useContext

44️⃣ What is the default value of useState() if no argument is given?

A. null
B. undefined ✅
C. false
D. 0

45️⃣ What is the correct way to pass a prop named title to a component?

A. <Component title="Hello" /> ✅
B. <Component props="Hello" />
C. <Component>title="Hello"</Component>
D. <Component>Hello</Component>

46️⃣ In React, what does JSX stand for?

A. JavaScript XML ✅
B. JSON XML
C. Java Syntax Extension
D. JavaScript Extended

47️⃣ What happens if you call setState in React with the same value as the current state?

A. Component re-renders
B. Component does not re-render ✅
C. React throws an error
D. State becomes undefined

48️⃣ What is the default behavior of React forms?

A. Forms automatically handle state
B. Forms auto-submit on enter
C. Forms store values in Redux
D. Forms use uncontrolled inputs by default ✅

49️⃣ In React, keys help to:

A. Identify unique elements in a list ✅
B. Improve CSS performance
C. Authenticate API requests
D. Style components


Here are all the questions, options, and correct answers compiled clearly 👇

---

### 50. What is the main advantage of using Context API to manage state?

A. It reduces code complexity by avoiding the need for props drilling
B. It improves performance by optimizing component rendering
C. It provides built-in form validation
D. It automatically handles asynchronous data fetching

✅ **Answer: A**

---

### 51. What is Prop Drilling in React?

A. It is a technique for passing data from a parent component to a deeply nested child component
B. It is a way to handle forms in React
C. It is a method for styling components using props
D. It is a process for managing state using the useContext hook

✅ **Answer: A**

---

### 52. In a controlled component, which React hook is commonly used to track input value?

A. useRef
B. useContext
C. useState
D. useEffect

✅ **Answer: C**

---

### 53. What is the purpose of using the useRef hook in React?

A. To access the DOM elements directly within functional components
B. To manage controlled components
C. To create uncontrolled components
D. To handle form submissions

✅ **Answer: A**

---

### 54. What is a controlled component in React?

A. A component controlled by CSS
B. A component where form data is handled by React state
C. A component that uses only HTML forms
D. A component that cannot change its value

✅ **Answer: B**

---

### 55. What event is commonly used to handle form submissions in React?

A. onClick
B. onSubmit
C. onChange
D. onBlur

✅ **Answer: B**

---

### 56. How do you use a custom hook in a functional component?

A. By passing it as a prop to the component
B. By importing it and calling it directly within the component
C. By wrapping the component with a higher-order component provided by the hook
D. By defining it within the component using the useCustomHook syntax

✅ **Answer: B**

---

### 57. How do you prevent a page reload when submitting a form in React?

A. Set reload attribute to false
B. Use a try-catch block
C. Call event.preventDefault() in the onSubmit handler
D. Use the onChange handler instead

✅ **Answer: C**

---

### 58. How do you pass children components to a parent component in React?

A. By using props to pass the children components to the parent component
B. By importing the children components directly within the parent component's JSX
C. By wrapping the children components with opening and closing tags inside the parent component's JSX
D. By defining the children components as local variables within the parent component's render method

✅ **Answer: C**

---


