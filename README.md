# 🎉FunTime-Celebrations

## Get to know us 

- A responsive, multi-page website built with HTML, CSS, and Bootstrap, showcasing fun and vibrant party themes for children’s celebrations. The project includes a gallery, service descriptions, and booking information, optimized for both desktop and mobile devices.
- FunTime Celebrations is a party organising service for parents. FunTime Celebrations offers the following services: themed parties, various entertainments, options for venues and catering, through different packages. 

##  🚀  Live Demo

👉 View the website [here]()

## 🛠 Technologies Used

HTML5

CSS3

Bootstrap 5

## GitHub User Story Project

A [project](https://github.com/users/IrinaAdeniyi/projects/4/views/1) containing user stories with acceptance criteria and tasks was created in GitHub. This was done to easily organize and prioritize work, as well as defining clear requirements and tracking progress.

## Wireframes

The wireframes for this website were created using [Balsamiq](https://balsamiq.com/education/)

*Disclaimer: The wireframes shown are for demonstration purposes only. The final implementation may vary from these initial representations.

### Home Page
![Homepage laptops wireframe](assets/wireframes/Home-laptops.png)
![Homepage tablets wireframe](assets/wireframes/Home-tablets.png)
![Homepage phones wireframe](assets/wireframes/Home-phones.png)

### Services Page
![Services laptops wireframe](assets/wireframes/Services-laptops.png)
![Services tablets wireframe](assets/wireframes/Services-tablets.png)
![Services phones wireframe](assets/wireframes/Services-phones.png)

### Gallery Page
![Gallery laptops wireframe](assets/wireframes/Gallery-laptops.png)
![Gallery tablets wireframe](assets/wireframes/Gallery-tablets.png)
![Gallery phones wireframe](assets/wireframes/Gallery-phones.png)

### Book Now Page
![BookNow laptops wireframe](assets/wireframes/BookNow-laptops.png)
![BookNow tablets wireframe](assets/wireframes/BookNow-tablets.png)
![BookNow phones wireframe](assets/wireframes/BookNow-phones.png)


## Building process
1. I started the project by creating the index.html and adding some of the links required in the project: meta links, favicons, CSS stylesheet, Bootstrap links, font awesome. I then created the layout of the home page.

2. I followed with the navigation bar and I created the remaining pages, adding the navbar, the boilerplate structure and the footer on each page.

3. I played with some color options to find something that I would like.

4. I then added the header and the *About us* section.

5. I proceeded to work on the *Services* section on the *Home* page.

6. I further styled the navbar and made the page responsive on mobiles and tablets. I finally tested the home page and moved to the next page *Services*.

7. On the services page I firstly added the background photo and text for each service: themes, entertainment, venues and food.

8. I then investigated how I can add some flip cards to present the offered packages. I struggled to make it work with Bootstrap, but managed to use some advice some W3Schools and make the cards flip.

9. I tested the *Services* page's links and responsiveness and made the necessary corrections.

10. As the *Gallery* page was a *should-have* page, I decided to continue with the booking form page, which was a *must-have*.

11. For the *Book Now* page I used a Bootstrap Form and added field for personal details like name and age, for email and phone number. I used dropdowns for *Party Package*, *Date and Time*, *Theme*, and *Enterntaiment*. Finally, I choose a textbox which requires the number of guests and offers flexibility to add any other requests or comments.

12. I continued by adding the background of the page, the title of the page and the booking button.

13. Once the *Book Now* page was fully responsive, I created a *Confirmation* page, to present the user with, once they press the *Book Party* button.

14. I styled the *Confirmation* page to fit with the rest of the website: it has a navbar and footer, a background picture, a button matching the othe rbuttons on the website and same fonts as the rest of the website.

15. The button on this page takes the user back to the home page.

16. Finally, I created the *Gallery* page. This page was created by using the *img-fluid* bootstrap class.

17. Once I completed the website, I checked that all links and buttons work as expected. I then tested for responsiveness on all pages and made the necessary adjustments. 

18. Once I finalised the manual checks, I used tools like HTML and CSS validators, as well as the Lighthouse feature in Chrome DevTools. The lighthouse tool higlighted some issues that were resolved to the best of my ability.

19. Finally the README file was updated.

## 📂 Project Structure
- **assets/**: Contains the static files for the website.
  - **css/**: The folder containing the main styles for the site (style.css).
  - **images/**: Contains all images for the website, with subfolders for the favicon, gallery and logo images.
- **HTML files**: The main content pages of the website:
  - `book-now.html`: The booking page.
  - `confirmation.html`: The confirmation page after booking.
  - `gallery.html`: The page displaying the gallery.
  - `index.html`: The homepage.
  - `services.html`: The page showcasing the services.

## Features
1. Navbar with logo and links to different pages




2. Flip cards to showcase different party themes

3. Image gallery for inspiration

4. Booking call-to-action

5. Clean and simple navigation bar

6. Footer with contact and social links

## Testing 
Detailed testing was done on the website to ensure the website works properly.

| Feature    | Expected behaviour | Outcome  |
| -----------|:------------------:| --------:|
| Header     | Looks good in all screen sizes|  Works as expected        |
| Logo       | On click takes you to home page                   | Works as expected         |
| Navigation bar | Active page bold, colapse on phone size, logo only on mobile       | Works as expected         |
| Book now button on navbar and header | Takes you to Book now page | Works as expected
| Abouts us section | Looks good in all screen sizes | Works as expected |
| Services section on home page | Links take you to the services page and cards display properly in all screen sizes | Works as expected

## Troubleshooting
1. I had an initial issue with the favicon, as I was unsure how to create a new one for my website. After reading the documentation I was able to add the right favicon for my website and make it work.

2. I encountered an issue with the navbar position, but after carefully reading the documentation on Bootstrap it was resolved.

3. I struggled to position the text in the footer (Contact section) - but was resolved reading documentation. 

4. While styling the navbar, the CSS I used to change the text colour in the navbar overrode the *active* class from Bootstrap. After researching I managed to find the solution by targeting the *active* class and giving it a different colour and style them bold.

5. I discovered I used a redundant class for the hero section and rectified the mistake.

6. The *About us* section on the home page kept showing next to the hero section. I managed to resolved this by using the flex-column class from Bootstrap.

7. I had issues with the way the page was scrolling and after investigating I realised I set a height to the hero section, which was interfering with the way the page was displayed - it was cut instead of scrolling.

8. The home page was not showing properly on mobiles and tablets, so I used media queries to adjust how the navbar, text, cards and footer look on these screens.



## Remaining bugs

## Website checks using validation tools

## Deployment

## Credits
