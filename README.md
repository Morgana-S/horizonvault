# HorizonVault - A FFXI Knowledge Repository

![Showcase of responsiveness of webpages](/documentation/feature-images/responsive-design-showcase.png)

## About
HorizonVault is a repository of basic knowledge designed for both new and experienced players of the popular private server for Final Fantasy 11, HorizonXI. The purpose of the website is to collate and display static data about the game in an easily accessible, readable format, as well as providing a place to view video examples of ingame practices that new players may find difficult or confusing.

The deployed version can be accessed on GitHub Pages [here.](https://morgana-s.github.io/horizonvault/index.html)

## UX Design

The design of the website was created so that users:

- Could navigate to labelled pages with the specific type of information they need
- Could navigate the website in a way that was clear and consistent across all pages
- Could find the information they were looking for in a readable and accessible format

## Target Audience

- New players for HorizonXI, looking to find out more about the game.
- More experienced players of HorizonXI, looking for a source of information to share with newer players.

## User Stories

**First time visitors:**

- As a first time visitor, I want to be able to navigate the site using a navbar that's easy to use.
- As a first time visitor, I want to be able to clearly understand the purpose of the site.
- As a first time visitor, I want guidance on which information might be immediately useful to me.
- As a first time visitor, I want content to be displayed in a readable format that isn't too intimidating to read.
- As a first time visitor, I want to be see consistent design between pages so I can recognize the key features easily.

**Frequent visitors:**

- As a frequent visitor, I want to be able to find information on quests that are useful to new players.
- As a frequent visitor, I want to see information that will be useful to new players just starting out.
- As a frequent visitor, I would like to see videos that show information in a way that is consistent and easy to understand.

## Features

**Please Note:** Some of the features displayed in the below screenshots may not reflect the current state of the site due to changes in formatting. Features are still accurate to the original version of the site.

### Navigation Bar
- Navigation Bar with fixed position at the top of the page.
- Contains links to the following site pages:
    - Horizon Logo; clicking logo takes to the index page as is standard practice on many websites;
    - Home - takes to the index page with clearer navigation;
    - Starter Quests - goes to the Starter Quests Page;
    - Beginner Tips - goes to the Beginner Tips Page;
    - Contact Us - goes to the Contact us form page.
- Responsive design - on small screens like vertical mobiles, a menu icon appears and the links become drop-down when clicked.
- Animated hover effect on tablet screens and larger (though the effect is only visible when hovered over with a mouse).
- A class has been used to designated the active page on the Nav Bar by underlining the page link, allowing users to understand where they are on the website at a glance.

![Desktop Version of the Nav Bar](/documentation/feature-images/navbar-tablets-larger.png)

![Mobile Version of the Nav Bar](/documentation/feature-images/navbar-mobile.png)

![GIF of the website logo hover effect](/documentation/feature-images/hv-logo-hover.gif)

![Gif of the Nav Bar hover effect](/documentation/feature-images/navbar-hover.gif)
---
### Hero Image
- Website users are drawn in with a hero image featuring art of the game.
- This image has a heading and subheading overlaid to welcome users to the site.
- The hero image is responsive, and different parts of the hero image are focused on based on the viewing platform to entice users in.

![Hero Image - Mobile Version](/documentation/feature-images/hero-image-mobile.png)

![Hero Image - Desktop Version](/documentation/feature-images/hero-image-desktop.png)
---
### Footer
- Footer is present on all pages, and contains labelled icons with links to websites that are relevant to the game.
- The websites linked to are:
    - The HorizonXI Website;
    - The HorizonXI Discord Server;
    - The HorizonXi Wiki;
    - The project's GitHub page.
- All of the above links open in a new window, as is standard practice for external sites.
- Footer is responsive and easily navigable on both small and larger screens..
- Hover Effect on Footer links to demonstrate interactivity.

![Footer - Mobile Version](/documentation/feature-images/footer-mobile.png)

![Footer - Desktop Version](/documentation/feature-images/footer-desktop.png)

![Footer - Hover Effect GIF](/documentation/feature-images/footer-hover.gif)
---
### Home Page
- The Homepage acts as enticement and a brief introduction to the website.
- It provides information on what the website is for, as well as a little information on the HorizonXI server.

![Home Page - Mobile Version - Hero Image](/documentation/feature-images/homepage-mobile-1.png)
![Home Page - Mobile Version - Part Two](/documentation/feature-images/homepage-mobile-2.png)

![Home Page - Desktop Version](/documentation/feature-images/homepage-desktop.png)
---
### Starter Quests Page
- The Starter Quests Page provides data on quests available to newer players of the game.
- This information is arranged in a table format, with info on things that would be of interest to users, such where to start the quest, rewards, and useful notes about the quests.
- The page has the option to select from quests in a particular city by selecting the image of the city's icon, which takes the user to the appropriate part of the page.
- On vertical mobile devices, the tables are too bulky to display in a reasonable fashion. A warning message exists for vertical mobile users to either rotate their phone horizontally or view the table on a tablet or laptop screen.
- Each of the external links, as with the rest of the site, has an ARIA Label to ensure accessibiity and ease of use for people who use screen readers to browse the site.

![Starter Quests - Mobile Version](/documentation/feature-images/starter-quests-mobile.png)

![Starter Quests - Desktop Version](/documentation/feature-images/starter-quests-desktop.png)

![Starter Quests - Navigation to Different Sections](/documentation/feature-images/starter-quests-in-page-navigation.png)
---
### Beginner Tips Page
- The Beginner Tips Page provides helpful advice to new players of the game.
- The page's design is simple and is focused on scalability while maintaining an interesting format.
- I have used alternating CSS classes to create 'cards' where the tips can be placed within. By alternating these cards, it keeps the page's structure interesting.
- The cards are also responsive and adjust their size on mobile devices.

![Beginner Tips - Mobile Version](/documentation/feature-images/beginner-tips-mobile.png)

![Beginner Tips - Desktop Version](/documentation/feature-images/beginner-tips-desktop.png)
---
### Contact Us Page
- The Contact Us page contains a form where the user can provide their contact information and a brief message about their query.
- The page also contains a direct link to the project's GitHub Issues page, so that users can submit issues they have with the site, should they find any.
- The form contains fields for the user's full name, email address, and reason for contact.
    - The input and textarea fields validate for an input with a required html attribute.
    - The Email Address field validates for whether the user has included a correctly formated email address, i.e. it checks for an @ symbol in the text entry field.
    - A textarea field with matching size to the input fields indicates to users that they can write a longer message in the field. The field is also resizeable vertically.

![Contact Us - Mobile Version](/documentation/feature-images/contact-us-mobile.png)

![Contact Us - Desktop Version](/documentation/feature-images/contact-us-desktop.png)
---
### Form Submitted Page
- The Form Submitted Page is reached by submitting the form on the Contact Us page above.
- The page confirms that the form was submitted and allows users to go back to the website's homepage.

![Form Submitted - Mobile Version](/documentation/feature-images/form-submitted-mobile.png)

![Form Submitted - Desktop Version](/documentation/feature-images/form-submitted-desktop.png)

## Testing & Bugs
- For Testing and Bugs, please view the [TESTING.md](/TESTING.md) file.

## Validation & Accessibility
- For information on each page's Validation & Accessibility features, please the the [TESTING.md](/TESTING.md) file.

## Tools
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - Page structure and content.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Page appearance and styling rules.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Used to add responsiveness to pages.
- [Visual Studio Code](https://code.visualstudio.com/) - IDE used for project development.
- [Git](https://git-scm.com/) - Version control.
- [Github Desktop](https://desktop.github.com/download/) - Additional version control.
- [Github](https://github.com/) - Project Hosting.
- [Github Pages](https://pages.github.com/) - Project Deployment.
- [Licecap](https://www.cockos.com/licecap/) - Screen recording GIFs for responsiveness demonstration testing.

## Deployment
### Deployment to GitHub Pages

- The page was deployed in the early stages to GitHub pages. The steps to deploy are as follows:
    1. In the GitHub [Repository](https://github.com/Morgana-S/horizonvault), click the settings option at the top of the page.
    2. Under 'Code and Automation' on the left side, click 'Pages'.
    3. Under 'Build and Deployment' > 'Source', choose 'Deploy from a Branch'. The chosen branch to deploy should be 'Main'. Save these settings.
    4. Back under the code section at te top of the page, view the deployments on the right hand side, and select the 'Github-Pages' Deployment.

### Local Deployment
- In order to make a local copy of this project, it can be cloned. In your IDE terminal, type the command below to clone this repository:
    - ``` git clone https://github.com/Morgana-S/horizonvault.git ```


## Credits

### Content
- [Love Running Project](https://github.com/Morgana-S/love-running) - code for the dropdown menu for mobile users.
- [Real Favicon Generator](https://realfavicongenerator.net/) - Import and assistance with generating favicon

### Media
- [Final Fantasy 11](http://www.playonline.com/ff11us/topics/special/200803_qLjWx/imgs/thevoraciousresurgence_l.jpg) - Hero image used on home page.
- [Google Fonts](https://fonts.google.com/) - Importing of Fonts used within the project (Bebas Neue & Titillium Web)
- [Font Awesome](https://fontawesome.com/) - Icons and Script for use of Icons within project
- [HorizonXI](https://horizonxi.com/) - Use of their logo for a link to their website in the footer, use of the mandragora art on their [Partner Program Page](https://horizonxi.com/partner-program).
- [Final Fantasy 11 Wiki](https://ffxiclopedia.fandom.com/wiki/Main_Page) - use of icons for the cities on the Starter Quest Page.
- [Discord](https://discord.com/) - Logo for the Discord link in the footer.