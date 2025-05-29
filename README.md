# odin-recipes
This is a simple project built as part of The Odin Project curriculum to practice basic HTML stucture, linking, and content organization. This site contains and intex page with links to multiple recipe pages, each containing structured information about a specific dish.

## Features
- Homepage listing multiple recipes
- Individual recipe pages with:
    - A title and image
    - A description
    - A list of ingredients
    - A step-by-step instruction guide
- Navagation links between recipe pages and the homepage

## Key Topics Learned
During this sections something new I learned ws about the target and relation attributes on the anchor tag. One of my goals throughout this course was to enhance my skills involve security and privacy and the relation attribute related to that goal.
1. Target Attribute:
    - By defualt, takes _self vaule, which opens link in current tab
    - To open link in new tab or window you can set it to _blank
2. Relation Attribute:
    - noopener: ensures that a link opened in a new tab or window cannot interact with or access the original page (without it, the new page can use JS to manipulate the original page, posing a security risk)
    - noreferrer: prevents the new page from knowing where the user came from (hiding the referrer) and also includes the behavior of noopener, preventing the new page from accessing the original page (but you still need to add noopener with noreferrer)