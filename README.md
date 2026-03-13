# react-questions

React Basics Quiz
1️⃣ What is a component in React?

Options:
A. A function that manages the server
B. A reusable piece of the UI ✅
C. A tool for styling elements
D. A library for handling HTTP requests

Answer: B — A reusable piece of the UI

2️⃣ JSX in React stands for:

Options:
A. JavaScript XML ✅
B. JavaScript Extension
C. JSX Syntax
D. JavaScript Expression

Answer: A — JavaScript XML

3️⃣ What is a key rule of JSX?

Options:
A. Multiple root elements are allowed without wrapping
B. JSX does not support JavaScript expressions
C. JSX must return a single parent element ✅
D. JSX replaces JavaScript completely

Answer: C — JSX must return a single parent element

4️⃣ How can you add dynamic content inside JSX?

Options:
A. Using square brackets []
B. Using curly braces {} ✅
C. Using parentheses ()
D. Using angle brackets <>

Answer: B — Using curly braces {}

5️⃣ What is the default value of props if not provided?

Options:
A. undefined ✅
B. null
C. An empty string ""
D. An empty object {}

Answer: A — undefined

6️⃣ Which of the following is the correct way to render a list of users using map() in React?

Options:
A. {users.map(user => <li>{user}</li>)}
B. {users.map((user) => {<li>{user.name}</li>})}
C. {users.forEach(user => <li>{user.name}</li>)}
D. {users.map(user => <li key={user.id}>{user.name}</li>)} ✅

Answer: D — {users.map(user => <li key={user.id}>{user.name}</li>)}

7️⃣ Which of the following is a valid conditional rendering technique when the first condition is false?

Options:
A. Using || (OR) operator ✅
B. Using && (AND) operator
C. Using ! operator
D. Using if-else inside JSX

Answer: A — Using || (OR) operator

8️⃣ What is the purpose of using map() when rendering lists in React?

Options:
A. To loop through elements and return them directly to the DOM
B. To filter out specific elements from an array
C. To create a new array of elements and render them in JSX ✅
D. To modify the state of the component

Answer: C — To create a new array of elements and render them in JSX

9️⃣ What is the main advantage of component-based architecture in React?

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

**Explanation:**  
“Thinking in React” means designing UI by **breaking it into reusable components** and managing **state and props** correctly.

---
