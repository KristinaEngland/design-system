# Pagination

Pagination provides users with the ability to navigate through large amounts of search results.

## When to Use
- when showing all the search content on a single page would impact page load performance; best practice is that if results exceed 25 items, you should provide pagination. 
- when users will not need to navigate the full amount of data.

## When Not to Use
- If pagination will not improve usability and page load performance. 

## Accessibility & Usability
- Clearly identify which page the user is on by displaying the current page number. 
- Do not use the load more infinite scroll technique instead of pagination. This causes problems for keyboard and assistive technnology users.
- Add the pagination at the bottom of the results as this makes it easier for keyboard and assistive technology users to navigate to the next page if needed.
- Limit the page to 25 results by default but give people the optiont to change the result limits up to 100 results. 
- Provide multiple ways to navigate the pagination - page numbers, previous and next buttons, as well as the ability to enter the page number. 
