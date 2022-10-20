# Select

The Select component is used on forms to select one item from a list. 

## When to Use
- Use the select component inside a form where users are selecting from a list of options and submitting data.
- If there are a significant amount of items to select from, consider implementing a search for the Select list.

# When Not to Use
- The Select component should only be used for long lists (radio buttons should be used short lists of values).

# Accessibility and Usability
- The visible label for the Select component should match the behind the scenes label to ensure the label works with all types of assistive technology. See WCAG Label in Name for more details.
- The label should not be placed inside the Select component - placeholders are never a substitute for labels as they can cause issues with assistive technology as well as be hugely problematic for anyone with cognitive or memory issues.
- Provide real time validation and ensure any errors are coded to be read by assistive technology.
- Ensure the select component is both usable with a mouse and keyboard. 
- If the Selec component has an autocomplete look up, ensure the search results are being read to screen reader users and that the results are reachable by keyboard and mouse.
- If you use the  component for questions, you should not pre-select any of the options in case it influences users’ answers.
