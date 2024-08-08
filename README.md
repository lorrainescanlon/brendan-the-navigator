# Brendan the Navigator
Brendan the Navigator is a site that hopes to introduce people to the man behind Saint Brendan, the fearless adventurer with a love for the travelling on the sea.
To bring this figure and his lengendary voyage into the mainstream and make him appealing to all and not just people of faith. 

![Wireframe](docs/wireframes/brendanwireframes.pdf)
![Responsive Design](docs/images/responsivevoyage.PNG)

## Features 
I included the following features on my website.
### Existing Features
- __Navigation Bar__
  - Featured on all three pages, the full responsive navigation bar includes links to the Home page, Voyage and Contact page. It is identical on each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
![Nav Bar](docs/images/navbar.PNG)
- __The landing page image__
  - The landing page includes a photograph with text overlay to allow the user to see exactly what this site is about. 
  - This section introduces the user to Brendan the Navigator with an image of his statue which stands at Fenit harbour in Kerry to set the scene.
  - This section includes a responsive timeline of the history of Brendan the Navigator.
![Landing Page](docs/images/landingimage.PNG)
- __The Voyage__
  - The voyage section details Brendans famous seven year voyage, pictures are used to support the content. 
  - This should encourage the user to want to learn more about Brendan and his famous voyage. Links are provided to external sites where the user can find more information.
![Voyage Page](docs/images/voyage.PNG)
- __Contact Page__
  - This page will allow the user to contact the page with any queries. The user will be asked to submit their full name and email address.
  - The user will also have the opportunity to provide feedback in the form of a vote button. They can give their opinion on whether Brendan reached America or not.
![Contact](docs/images/form.PNG)
- __The Footer__ 
  - The footer section includes links to the relevant social media sites for Brendan the Navigator. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.
![Footer](docs/images/footer.PNG)

### Features Left to Implement
- As a future add on, a feature that would display the results on the vote button would be beneficial. Shown as a graphic to illustrate what percentage of users believe Brendan reached America versus the percentage that believe he didn't.
## Testing
- This page has been tested on different browsers such as chrome, firefox and samsung internet browser.
- Responsiveness and functionality have been tested on all screen sizes using the dev tools device toolbar.
- All links have been tested.
- I have tested the contact form validation for text and email input fields. 
- The submit button also posts the data to the code institute server. 
- I used lighthouse to test the websites performance and .. 

## Bugs Encountered
- When I first deployed the website to GitHub, I discovered that the social media links didn't work. 
  This was due to not enclosing the icons within the anchor opening and closing tags.
- I also discovered that my radio buttons didn't behave as expected. 
  This was due to me assigning unique ids to the buttons, I resolved this by giving them both the same id.
- I encountered problems when applying the media query to change the layout of the timeline for larger screens. The timeline ruler and containers were displaying correctly, the problem was that 
  the exisiting circles for some containers were not being re organised so I had duplicate circles. With some assistance from tutor support I added a line of code left;auto to set the offending items to default.

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.

Initial testing once main structure was in place on both HTML and CSS validators. Errors reported and resolved before moving on to resposive design developement.
### Validator Testing 
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)
### Unfixed Bugs
You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 
No h2 - h6 elements used in section returned a warning. 
## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 
- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
The live link can be found here - https://lorrainescanlon.github.io/brendan-the-navigator/
## Credits 
In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
You can break the credits section up into Content and Media, depending on what you have included in your project.
### Content 
- I used Wikipedia https://en.wikipedia.org/wiki/Brendan_the_Navigator as a content source.
- I used Dingle-Peninsula https://dingle-peninsula.ie/stories-2/49-blog-from-the-dingle-peninsula/251-st-brendan-the-navigator-s-departure-from-brandon-creek.html as a content source.
- I used Irish Culture and Customs https://www.irishcultureandcustoms.com/ASaints/BrendanNav.html as a content source.

### Media
- The Statue and Brandon Creek images are my own.
- The Sea image used is from Unsplash by Ulrike Donohue.
- The Puffin image used is from Pixabay by Frank Liebmann.
- The Volcano image used is from Pixabay by Julius H.
- The Iceberg image used is from Pixabay by Lurens.
- The Ship image used is from Pixabay by the user dp1616.
- The compass favicon was taken from https://favicon.io/.com
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
### Code
 - I researched how to implement the timeline on W3Schools. I used the instructions at the following link as a basis for this feature https://www.w3schools.com/howto/howto_css_timeline.asp This code creates a split timeline that then reconfigures to become a single sided timeline. I was using the revserse approach as I developed the mobile site first and then added media queries to split the timeline for larger screens so I chopped and changed the code quiet a bit to get the effect I was looking for.

