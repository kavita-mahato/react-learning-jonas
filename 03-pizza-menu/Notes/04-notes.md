# Conponents as Building Blocks

### 1. Definition and Fundamental Role
* **Core Concept:** Components are the most fundamental concept in React because applications are built entirely out of them.
* **Building Blocks:** They act as the "building blocks" of any user interface (UI).
* **Rendering:** React’s primary job is to render a view for each component and combine them to create the full UI.
* **Scope:** Nothing in a React app exists outside of a component.

### 2. Component Composition
* **Triad of Characteristics:** Each component possesses three distinct properties:
    * **Data:** The information the component holds.
    * **Logic:** JavaScript logic determining behavior.
    * **Appearance:** How the component looks (UI).
* **Function:** A component describes both how it works and what it looks like.

### 3. Building Interfaces: Nesting and Composition
* **Lego Approach:** Complex UIs are built by combining multiple components together, similar to assembling Lego pieces.
* **Granularity:** Components can vary significantly in size:
    * **Large:** Entire sections like a "Video Player" or "Questions List".
    * **Small:** Tiny elements like individual "Filters".
* **Nesting:** A crucial practice is placing (nesting) components inside other components.

### 4. Reusability and Props
* **Handling Duplication:** Instead of writing code multiple times, you create a component once and reuse it as needed (e.g., reusing a "Question" component three times in a list).
* **Props:** To make reused components dynamic, "props" are used to pass different data into each instance of the component.
* **Skill Development:** Learning how to break a design down into reusable components is a critical skill in React.

### 5. The Component Tree
* **Visualization:** A component tree is a diagram that helps analyze the hierarchy and relationships between components.
* **Parent-Child Relationship:**
    * **Parent:** The container component (e.g., "Refined Questions").
    * **Child:** The nested component inside the parent (e.g., "Filters").
* **Purpose:** The tree makes it easy to understand how components relate to and nest within one another.