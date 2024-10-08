# Delightful Bite

The Delightful Bite is a website page for anyone who wants to learn new recipes and discover new flavors. The Delightful Bite provides detailed guidance, with an ingredient list, instructions, cooking tips, and nutritional value for those who want to track the calories. It is made for you do not get lost while doing a new recipe.

The user will be able to see our brief description of the recipe on the homepage, so the user can choose which one they want to do before they click on the recipe and get moved to another page. The Delightful Bite website targets everyone who dares to try new flavors.

![Responsible screenshot](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/responsible-screen.png)

## User Stories

### User
> As a user I want to be able to find recipes easily without much clicks.   
> As a user I want to be able to find easy recipes to make.     
> As a user I want to be able to see the nutritional value of the recipe.   
> As a user I want to be able to have a detailed guide of the recipe.   
> As a user I want to be able to get notified when a new recipe is online.  

### Business Owner
>As the site owner I want to provide detailed guide of recipes to users.    
>As the site owner I want to provide to user new recipes every week with new different flavors.   
>As the site owner I want to allow the user to choose which recipe is better to make based on a brief   description of the recipe.  
>As the site owner I want to bring back the tradition of recipe pass from generations.  
>As the site owner I want to show the user the nutritional value of the meal.   
>As the site owner I want to make user taste recipes from other cultures without leaving home.  

## Features

- __Navigation Bar__

    - Featured at the top of the page, the navigation bar shows a Recipe that links to the recipe section, Contact Us that links to the Contact Us and Sign Up which opens a new page with a sign-up form.
    - The navigation provides the user with easy and kick access to the section on the page.
    - The navigation background color is orange, to highlight the page.
    
    ![Nav Bar](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/navbar.png)

- __The Header__

    - The header has an image and a about us.
    - The image shows the name of the website in green surrounded by food images. The About Us tells the purpose of the website.

    ![Header](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/header.png)

- __Recipes Section__

    - The recipes section has 3 recipes, hamburger, cheesecake. and homemade pizza. 
    - Each recipe has an svg corresponding to the dish, an anchor that when clicked opens another page with more details of the recipe, and a brief description.
    - The brief description shows the user if that dish is a good choice, before being taken to another page.

    ![Recipes Section](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/recipe-section.png)

- __Recipes Pages__

    - The Recipe pages can be accessed by clicking on the anchor below the image on the home page. The anchor has the name of the recipe.
    - The Recipe page provides a navbar on top with Home, Recipes and Contact Us anchor,an image from the recipe, and the instructions to make the recipe.
    - The instructions contain a background color matching the image color, title, description of the recipe, preparation time, ingredients, instructions, serving, and nutritional value.
    - The Recipe page provides to the user recipes with more details and deep guidance.

    ![Recipes Pages](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/recipe-page.png)

- __Contact Us__

    - The feature is at the bottom of the page, The Contact Us shows the user how they can find us.
    - Contact Us has a big title inside a box, and also has a green background. 
    - Contact Us provides an email below an envelope icon and 3 icons which are Facebook, Twitter, and Instagram. The 3 icons down below when clicked open a Delightful Bite social media.
    - Contact Us encourages users to get in contact if any help is needed while making the plate or scrolling the website.


    ![Contact Us](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/contact-us.png)

- __Sign Up__

    - The sign-up page can be accessed by clicking on the Sign Up "anchor" in the navbar.
    - Sign Up provides a form with validation that contains a title, name, email, radio button, and a sign-up button to submit the form.
    - The page contains a navbar on top, a title, an image, and a form. The page has a whitesmoked background color.
    - The Sign Up page encourages users to sign up and get access to more recipes.

    ![Sign Up](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/sign-up.png)

- __Sign Up Confirmation Page__

    - The sign-up confirmation page can be accessed after submitting correctly the form on sign-up page.
    - The sign confirmation page is made for users to make have sure the sign was made correctly.
    - The page provides and navbar on top, a big text thanking for the sign-up, a section showing the recipes on the page and, a contact us section.

    ![Sign Up Confirmation](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/sign-confirmation.png)

## Skeleton Plane

- __Home Page Desktop Wireframe__

![Desktop Wireframe](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/homepage-desktop.png)

- __Home Page Mobile Wireframe__

![Mobile Wireframe part1](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/homepage-mobilepart1.png)

![Mobile Wireframe part2](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/homepage-mobilepart2.png)

> The design flow of the website is meant to be minimalist with a cartoon. Made to be easier to understand and accessible for all ages.

> The color pattern is mainly white, green, and orange, made to match the first image (that with the website name).

## Testing

**Testing Links and Form**
| Test | Outcome |
|--|--|
|All links on Navigation lead to their correct pages| Pass |
|Contact button leads to contact section | Pass|
|Footer social links all lead to their respective social media sites| Pass |
|Sign Up form submits when all criteria is filled correctly| Pass |
|User prevented from submitting form without correct element| Pass |
|Form Validation presents when incorrect input type is entered | Pass|

**Testing for responsiveness**
| Test |Outcome  |
|--|--|
|Home page, about us, contact up, sign up, recipes page, sign up complete page displays correctly on mobile, tablet, laptop and desktop | Pass |

> No Issues reported from 3 users

### Bugs

- __Fixed Bugs__

- At first the score in performance and accessibility were low.
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/accessibility.png)
    - The accessibility score was fixed by adding an arial label to icons and fixing the order of the 'H' element. However, the LCP (Largest Contentful Paint element) was making the performance score low.
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/second-accessibility.png)
    - This bug was fixed adding load priority to the image and compressing the image.

- __Unfixed Bugs__

When the website is open on an iPhone mobile, the button to submit the form on the Sign Up page does not show up, still submitting the form, but does not have any text inside the button. 
![Iphone-Bug](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/bug-iphone.jpg)

The bug does not happen when the page is opened in an android phone:

![Androind-Bug](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/bug-android.jpg)
    
> Good to mention this is a picture with an old version of the website (with the password input) but the button text still shows even in current versions.

### Validator Testing

- HTML
    - No errors were returned when passing through the official W3C validator
    - Index.html
    ![W3C Html](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-html.png)
    - sign-up.html
    ![W3C Html](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-signup.png)
    - sign-up-complete.html
    ![W3C Html](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-signcomplete.png)
    - cheesecake.html
    ![W3C Html](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-cheesecake.png)
    - hamburger.html
    ![W3C Html](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-hamburger.png)
    - pizza.html
    ![W3C Html](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-pizza.png)
    
- CSS
    - No errors were returned when passing through the official (Jigsaw) validator
    ![W3C CSS](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/w3c-css.png)
- Accessibility
    - Lighthouse test index.html
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/third-accessibility.png)

    - Lighthouse test sign-Up.html
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/lighthouse-sign.png)

    - Lighthouse test sign-up-complete.html
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/lighthouse-sign-complete.png)

    - Lighthouse test piza-html
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/lighthouse-pizza.png)

    - Lighthouse test hamburger.html
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/lighthouse-hamburger.png)

    - Lighthouse test cheesecake.html
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/lighthouse-cheesecake.png)

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

  > I then received a notification from GitHub that my project is being deployed and after about 1 minute & a couple of refreshes of the page it was ready and live.

The live link can be found here - https://jonatas-01.github.io/delightful-bite/index.html

## Credits
 > favicon: (https://www.flaticon.com/free-icon/strawberry_15674863?term=bite&page=1&position=11&origin=search&related_id=15674863)

 > hamburger image: (https://storyset.com/illustration/hamburger/bro)

 > pizza image: (https://storyset.com/illustration/pizza-sharing/bro)

 > cake image: (https://storyset.com/illustration/red-velvet-cake/bro)

 > home page image: (https://www.freepik.com/free-vector/abstract-hand-drawn-recipes-youtube-channel-art_13109020.htm#fromView=search&page=2&position=39&uuid=b029be65-745b-4eb7-a2e1-8485b8b3897d)

 > sing up image: (https://storyset.com/illustration/computer-login/amico)

 > icons: (https://fontawesome.com/)

### Content

- Recipes taken from ChatGPT
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Idea for Recipes pages taken from [Front End Mentor](https://www.frontendmentor.io/challenges)
- Favicon taken from [Flaticon](https://www.flaticon.com/free-icon/strawberry_15674863?term=bite&page=1&position=11&origin=search&related_id=15674863)
- General lookup for HTML and CSS taken from [w3 school](https://www.w3schools.com/)

### Media

- Svg's used on recipes taken from [Storyset](https://storyset.com/)
- Logo Photo on home page taken from [FreePik](https://www.freepik.com/)

## Acknowledgements

- __Alan Bushell__

> My mentor who provided me with constructive feedback and positive reinforcement where applicable.