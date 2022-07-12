# Toggle
Toggle switches allow users to switch between on and off settings. They are most often seen in user preferences for systems. There is always a default setting, which should be established during the design phase. In addition, you can leverage a user's system preferences to determine what the default is when they create an account in the system. For example, if a user already has a system preference to reduce preferred motion, you can configure the toggle switch to change based on their system preferences so that the user doesn't need to manually change the default setting. 

## When to Use
- When the goal is to change the state of system functionalities and preferences; and
- When the change will be immediate. 

## When Not to Use
- When a process requires the user to press the submit button - either radio buttons or a checkbox should be used in this case.

## Accessibility and Usability
- Toggle switches should take immediate effect and should not require the user to click Save or Submit to apply the new state.
- The toggle label should describe what the control will do when the switch is on; they should not be neutral or ambiguous. When in doubt, say the label aloud and append “on/off” to the end. If it doesn’t make sense, then rewrite the label.
- Use <button> elements, not links, with aria pressed or aria checked.
- Use aria-pressed to turn the button into a toggle. Aria-pressed will convey the button's current "pressed" state.
- Do not rely on color alone to indicate a toggle button's change in state
