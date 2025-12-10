# What is JSX ?

### 1. Definition and Purpose
* **Core Definition:** JSX is a declarative syntax used to describe what components look like and how they work based on their data and logic .
* **Extension of JavaScript:** While it resembles HTML, JSX is actually an extension of JavaScript that allows developers to combine HTML, CSS, and JavaScript into a single block of code .
* **The Component Rule:** Each component must return one block of JSX, which React uses to render the UI .
* **Capability:** It enables embedding JavaScript variables and referencing other React components to nest and reuse them .

### 2. How JSX Works Under the Hood
* **Browser Limitation:** Browsers cannot understand JSX directly; they only understand standard HTML and JavaScript .
* **The Role of Babel:** A tool called Babel (included by Create-React-App) automatically converts JSX into standard JavaScript .
    * **Conversion Process:** Babel translates every JSX element into a `React.createElement` function call .
    * **Manual Alternative:** It is possible to write React without JSX by manually writing `createElement` functions, but this is difficult to read and rarely done .

### 3. Declarative vs. Imperative Approaches
* **Imperative Approach (Vanilla JS):**
    * **"How" to do it:** You give the browser step-by-step instructions on how to update the UI .
    * **Manual Steps:** Involves manually selecting elements, traversing the DOM, and attaching event listeners .
    * **Mutation:** You explicitly command the browser to mutate DOM elements to reach the desired state .
* **Declarative Approach (React):**
    * **"What" to do:** You simply describe *what* the UI should look like based on the current data (props and state) .
    * **Abstraction:** React abstracts away the DOM, meaning developers rarely touch it directly (no `querySelector` or `classList` manipulations) .
    * **Synchronization:** The UI is treated as a reflection of the current data, and React automatically keeps the UI in sync with that data .