# Homework-01

![About Page](/02-Homework/Assets/Images/AboutMePage.png)

![Portfolio Page](/02-Homework/Assets/Images/PortfolioPage.png)

![Contact Page](/02-Homework/Assets/Images/ContactPage.png)

## HTML and Bootstrap

I started with building the basic html for this page with bootstrap to get my columns and positioning for the largest screen size first, starting with the navbar and moving down the page.

### Nav bar

I used the bootstrap grid layout to build this. breaking the navbar into 3 elements: the title portion, blank space, then the nav links.

### About Me content

I used the Bootstrap grid layout to define the size of the card

everything in the card was defined as a bootstrap class card-content

I placed a h4 tag for the title of the card, an image, and a section containing my bio

### portfolio content

i copied and pasted the card over, maintaining the size and general layoout

i changed the content of the h4 header and removed the rest of the card contents

i created an internal grid system with 3 rows and two columns each

the div with the column class i left blank with the intention of using css to link a background image for each card

inside the columns i added another div with the caption for each card

the last column in the last row i left blank, just there to keep the last card positioned properly to the left

### contact content

i once again copied the card over to get the same basic layout, and changed the title of the card

i copied over a blank form from bootstrap twice and changed the content to match the example

i compied over a long message form group from bootstrap as well along with a button

## CSS

### Nav bar

I changed the font of all the h headings throught the page to be more similar to the example

for the name portion of the navbar i changed the font and background color to match the example, centered the text and added padding on the top and bottom based on my preferences

i adjusted the links to not have text decoration

i set a class for each link in the nav and put a border on the right and adjusted the padding for all the links (except for the first one that got special padding)

### About Content

for the card, i wanted to match the example so i picked a similar color for the border, added a margin on top and bottom to add space between the car and the nav and the footer, and changed the border radius to not have rounded edges

the card title needed padding on the bottom to add space between the text and the bottom border i added to match the example, i added a margin after that to add space between the border and the rest of the card content, for the title text i changed the font color

i changed to color of the rest of the text in the card

for the picture, i floated it left in the card, adjusted the size to maintain its aspect ratio and fit the carrd better, and added a margin to the right to add space between the image and the text

### Portfolio Content

i copied and pasted the basic styling of the card from the about page

for each portfolio image in the card, i linked the image as a background image, controlled the aspect ratio to be consistant and added a margin

for the caption i set the div position as absolute to adjust teh positioning based on the image in the parent div, adjusted the width of the caption to reach across the entirety of the parent element, centered the text and adjusted the background and font color and font family

### Contact Content

I copied over the basic css from the portfolio card

for each label for the forms, i adjested the font color

i removed the border radius for the button, removed the color of the borderm, and adjusted the padding to match the example better

## Media Query

for the navbar i made a query that made the name portion and the nav portion take a whole row each when the screen was below 640px

for the about card, i added padding along the top of the bio and cleared the bio from the float when below 640px

for the image in the about card i set the width to 100% and the height to auto when the screen is below 640px

i got a little tricky for the portfolio card images because they were set as background images, it made the divs act strange when below 640 px. i set the width of the div to 100R% to fill the card horizontally, set the height of the div to 0 and added padding to the top at 75% to maintain the 4:3 aspect ratio of the image