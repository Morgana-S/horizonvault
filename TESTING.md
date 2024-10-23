# Testing & Bugs
## Compatibility
- Each page of the deployed project was opened on a variety of platforms:
    - Desktop PC (Microsoft Edge, Firefox, Google Chrome)
    - Mobile
    - Chrome DevTools Tablet Mode (simulating an iPad Pro)

### Microsoft Edge
![Testing - Desktop PC - Microsoft Edge](/documentation/testing-images/testing-homepage-edge.png)
### Mozilla Firefox
![Testing - Desktop PC - Mozilla Firefox](/documentation/testing-images/testing-homepage-firefox.png)
### Google Chrome
![Testing - Desktop PC - Google Chrome](/documentation/testing-images/testing-homepage-chrome.png)
### Mobile Phone (Chrome Mobile Browser)
![Testing - Mobile](/documentation/testing-images/testing-homepage-mobile.png)
### DevTools iPad Pro Simulation
![Testing - Chrome DevTools - iPad Pro Simulation](/documentation/testing-images/testing-devtools-ipad.png)

## Manual Testing
- The following tests were conducted to ensure features were working as intended:
    - Nav Bar:
        - (Mobile & Desktop) Click on the Logo - redirects to the Home page;
        - (Mobile) Click on the menu icon - drop down list appears displaying Nav Bar Options;
        - (Mobile & Desktop) Click on the Home link on Nav Bar - redirects to Home page;
        - (Mobile & Desktop) Click on the Starter Quests Link on Nav Bar - redirects to Starter Quests page;
        - (Mobile & Desktop) Click on the Beginner Tips link on Nav Bar - redirects to Beginner Tips page;
        - (Mobile & Desktop) Click on the Contact Us link on Nav Bar - redirects to Contact Us page.
    - Footer:
        - (Mobile & Desktop) Click on the HorizonXI Website icon on Footer - opens a new tab to the HorizonXI Website;
        - (Mobile & Desktop) Click on the Discord icon on Footer - opens a new tab to the HorizonXI Discord server;
        - (Mobile & Desktop) Click on the HorizonXI Wiki icon on Footer - opens a new tab to the HorizonXI Wiki;
        - (Mobile & Desktop) Click on the GitHub icon on Footer - opens a new tab to the project's GitHub page.
    - Home Page:
        - Nav Bar and Footer works correctly, as detailed above.
    - Starter Quests Page:
        - Nav Bar and Footer works correctly, as detailed above.
        - (Mobile & Desktop) Click on the logos for each city - takes to the relevant section of the page for each city's quests.
        - (Mobile & Desktop) Click on the "back to top" link under each city's heading - takes back to the top of the page.
    - Beginner Tips Page:
        - Nav Bar and Footer works correctly, as detailed above.
    - Contact Us Page:
        - Nav Bar and Footer works correctly, as detailed above.
        - Form Submission does not currently work - this is outside of the scope of this project at present and as the form is not posted to a URL, this is working as intended.
        - Full Name Input was not being validated at the time of testing - please see bugs section below. This has now been rectified to validate for input.
        - Email submission field was tested by just putting random characters - confirmed that form will ask for correctly formated email address before submission is allowed.
        - Reason for Contact Input was not being validated at the time of testing - please see bugs section below. This has now been rectified to validate for input.

## Peer Reviewed Testing
- The deployed website was tested by two friends using both desktop and mobile devices. Testing methodology was followed in line with the above tests conducted.
    - Both testers found that the website was intuitive to them and easy to use. Both friends are members of the target audience for the site (i.e. people who play on the HorizonXI server).
    - Their feedback and responses to it have been marked in the section below as **[Feedback]**.

## Bugs & Feedback
- While testing the Contact Us form, validation was not being performed for the "Full Name" and "Reason for Contact" fields. 
    - Cause: HTML input for these fields not having the "required" attribute.
    - Solution: Adding the "required" attribute for both input elements. This has not been added to the "email" input as this self-validates by checking for an email address.
- While testing the Contact Us form, submitting the form would lead to a 503 Service Unavailable error on GitHub Pages.
    - Cause: Method for the form was "post", despite not having a url to post the form information to.
    - Solution: Change method to "get", create form-submitted.html to confirm form submission button working correctly.
- **[Feedback]** Content added in commit "257b11e" was too large, defying best practices for version control.
    - Acknowledged that the commit was too large with a comment left on the commit itself.
    - Will strive to increment commits in smaller, more manageable sections in future projects.
- **[Feedback]** Commit messages are too long and generally formatted in past tense rather than present tense.
    - All future commit messages to be kept to 80 characters or less where possible and commit messages to be written in present tense. (i.e. "moved x to y folder" becomes "move x to y folder") to maintain standards.
- "Starter Quest" page body was not displaying correctly, with a white space between the header and the main content. 
    - Cause: An errant text character being displayed outside of the sections of the main content.
    - Solution: Text character was removed in commit "723f7f1", fixing the issue.
- **[Feedback]** Hovering over items in the footer highlights the individual navigation list elements, but the entirety of the li is not clickable, which means that it is possible to click an area that darkens when hovering, and have the area not be interactable.
    - When designing for future projects that require a navigation bar, I will ensure that the entirety of the element's hover area is clickable for ease of use by end-users.

## Responsiveness
All pages are responsive in design and designed with a mobile-first design principle. Of particular note are the following features:
- Mobile:
    - The Nav Bar is a drop down menu on vertical mobile screens to allow for better use of screen real-estate.
    - On the Starter Quests page, the quest tables are not visible on a vertical mobile due to their size. There is a warning that advises users to rotate their phone or access the site on a larger screen (such as a tablet or laptop) to see the tables.
- All pages use CSS Flexbox to ensure that page responsiveness is achieved.

### Responsiveness Screenshot GIFs

#### Home Page
![Home Page - Responsiveness GIF](/documentation/testing-images/testing-home-page-responsiveness.gif)

#### Starter Quests Page
![Starter Quests Page - Responsiveness GIF](/documentation/testing-images/testing-starter-page-responsiveness.gif)

#### Beginner Tips Page
![Beginner Tips Page - Responsiveness GIF](/documentation/testing-images/testing-beginner-tips-page-responsiveness.gif)

#### Contact Us Page
![Contact Us Page - Responsiveness GIF](/documentation/testing-images/testing-contact-us-page-responsiveness.gif)

#### Form Submitted Page
![Form Submitted Page - Responsiveness GIF](/documentation/testing-images/testing-form-submitted-responsiveness.gif)

# Validation
Each page was validated on the W3C HTML Validator and W3C Jigsaw CSS Validator, as shown below:

## Home Page
![Home Page - W3C HTML Validation](/documentation/testing-images/validation-html-homepage.png)

## Starter Quests Page
![Starter Quests - W3C HTML Validation](/documentation/testing-images/validation-html-starterquests.png)

## Beginner Tips Page
![Beginner Tips - W3C HTML Validation](/documentation/testing-images/validation-html-beginnertips.png)

## Contact Us Page
![Contact Us - W3C HTML Validation](/documentation/testing-images/validation-html-contactus.png)

## Project CSS Validation
![W3C CSS Validation](/documentation/testing-images/validation-css.png)

# Accessibility
Accessibility for each page was tested using Lighthouse in Chrome's Dev Tools. This confirms accessibility and performance criteria for each page.

- Home Page

![Lighthouse Report - Homepage](/documentation/testing-images/accessibility-lighthouse-homepage.png)

- Starter Quests Page

![Lighthouse Report - Starter Quests](/documentation/testing-images/accessibility-lighthouse-starterquests.png)

- Beginner Tips Page

![Lighthouse Report - Beginner Tips](/documentation/testing-images/accessibility-lighthouse-beginnertips.png)

- Contact Us Page

![Lighthouse Report - Contact Us](/documentation/testing-images/accessibility-lighthouse-contactus.png)