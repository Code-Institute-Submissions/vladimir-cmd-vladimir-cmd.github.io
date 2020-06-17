# Delicious Food

Delicious food is a place where one can read about world's best cusisines.
Site goal is to make it easier for others when it comes to food making or recipe seaching.
Visitor should be able to browse the recipes without registering.

# <p align="center">[Delicious Food Web Site Link](https://vladimir-cmd.github.io/index.html "Delicious Food Homepage")</p>
 
## User Experience

### Plan

Delicious food website is the best place to be if you are a food lover, or someone who loves making food for self and the others.
It is simple and clean website, easy to navigate between pages. On home page there is a short representation of world's best cuisines, and you can go and read more about them with just a click of a button.
This website is for either a person who had never cooked in their live, just starting with food making, or for an experienced cooker who would like to broaden its experience.

### User Stories

Reason why creating this website:

* be a place where visitor will come to look for delicious recepies
* be a place where visitor will be able to find out more about famous cuisines
* be a place where visitor can subscribe for a newsletter, to be up to date with latest recepies
* be a place where visitor can check for the top 5 monthly recepies
* be a place where visitor can check the photos of various types of food
* be a place where visitor can create lists of its favorite recepies

## Wireframes
I used [AdobeXD](https://www.adobe.com/ie/products/xd.html) to create
[wireframes](https://github.com/vladimir-cmd/vladimir-cmd.github.io/tree/master/wireframes) in desktop, tablet and phone view.

## Features

### Page Features:
* [Home](https://vladimir-cmd.github.io/index.html)
   - This page starts with a header, with a hero image coming right after.
   - Home page contains section with reasons why you should eat healthy. 
   - Contains section with list of Cuisines with a "read more" button. 
   - Contains a table of top 5 favorite recipes of the month.
   - At the bottom of the page is a neat row of social links consisting of Facebook, Twitter, Instagram and Youtube.

* [Gallery](https://vladimir-cmd.github.io/gallery.html)
   - Gallery page contains images of delicious food.
   - This page starts with a header.
   - For a Desktop resolution, there are three columns.
   - Images are a bit enlarged when you hover over it.
   - Each image has a title and a small description.
   - Newsletter subsection follows, where visitor can subscribe.
   - At the bottom of the page is a neat row of social links consisting of Facebook, Twitter, Instagram and Youtube.

* [Contact](https://vladimir-cmd.github.io/contact_me.html)
   - Contact page contains an email form which visitor can fill out and send.
   - This page starts with a header, with a hero image coming right after.
   - Over the hero image there is a contact form box.
   - The required fields are clearly indicated, with a possible notification in case a visitor doesn't fill all the required fields successfully.
   - Newsletter subsection follows, where visitor can subscribe.
   - At the bottom of the page is a neat row of social links consisting of Facebook, Twitter, Instagram and Youtube.

* **Cusisine**:
   - Each Cuisine has its own dedicated page. The list of Cuisines:
      - [Italian Cuisine](https://vladimir-cmd.github.io/Italian.html)
      - [Chinese Cuisine](https://vladimir-cmd.github.io/Chinese.html)
      - [Mexican Cuisine](https://vladimir-cmd.github.io/Mexican.html)
      - [Serbian Cuisine](https://vladimir-cmd.github.io/Serbian.html)
      - [Turkish Cuisine](https://vladimir-cmd.github.io/Turkish.html)
      - [Thai Cuisine](https://vladimir-cmd.github.io/Thai.html)
   - This page starts with a header.
   - Each page contains description of selected cuisine.
   - Each page contains 4 recipes each.
   - Recipes are sorted in two columns for Desktop Resolution, and one column for Mobile resolution.
   - Newsletter subsection follows, where visitor can subscribe.
   - At the bottom of the page is a neat row of social links consisting of Facebook, Twitter, Instagram and Youtube.

### All Page Features:
* **Semantic HTML**: All pages have been written with semantic HTML in mind.
* **Fixed Header**: Each page has a fixed header, for ease of navigation.
* **Responsive Design**: Site pages are designed to work on all sizes of device.
 
### Specific Features:
* **Subscribe to Newsletter**: Every page includes subscribe to newsletter section where visitor can subscribe for the latest recepies.
* **Top 5 best recepies**: Home page includes top 5 monthly recepies section.
* **Read More**: Front page contains Read More button for each Cusine for ease of navigation.

## Technologies Used

In this project the following technologies have been used.

- [HTML](https://en.wikipedia.org/wiki/HTML) 
   - Semantic markup language as the shell of the site.

- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
   - Cascading Style Sheets as the design of the site.

- [Google Fonts](https://fonts.google.com/)
   - Google's font catalog places typography front and center, inviting users to explore, sort, and test fonts for use in more than 135 languages.

- [FontAwesome](https://fontawesome.com/)
   - **FontAwesome** provided the icons used on the page.

- [Bootstrap 4](https://getbootstrap.com/)
   - To be easily responsive, navbar, the list groups, card decks and forms were used to give a clean, simple and ordered look. I wanted to re-inforce what I had learnt from the UCFD module.

- [Gitpod](https://gitpod.io/) 
  - IDE (Integrated Development Environment).

- [GitHub](github.com/) 
  - The remote hosting platform. 

- [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) 
  - To see visually the elements of what each code produced, what happens if code is changed, and responsiveness of different device sizes.

- [Jigsaw](https://jigsaw.w3.org/css-validator) 
  - To check for any errors in the CSS code.

- [W3C Markup Validator](https://validator.w3.org/) 
  - To check for any errors in HTML code.

# Testing 
Testing information is found on a separate file [TESTING.md](TESTING.md)

## Deployment

Creation of website

This website is deployed using GitHub pages.

**GitHub pages** was used to deploy this site.
    - Go to repository master branch ([Source](https://github.com/vladimir-cmd/vladimir-cmd.github.io))
    - Press Settings button on right.
    - Scroll down to Github Pages section.
    - There will be link to website
Note: there is only a master branch. No other branches were created.

To run the copy of website, there are two options:

1. Sign to your GitHub account
2. search for the following repository: https://github.com/vladimir-cmd/vladimir-cmd.github.io
3. In the upper right corner click on "Fork" button
4. You have successfully duplicated my website to your GitHub account

OR

Important: must have git CLI installed on local machine
1. Sign to your GitHub account
2. search for the following repository: https://github.com/vladimir-cmd/vladimir-cmd.github.io
3. Click on "Clone or download" button and copy the path
4. Open Command Line interface (Windows - Powershell or Linux\MacOS - Terminal)
5. git clone https://github.com/vladimir-cmd/vladimir-cmd.github.io.git
6. You have successfully clonned repository on your local machine
Note: You would require a web server to run the site from your local machine.
As a workaround, you can use repl.it

You can open the site in repl.it
1. Sign to your GitHub account
2. search for the following repository: https://github.com/vladimir-cmd/vladimir-cmd.github.io
3. Click on "Clone or download" button and copy the path
4. Open repl.it
5. Navigate to myrepls
6. In the upper right corner click on "new repl"
7. In a new window, select "Import From GitHub"
8. Paste the link you copied in step 3

## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
