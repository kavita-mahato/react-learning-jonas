# Separation of Concerns

### 1. The Traditional Approach
* **Old Standard:** Before modern frameworks, web development relied on a strict separation of technologies .
* **One File Per Tech:** We maintained separate files for HTML (structure), CSS (style), and JavaScript (logic) .
* **Definition:** This method of organizing code by technology type was traditionally known as "Separation of Concerns" .

### 2. The Shift to Interactive Apps
* **Rise of SPAs:** As Single Page Applications (SPAs) became popular, the role of JavaScript expanded significantly .
* **Logic Drives UI:** JavaScript began to completely determine the content and presentation of the HTML .
* **Tight Coupling:** The logic (JS) and the User Interface (HTML) became tightly coupled, meaning the HTML often makes no sense without the corresponding JavaScript .

### 3. React's Philosophy: Co-location
* **The Question:** If logic and UI are inextricably linked, why keep them in separate files? .
* **Component Design:** This realization led to React components, where data, logic, and appearance are all contained within a single block of code .
* **Co-location Principle:** React follows the principle of "co-location," which states that things that change together should be located as close as possible to each other .
* **New Organization:** Instead of one technology per file, React uses one *component* per file .

### 4. Redefining Separation of Concerns
* **Common Misconception:** Many early critics believed React abandoned separation of concerns by mixing JSX and JS .
* **The Reality:** React *does* implement separation of concerns, but the paradigm has shifted .
* **New Paradigm:**
    * **Old:** One concern per file (Tech-based separation) .
    * **New:** One concern per component (Functionality-based separation) .
* **Outcome:** Each component is solely concerned with a specific piece of the UI, managing its own HTML, CSS, and JS internally .