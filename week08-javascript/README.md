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

hike-form: This is the form with the drop down options the user needs to select to plan their hike.
form-feedback: This is where the confirmation of the submission will appear once the form has been submitted.

### Decision 2 — Event Handling
What events did you listen for? Why were those events appropriate?

For the difficulty panel, my script listened for when difficulty-toggle was clicked because the difficulty panel will remain hidden if the button is not clicked.

For the hike form, my script listened for when the submit button was pressed because this told the form to check if the required fields in the form were selected and if the feedback could be displayed with a valid submission.

### Decision 3 — State / DOM Update
How did the interface change after user action?

For the difficulty panel, the help-card section was expanded to display the difficulty panel.

For the hike form, the form feedback was displayed underneath the submit button with a confirmation message.

### Decision 4 — Accessibility
How did you preserve or improve keyboard/accessibility behavior?

I preserved accessibility by having the script update aria-expanded, therefore having the visual state matches the same information the assistive technology has and by ensuring the interactions were keyboard accessible.

---

## Testing Notes

### Difficulty Disclosure
- Mouse: No issues found, tested as expected
- Keyboard: No issues found, tested as expected
- `aria-expanded`: Initially could not test 'aria-expanded' because I forgot to add "console.log(isOpen);" to my script. After adding it, the test went as expected
- Console errors: No errors occured

### Planning Form
- Empty/invalid submission: No issues found, tested as expected
- Valid submission:No issues found, tested as expected
- Keyboard: No issues found, tested as expected
- Console errors: No errors occured

---

## Live Site
[(https://n0nbeenary.github.io/webworks-studio/week08-javascript/index.html)]
