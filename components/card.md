# Card Component

A card is generally a block element that contains common elements such as an image, heading, text, metadata, etc. Cards are a great way to display information that has a pleasing layout that also works well on mobile devices. General practice is to make the entire card clickable.  However, that often creates a less-than great experience for some users of assistive tech as it is variable what content will be read.  We prefer to keep each element separate and use the title of the card as the link.  Doing it this way also allows people using screen readers to browse the cards by title or by link.

## When to Use

- Use cards to create a graphically pleasing teaser of content. 

## When not to use

- Do not use cards for a long list of content as a list is more easily scanned and will provide users of assistive technology the expectation of how many items are in the list they are about to browse through.
- Do not use cards when each item contains a number of variables that need to be easily scanned and could also provide a method for sorting or filtering the data set.

## Accessibility and Usability

- Focus Indicator is the same for a mouse hover or keyboard focus.
- The link is the title of the card. 
  - You should make sure to use the proper heading level according to the cards location in your page content.
  - CSS for the Heading/link should follow already established link behavior for the rest of the site (i.e. color change on hover) 
  - When the link is the title of the card (usually the title of the page or article you are linking to) there is no need to add "read more" text on each card.  "Read more" will be the same text in each card and would make it impossible for voice recognition users to target the the correct "read more" link. 
- Image should contain alt text if there is information/intent in the image that is not conveyed by the image itself.  Use a blank alt attribute in order to skip the image in screen readers.
- Text in the card is read by screen readers and can be selected with a mouse.
- Text in the card should be short and easily scannable.  

## HTML and CSS

### Card Component with Image; Accessible

<iframe height="300" style="width: 100%;" scrolling="no" title="Card Component with Image; Accessible" src="https://codepen.io/team/UMPO_ADDT/embed/abLrdgK?default-tab=html" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/team/UMPO_ADDT/pen/abLrdgK">
  Card Component with Image; Accessible</a> by App Dev & Digital Transformation (<a href="https://codepen.io/team/UMPO_ADDT">@UMPO_ADDT</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

### Card Component, no Image; Accessible

<iframe height="300" style="width: 100%;" scrolling="no" title="Card Componet, No Image; Accessible" src="https://codepen.io/team/UMPO_ADDT/embed/zYEQBGV?default-tab=html" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/team/UMPO_ADDT/pen/zYEQBGV">
  Card Componet, No Image; Accessible</a> by App Dev & Digital Transformation (<a href="https://codepen.io/team/UMPO_ADDT">@UMPO_ADDT</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
