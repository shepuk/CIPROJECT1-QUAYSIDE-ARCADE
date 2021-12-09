<h1>Quayside Arcade Website</h1>

[View the live project here.](Insert link here)

Quayside Arcade is a fictional modern arcade/bar/cafe, and a project which I have created to display and test various HTML, CSS and Bootstrap skills. It consists of three static web pages with a consistent design throughout.


## User Experience (UX)

-   ### User stories

    -   #### New Visitor Goals

        1. As a new visitor, I want to find information on what the venue has to offer me.
        2. As a new visitor, I want to find out how to find the business.
        3. As a new visitor, I want to look at images and see what it's like inside the business.
        4. As a new visitor, I want to find out about any upcoming events I could be involved in.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to check on upcoming events.
        2. As a Returning Visitor, I want to find contact details for the organisation.

-   ### Design
    -   #### Colour Scheme
        -   I used a color palette tool (https://coolors.co/) to find a pleasing set of colours to use in the design of the website. The main colours used are: #e63946, #ff9d9d, #457b9d, #1d3557 & #212529
    -   #### Typography
        -   Bebas Neue and Barlow Semi Condensed fonts are main fonts used throughout the website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. These custom fonts are modern, readable and pleasing to the eye, making the website more enjotable as a result.
    -   #### Imagery
        -   Various stock imagery has been used througout the website. I was careful to choose images which complemented the design/ font/ colour scheme etc.

*   ### Wireframes


## Features

-   Responsive on all device sizes

-   Interactive elements

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 5:](https://getbootstrap.com/docs/5/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)




##### BUG - Text not centered in call to action button, hero section. Resolved by removing parent div of <p> elememt and aligning <p> element instead.
##### BUG - .nav-link hover effect not displaying correctly when in phone/tablet dropdown state - resolved with stackoverflow post (link in css)
##### BUG - Some horizontal scrolling sactivated once viewport is below 992px - caused by hero image media query - used 100% rather than 100vw
##### BIG - Event cards hug left of viewport when in mobile view - Resolved, issue caused by bootsrap/custom styling conflict. Altered min/max div sizes and added left/right margin with a media query to center as desired.
