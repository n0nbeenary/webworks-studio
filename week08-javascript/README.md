# Week 8 — JavaScript Interaction Handoff
## Hill Country Trail Guide

**Primary User:** Maya Torres

## Required Behaviors
1. Accessible trail-difficulty disclosure
2. Hike-planning form validation/submission feedback

---

## JavaScript Decisions

### Decision 1 — DOM Selection
What elements did your script need to select, and why?

difficulty-toggle: This is the button to toggle the difficulty panel
difficulty-panel: This is the difficulty panel that is hidden/shown when the difficulty toggle is clicked



### Decision 2 — Event Handling
What events did you listen for? Why were those events appropriate?

For the difficulty panel, my script listened for when difficulty-toggle was clicked because the difficulty panel will remain hidden if the button is not clicked.



### Decision 3 — State / DOM Update
How did the interface change after user action?

For the difficulty panel, the help-card section was expanded to display the difficulty panel.

### Decision 4 — Accessibility
How did you preserve or improve keyboard/accessibility behavior?

I preserved accessibility by having the script update aria-expanded, therefore having the visual state matches the same information the assistive technology has.

---

## Testing Notes

### Difficulty Disclosure
- Mouse: No issues found, tested as expected
- Keyboard: No issues found, tested as expected
- `aria-expanded`: Initially could not test 'aria-expanded' because I forgot to add "console.log(isOpen);" to my script. After adding it, the test went as expected
- Console errors: No errors occured

### Planning Form
- Empty/invalid submission:
- Valid submission:
- Keyboard:
- Console errors:

---

## Live Site
[Add GitHub Pages URL here.]
