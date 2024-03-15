# Ace Dog Walks

Ace Dog Walks is a website for people wanting to find out more about the dog walking options offered by Ace Dog Walks, the cost of these walks and contact Hannah to book a walk or find out more.

The Ace Dog Walks site aims to help dog owners to feel reassured that their pet will be well looked after, that they will have a fun and energetic walk and that they are going to get value for money.

![Multi-device mockup showing responsiveness](docs/readme-images/multi-mockup.png)

## Features

### Site Wide

***Favicon***
- A favicon of the letter 'A' from the Ace Dog Walks header logo so it is easily identifiable among multiple tabs.

![Screenshot of favicon image on a tab](docs/readme-images/favicon.png)

***Navigation Menu***
- Makes it easy for the user to move around the site and find relevant information.
- Includes links to each page of the site (Home, Gallery and Contact). 
- Responsive design to work across devices of different sizes (uses less space and reduced logo with burger icon on smaller devices).

![Screenshot of navigation menu on Galaxy Fold](docs/readme-images/nav-menu-smallest.png)
![Screenshot of navigation menu on tablet and up](docs/readme-images/nav-menu-larger.png)


***Footer***

- Contains links to the Ace Dog Walks social media profiles so they can follow or find further information.
- These links open in a new tab and include accessibillity conventions such as aria labels.

![Screenshot of footer on Galaxy Fold](docs/readme-images/footer-smallest.png)
![Screenshot of footer on tablet and up](docs/readme-images/footer-larger.png)

### Home Page (index.html)

***Hero Image***

- Includes cover text with tagline for priorty message to users.
- Landscape image to convey happy dog on a walk in a natural outdoor setting.
- Selected image to work well with adjusted focus on different device sizes.


![Screenshot of hero image Galaxy Fold](docs/readme-images/hero-mobile.png)
![Screenshot of hero image on tablet and up](docs/readme-images/hero-tablet.png)
![Screenshot of hero image on desktop](docs/readme-images/hero-image.png)

***Intro Text***
- Short introductory paragraph to provide some general info on Ace Dog Walks and what they do.
- Key messages to highlight main aims, values and priorities of Ace Dog Walks.   

***Why Book with Ace Dog Walks***

- Short bio on Hannah Brookes and her approach to dog-walking with a photo
- Section listing the reasons that the user (dog-owner) would choose Ace Dog Walks under two subheadings dog reasons and dog-owner reasons.
- Includes images of Hannah with happy dog/s to reinforce the listed reasons to choose Ace Dog Walks.
- The aim of this section is to build trust in Hannah and reassure the dog-owner that their dog will be safe and happy. 

![Screenshot of bio and reasons on Galaxy Fold](docs/readme-images/galaxy-fold-min-design.png)
![Screenshot of bio and reasonson on tablet and up](docs/readme-images/bio-reasons-tablet.png)

### Gallery Page (gallery.html)

***Gallery***

- This image gallery includes a variety of images to create a hall of fame of dogs enjoying their Ace Dog Walks.
- Retro styling with rounded corners to complement other pages and give consistent look and feel.
- Images are arranged using responsive masory layout to ensure they look good on larger tablets and desktops. 

![Screenshot of Gallery page with responsive layout on tablet](docs/readme-images/gallery-tablet.png)

### Contact Page (contact.html)

- Provides contact details for Hannah and a form to submit an enquiry. 
- Form for dog-owners to provide personal information, details of their dog.
- Includes a variety of input types such as radio buttons and checkboxes for the dog-owner to select their preferred days / times to enable Hannah to check availability.

![Screenshot of full Contact form on desktop](docs/readme-images/contact-form.png)
![Screenshot of form on mobile](docs/readme-images/contact-form-mobile.png)

### Thank You Page (thank-you.html)

- Thank you page to let the user know that their form submission has been successful.
- Prompted by submit button in contact form (instead of CI form dump).

![Screenshot of thank you page on mobile](docs/readme-images/thank-you-mobile.png)

### 404 Error Page (404.html)

- Branded 404 error page with logo and button so the user can easily navigate back to the home page.
- Same site-wide styling as other pages to improve user experience and consistency.

![Screenshot of 404 error page](docs/readme-images/404-page-mobile.png)

### Existing Features

- Responsive hompepage with effective styling to look good on different sized devices.
- Responsive header and footer with hidden elements to improve appearance on smaller devices.
- Responsive gallery with complementary retro styling to tie in with other pages.
- Contact form with thank-you page triggered by submit.

### Additional Features to Implement
To expand on this site, there are a number of features that could be added to provide additional information and functionality:
- Submit action in contact form would send information to Hannah in email format and send a copy to the dog owner.
- Add video content to gallery page, embedding reels and other video content from socials.
- Add a walk options page with examples of walk locations on a map with further images and costings.
 
## Design

### Responsive Homepage Layout

![Mobile wireframe design of homepage](docs/readme-images/mobile-homepage-wireframe.png)
![Mobile wireframe design of homepage](docs/readme-images/tablet-homepage-wireframe.png)
![Mobile wireframe design of homepage](docs/readme-images/laptop-homepage-wireframe.png)

## Testing

### Links
Every link and hover link has been tested on each page of the site.

***Method of Testing***

Once deployed in Github, each page has been opened in turn and every link clicked on to check that the correct target was opened in a new tab.

Email links have been tested to ensure they open an email with the email address entered.

Telephone links have been tested to ensure they prompt the user to select an appropriate app to make a phone call.

***Results***

All links are fully working and open the expected link in a new tab or create a new email, or prompt the user to select a telephone application. 

### Responsiveness
Each page has been tested for responsive design on devices ranging from a minimum of 280px wide (Galaxy Fold), larger mobiles of 320, 350px and 425px and for tablets of 768px, laptops at 1024px and larger desktop screens.

***Method of Testing***

Once deployed in Github, each page has been viewed at each of the above marked out sizes within Google Developer Tools, and by clicking and dragging the screen size to the smallest and largest sizes.

To access Google Developer Tools:
- Click on Google menu (three dots in top left corner)
- Select 'More tools'
- Select '<> Developer tools'
- Opens the current page in an adaptive window where you can change size of device by clicking in different spaces in the top border above the screen preview

***Results***

All pages include responsive design and css to ensure that the layout is adapted to work on devices of all sizes. No images appear to be pixelated, squashed or stretched to fit the space and there is no overlap of elements.

### Form Inputs

***Method of Testing***

***Results***

### Validator Testing

- HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)

- CSS
    - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)

- Lighthouse Testing
    - Good scores achieved for all pages. Full screenshots available in docs folder.
![Summary of all lighthouse results](docs/readme-images/ace-dog-walks-lighthouse-scores.png)


### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 


## Deployment


This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab
  - Select Pages link in the left hand menu 
  - From the source section drop-down menu, select the Main Branch
  - Click 'Save'
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here https://sophie-thomson.github.io/ace-dog-walks/

## Credits


### Content

- Sections of html and css code for the Home Page was taken from the Code Institute Love Running walkthrough project.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home page and contact form are from This Open Source site
- The images used for the gallery page were taken from this other open source site