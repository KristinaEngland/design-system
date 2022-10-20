# Side Navigation

Create a vertical list of navigation links for use in a sidebar 

## When to Use
- When sub-content on a site requires it's own menu. For example, a department site with several main page and sub-pages that would not fit into the main navigation of the site. 

## When Not to Use
- For sub-content that does not have multiple pages of content.

## Accessibility and Usability

- Navigation components should have clearly defined Navigation landmarks behind the scenes. The Sub navigation should thus have a clear landmark name to delinate it from the main navigation of the site, such as "Section Pages" or "In this Section." 
- Use the “active” state to show users which page they are currently on in the side nav. 
- If a side nav menu requires multiple levels, ensure you categorize all the sub-pages under thoughtful top level categories so that they are intutitve to find.
- If the side nav is multiple levels, always provide the user with a visual indicator that there will be sub-pages, such as a plus sign. This is especially important on mobile where the whole page will refresh and the mobile menu will collapse. If a person is not provided with a hierarchy indicator, they won't know to go back to the menu to access sub-pages. In addition, when possible, provide another way to navigate to sub-pages that accounts for mobile, such as tiles that repeat the sub-items on the main category page. 
