# Radio Buttons

## When to Use
- When the user can only select one value, and
- When the selection of a value is required. 

## When Not to Use
- When the selection of a value is optional. In this case, you should use a dropdown list instead. Otherwise, users could accidentally select a value when completing a form. There is no way to unselect a radio button value once one is selected without refreshing the form and losing valueable data.
- When the user needs to select multiple values. In this case, you would use the checkbox component. 

## Accessibility and Usability
- As noted above in the When Not to Use section, avoid using radio buttons for optional fields as the selection of a radio button can't be undone. However, if you do choose to use a radio button for an optional field, provide a "none of the above" option so the user can switch their answer to none of the above in a case where they accidentally selected a value. 
- Group related radio buttons together with <fieldset> and describe the group with <legend> to ensure they are accessible to assistive technology.
- Each radio button should have a <label>. Associate the two by matching the <label>’s for attribute to the <input>’s id attribute. This matching is not only important for screen reader users who need the label to match the input ID so that they hear the correct label, but is also important for speech recognition users so they can speak the visual label and activate the radio button with their voice. See WCAG's [Label in Name](https://www.w3.org/WAI/WCAG21/Understanding/label-in-name.html) for more details. 
- Avoid setting a default value as this can accidentally come across as biased towards a sepcific answer, especially in the case of gender identity or race. 
