# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

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
THEN I find semantic HTML elements @
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning @
WHEN I view the image elements
THEN I find accessible alt attributes @
WHEN I view the heading attributes
THEN they fall in sequential order @
WHEN I view the title element
THEN I find a concise, descriptive title @

@ = finished to the best of my ability
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

## student notes and changes
I changed the title to the name of the company. A lot of the class selector were made IDs becuase class was unnecessary. I also added the background image to the HTML using an image tag inside the original tag(which was changed from div to section for SEO purposes). The style sheet had to be changed because of this. I added an ID to target the new HTML image element and applied css properties to it. Half of the properties in #hero were maintained. I added the alt attribute to image tags. The structure of the HTML fell in a logical and understandable order, but  use the semantic format. I organized everythign in the body to be inside the head, main, footer tags. The section was used to wrap major sections of content on the page in the body tag. The aside was used instead of section of the content floated to the right. 

