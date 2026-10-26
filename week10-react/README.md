# Week 10: Meet React — Component-Based Web Development

## Project Overview

**Role:** Junior Front-End Developer  
**Project:** Community Connect React Service Directory

Briefly describe what you refactored and added.

I created a function that assisgned a state to the service cards that allowed them to be filtered. I also completed a component that let the service cards with the same format to be created from an array.

---

# React Decisions

Document approximately three meaningful React decisions.

## Decision 1

**React Concept:**  
[Component, props, list rendering, state, or event] Props: categoryLabel, title, description, detail

**Used For:**  
[What did you implement?] I used these props to tell the ServiceCard component how to format the information inside each array item into a new Service Card.

**Why It Helps:**  
[How does this improve the code or interface?] This improves the code by reducing repetitive code.

## Decision 2

**React Concept:**  List rendering: services

**Used For:**  I used list rendering to generate service cards automatically.

**Why It Helps:**  This improves the code by making it easier to edit the list of items, like when the filter was applied, without the list needing to be fully typed out.

## Decision 3

**React Concept:**  State: useState("all")

**Used For:**  I used this state to display all the service cards by default before a filter is selected.

**Why It Helps:**  This improves the interface by displaying information and prompting users to engage with the filters.

---

# React Reflection

Write approximately **75–100 words** responding to:

> How is working with React components different from manipulating the DOM directly as you did in Week 8? What seems easier, and what seems more complex?

While I initially struggled to understand React, when compared to the Javascript used in Week 8 the code that made the component reactive was simpler. The function makes it easy to follow what the output should be. The props reduced the amount of variables that needed an independent variable. It was easier to track my progress and troubleshoot errors since the function did all the work once I got the props and variables set up correctly.

---

# Testing Notes

- [x] `npm install` completed successfully
- [x] `npm run dev` runs the project
- [x] ServiceCard is reusable
- [x] Services render from the supplied array
- [x] Every rendered service uses a stable key
- [x] All filter works
- [x] Health filter works
- [x] Housing filter works
- [x] Community filter works
- [x] Active filter is visually clear
- [x] Active filter uses an accessible programmatic state
- [x] Keyboard interaction works
- [x] Browser console has no unresolved warnings/errors
- [x] `npm run build` completes successfully

---

# Final Handoff Check

- [x] My project folder is named `week10-react`
- [x] I used the supplied React/Vite project
- [x] `ServiceCard.jsx` exists
- [x] I used props
- [x] I used `map()`
- [x] I used stable keys
- [x] I used `useState()`
- [x] I used React event handling
- [x] I used native buttons for filters
- [x] `node_modules` is not committed
- [x] My README is complete
- [x] I committed and pushed the completed project
