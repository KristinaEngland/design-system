# Breadcrumb Navigation
Breadcrumbs are a particular type of navigation that helps a visitor understand their current location in the website's hierarchy.


## When to use
- Use the breadcrumbs component when you need to help users understand and move between the multiple levels of a website.

## When not to use
- Breadcrumbs shouldn’t be used for flat sites (single level navigation) because they create unnecessary clutter.

## Accessibility & Usability

- Always place breadcrumbs at the top of a page, before the Main landmark. Placing them here ensures that when someone uses the Skip to main content link, they will skip over all navigation links, including breadcrumbs.
  Use an ordered list versus an unordered list - this indicates hierarchy versus just being a list of items.
- All the pages in the breadcrumb component should be interactive (except the current page) and link to their respective pages.
- Use a nav element with the role attribute equal to "navigation."
- use a aria-label element to indicate the type of navigation element, set to "breadcrumb"
- If the current page is represented in the breadcrumb, use aria-current attribute set to "location."
- List items are enough of an indication of the location level. Separators are just for visual presentation and should be added either with CSS or hidden from assistive tech with an aria-hidden attribute


## HTML and CSS

<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/team/UMPO_ADDT/embed/gOXgabV?default-tab=html%2Cresult" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/team/UMPO_ADDT/pen/gOXgabV">
  Untitled</a> by App Dev & Digital Transformation (<a href="https://codepen.io/team/UMPO_ADDT">@UMPO_ADDT</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
