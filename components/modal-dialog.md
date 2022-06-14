# Modal Dialog
Modal dialogs are pop-up windows that disrupt the flow of what a user is doing and demand an action. They are appropriate when the user’s attention needs to be directed toward important information that cannot be conveyed within the page.

## When to use
As documented by the Nielsen Norman Group, modal dialogs should be used in the following cases, for content that requires interrupting a user's workflow:
- Use modal dialogs for important warnings, as a way to prevent or correct critical errors.
- Use modal dialogs to request the user to enter information critical to continuing the current process.
- Use modal dialogs to ask for information that, when provided, could significantly lessen users’ work or effort.

## When not to use
- Do not use modal dialogs for nonessential information that is not related to the current user flow.
- Avoid modal dialogs that interrupt high-stake processes such as checkout flows.
- Avoid modal dialogs for complex decision making that requires additional sources of information unavailable in the modal.

## Accessibility and Usability
- Modals should be used sparingly as they interrupt a person's workflow. 
- The modal dialog should receive keyboard focus when activated so that keyboard and screen reader navigation begins at the top of the modal content. Never force the focus to land anywhere else in the dialog.
- A person using keyboard navigation should be able to close the modal by  hitting the Esc key and pressing a Close button (both options should be available).
- Once a modal is closed, focus should be returned to the button that triggered the modal dialog.

## HTML and CSS
