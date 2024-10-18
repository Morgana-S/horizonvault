# Testing & Bugs
## Compatibility
- Each page of the deployed project was opened on a variety of platforms:
    - Desktop PC (Microsoft Edge, Firefox, Google Chrome)
    - Mobile
    - Chrome DevTools Tablet Mode (simulating an iPad Pro)

![Testing - Desktop PC - Microsoft Edge](/assets/documentation/testing%20images/testing-homepage-edge.png)

![Testing - Desktop PC - Mozilla Firefox](/assets/documentation/testing%20images/testing-homepage-firefox.png)

![Testing - Desktop PC - Google Chrome](/assets/documentation/testing%20images/testing-homepage-chrome.png)

![Testing - Mobile](/assets/documentation/testing%20images/testing-homepage-mobile.png)

![Testing - Chrome DevTools - iPad Pro Simulation](/assets/documentation/testing%20images/testing-devtools-ipad.png)

## Features Testing
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

## Bugs
- While testing the Contact Us form, validation was not being performed for the "Full Name" and "Reason for Contact" fields. 
    - This is caused by the HTML input for these fields not having the "required" attribute.
    - This has now been fixed by adding the "required" attribute for both input elements. This has not been added to the "email" input as this self-validates by checking for an email address.

## Responsiveness
All pages are responsive in design and designed with a mobile-first design principle. Of particular note are the following features:
- Mobile:
    - The Nav Bar is a drop down menu on vertical mobile screens to allow for better use of screen real-estate.
    - On the Starter Quests page, the quest tables are not visible on a vertical mobile due to their size. There is a warning that advises users to rotate their phone or access the site on a larger screen (such as a tablet or laptop) to see the tables.
- All pages use CSS Flexbox to ensure that page responsiveness is achieved.

### Responsiveness Screenshot GIFs

#### Home Page
![Home Page - Responsiveness GIF](/assets/documentation/testing%20images/testing-home-page-responsiveness.gif)

#### Starter Quests Page
![Starter Quests Page - Responsiveness GIF](/assets/documentation/testing%20images/testing-starter-page-responsiveness.gif)

#### Beginner Tips Page
![Beginner Tips Page - Responsiveness GIF](/assets/documentation/testing%20images/testing-beginner-tips-page-responsiveness.gif)

#### Contact Us Page
![Contact Us Page - Responsiveness GIF](/assets/documentation/testing%20images/testing-contact-us-page-responsiveness.gif)

# Validation
Each page was validated on the W3C HTML Validator and W3C Jigsaw CSS Validator, as shown below:

## Home Page

