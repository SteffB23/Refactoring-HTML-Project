## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

<!--What was done to meet the acceptance criteria
1st- Modification to the elements included:
    A. Changing <div> to the corresponding symantic element i.e., <section>, <aside> & <summary>
    B. Ensuring that elements were placed on the targeted lines following a smooth open and closed placement. Various tags were placed above and below various structures
2nd- Added alts to the images giving them an accurate description of each image
3rd- Ensured that the heading attributes were accessible and functional
4th- Changed the title from "website" to Horiseon Social Services & Solutions>
5th- Also made minor changes to the CSS style by:
    A. Grouping sections with classes rathere than them being split individually (see notes on style.css)
6th- Changed benefits lead, brand & cost margin to match the centered blocks margins.   