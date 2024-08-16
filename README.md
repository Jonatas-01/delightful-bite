# Delightful Bite

The Delightful Bite is a website page for anyone who wants to learn new recipes and discover new flavors. The Delightful Bite provides detailed guidance, with an ingredient list, instructions, cooking tips, and nutritional value for those who want to track the calories. It is made for you do not get lost while doing a new recipe.

The user will be able to see our brief description of the recipe on the homepage, so the user can choose which one they want to do before they click on the recipe and get moved to another page. The Delightful Bite website targets everyone who dares to try new flavors.

![Responsible screenshot](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/responsible-screen.png)

## Features

- __Navigation Bar__

    - Featured at the top of the page, the navigation bar shows Recipe that links to recipe section, Contact Us that link to the contact us and Sign Up which a open a new page with sign up form.
    - The navigation provide the user an easy and kick access to the section in the page.
    - The navigation background color is orange, to highlight in the page.
    
    ![Nav Bar](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/navbar.png)

- __The Header__

    - The header has an image and a about us.
    - The image shows the name of the website in green sourounded by food images. The About Us tells the porpose of the website.

    ![Header](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/header.png)

- __Recipes Section__

    - Recipes section has 3 recipes, hamburger, cheesecake and homemade pizza. 
    - Each recipe has an svg corresponding for the dish, an anchor which when clicked open another page with more details of the recipe, and an brief description.
    - The brief description shows the user if that dish is good choice, before being taken to another page.

    ![Recipes Section](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/recipe-section.png)

- __Recipes Pages__

    - The Recipe pages can be accessed clicking on anchor bellow the image in the home page. The anchor has the name of the recipe.
    - The Recipe page provides an navbar on top with Home, Recipes and Contact Us anchor, image from the recipe, and the instructions to make the recipe.
    - The instructions contains a background color matching the image color, title, description of the recipe, preparation time, ingredients, instructions, serving and the nutricional value.
    - The Recipe page provides to the user the recipe with more details and deep guidance.

    ![Recipes Pages](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/recipe-page.png)

- __Contact Us__

    - The feature is at the bottom of the page, The Contact Us shows the user how they can find us.
    - Contact Us has a big title inside a box, also has a green background. 
    - Contact Us provides an email bellow an evenlope icon, and 3 icons which is Facebook, Twitter and Instagram. The 3 icon down bellow when clicked opens a Delightful Bite social media.
    - Contact Us encourages users to get in contact if any help in needed while making the plate or scrolling the website.


    ![Contact Us](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/contact-us.png)

- __Sign Up__

    - The sign up page can be accessed clicking on Sign Up "anchor" in navbar.
    - Sign Up provides an form with validation that contains a title, name, email, radio button and a sign up button to submit the form.
    - Page contains a navbar on top, title, image and a form. The page has a whitesmoked background color.
    - The Sign Up page encourages users to sign up and get access to more recipes.

    ![Sign Up](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/sign-up.png)

- __Sign Up Confirmation Page__

    - The sign up confirmation page can be accessed after submit correctly the form in sign up page.
    - The sign confirmation page is made for user have sure the sign was made correctly.
    - The page provides and navbar on top, a big text saying thanking for the sign up, a section showing the recipes in the page and a contact us section.

    ![Sign Up Confirmation](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/sign-confirmation.png)

## Skeleton Plane

- __Home Page Desktop Wireframe__

![Desktop Wireframe](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/homepage-desktop.png)

- __Home Page Mobile Wireframe__

![Mobile Wireframe part1](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/homepage-mobilepart1.png)

![Mobile Wireframe part2](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/homepage-mobilepart2.png)

> The design flow in the website is meant to be minimalist with a cartoon. Made to be easier to undesrtand and accessible for all ages.

> The color patern is mainly white, green and orange, made to match with the first image (that with website name).

## Testing

 - Tested that this page works in different browsers: Chrome, Firefox, Edge, Mobile Safari.
 - Confirmed that this project is responsive, looks good and functions on all screen sizes.
 - Confirmed that the navigation, header, recipes section and pages, contact us and sign up text are all readable and easy to understand.
 - Confirmed that the form works: requires entries in every field, will only accept email in the email field, and submit button works.

### Bugs

- __Fixed Bugs__

- At first the score in performance and accessibility were low.
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/accessibility.png)
    - The accessability score were fixed adding arial label to icons and fixing the order of the 'H' element. But the LCP (Largest Contentful Paint element) were making the performance score low.
    ![Accessibility](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/second-accessibility.png)
    - This bug was fixed adding load priority to the image and compressing the image.

- __Unfixed Bugs__

When the website is open in an Iphone mobile, the button to submit the form in Sign Up page does not show up, still submiting the form, but does not have any text inside the button. 
![Iphone-Bug](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/bug-iphone.jpg)

The bug does not happen when the page is opened in an androind phone:

![Androind-Bug](https://github.com/Jonatas-01/delightful-bite/blob/main/assets/media/readme-img/bug-android.jpg)
    
> Good to mention this is a picture with an old version of the website (with the password input) but the button text still showing even in current versions.

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