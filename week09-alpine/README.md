# WebWorks Studio — Module 9 Student Starter
## Mission City Makers Market

You are the **Junior Front-End Developer** assigned to improve a fictional client page using two different professional tools:

1. **Alpine.js** — create one lightweight custom interaction.
2. **Preline UI** — choose and adapt one reusable component.

The goal is not to add as many effects as possible. The goal is to choose the right tool for the right job.

## Start Here

Open this entire folder in Visual Studio Code.

In the VS Code terminal, run:

```bash
npm install
npm run dev
```

Keep `npm run dev` running while you work.

The `dev` command:

- copies Preline's browser JavaScript to `js/vendor/preline.js`;
- starts Tailwind watch mode;
- rebuilds `css/output.css` when your HTML changes.

Preview `index.html` with Live Server.

## What Is Already Set Up?

- Tailwind CSS 4
- Preline UI
- Tailwind Forms
- Alpine.js through the approved CDN
- responsive client page
- accessible baseline HTML
- client content and starter images
- clearly marked Alpine and Preline work areas
- Mac/Windows-friendly npm scripts

### Versions

- Tailwind CSS 4.3.3
- Tailwind CLI 4.3.3
- Preline UI 4.2.0
- Tailwind Forms 0.5.11
- Alpine.js CDN 3.17.1

Do not change versions unless your instructor tells you to.

# Requirement 1 — Alpine-Powered Exploration Tool

Use Alpine to help a visitor explore, narrow, compare, select, or better understand the supplied maker content.

Required:

- `x-data`
- at least one user event
- at least one additional reactive directive
- visible, understandable interface response
- semantic, keyboard-accessible controls

Search `index.html` for:

`TODO: REQUIRED ALPINE INTERACTION`

Do not copy the classroom Alpine playground unchanged.

# Requirement 2 — Adapted Preline Component

Choose one Preline component that improves the supplied client page.

Possible choices:

- accordion
- tabs
- modal
- dropdown
- alert
- another instructor-approved component

Required:

- solve a real client/user need
- use official Preline structure
- retain meaningful client content
- adapt styling with Tailwind utilities
- remain keyboard usable
- preserve accessibility behavior
- work at narrow, medium, and wide widths

Search `index.html` for:

`TODO: REQUIRED PRELINE COMPONENT`

# Scope Rule

Your Alpine interaction and Preline component must solve **different problems**.

# Why `js/vendor/preline.js` Exists

`node_modules` should not be committed or relied on by GitHub Pages.

Running:

```bash
npm run dev
```

or:

```bash
npm run build
```

copies Preline from:

```text
node_modules/preline/dist/preline.js
```

to:

```text
js/vendor/preline.js
```

Commit the copied runtime with your finished project.

# Before Pushing to GitHub

Run:

```bash
npm run build
```

Then confirm these contain real generated code:

```text
css/output.css
js/vendor/preline.js
```

Commit both files.

Do not commit `node_modules/`.

# Required README Documentation

Replace each TODO before submitting.

## Project Summary

I was tasked with coding one alpine interaction and one preline component to solve different tasks for the Mission City Makers Market webpage. I decided to use Alpine to create a modal for each maker to highlight their information individually. I also used Preline to simplify the FAQ section into an accordion group. My end goal was to make sure these components highlighted the included information while being easily accessible.

## Alpine Decision

**User/client need:**  
Explore each maker.

**Alpine directives used:**  
x-data, x-on, x-cloak, x-show, x-transition

**Why Alpine was appropriate:**  
Alpine easily handles the display transitions for each modal button without needing to write a script.

## Preline Decision

**Preline component selected:**  
Accordion

**Problem it solves:**  
It allows users to quickly identify the question relevent to them without the need to read through irrelevant information.

**How you adapted it:**  
I turned each article from the previous grid into an accordion item.

## Accessibility Notes

1. Both components have been tested for keyboard navigation.
2. Added high contrast hover states that matched the theme of the webpage.

## Testing Notes

**Narrow viewport:** I changed the window size to be narrow to check that the components displayed properly. Both sections passed
**Medium viewport:** I changed the window size to be medium to check that the components displayed properly. Both sections passed  
**Wide viewport:** I changed the window size to be wide to check that the components displayed properly. Both sections passed 
**Keyboard testing:** I used the keyboard to navigate the page and interact with the components. Both sections passed  
**Browser console:** I used the mouse to navigate the page and interact with the components. Both sections passed

## Dependencies

**Alpine.js — how used:** Used to create a component that can be adjusted to accomodate desired states, events, and responses.
**Preline UI — how used:** Used to insert a lightweight interactive component.
**Tailwind CSS — how used:** Used to create the output.css used to stylelize the components.

## Official Documentation Used

- Alpine.js: Modal
    https://alpinejs.dev/component/modal
    https://www.penguinui.com/components/modal
- Preline UI: Accordion - Bordered 
    https://preline.co/docs/components/accordion.html

# Official References

- https://alpinejs.dev/start-here
- https://alpinejs.dev/directives/
- https://preline.co/docs/
- https://preline.co/docs/components.html
- https://preline.co/docs/accessibility.html

# Final Check

- [x] `npm run build` completes.
- [x] Tailwind styles load.
- [x] Alpine interaction works.
- [x] Preline component works.
- [x] They solve different needs.
- [x] Keyboard testing works.
- [x] Responsive testing is complete.
- [x] Console has no unresolved errors.
- [x] README is complete.
- [x] `css/output.css` is committed.
- [x] `js/vendor/preline.js` is committed.
- [x] `node_modules` is not committed.
- [x] Work is pushed to GitHub.
