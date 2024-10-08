# Safeguarding Project

## This project aims to display easy-to-understand information on safeguarding practices, including how to recognise and respond to safeguarding concerns.

To do this it will include:
* A Hero Section: A Jumbotron with a brief statement about the importance of safeguarding, using a bold heading and a relevant image.

* Key Information Sections: Using Bootstrap’s grid system to divide the page into sections like “What is Safeguarding?”, “Signs to Watch For,” and “Action Steps.”

* Bullet Points for Action Steps: Presenting the safeguarding steps as a list using Bootstrap’s list group or standard bullet points, ensuring clarity.

* A Contact Section: Include a simple contact form or a list of important contacts, styled with Bootstrap’s form components, for reporting safeguarding concerns.

## Target Audience: Code Institute members
This project will benefit Code Institute (CI) members by presenting them with easy access to a 'one stop shop' for safeguarding information. This information will be presented concisely, with CI members valued time in mind and hopefully be aesthetically pleasing. Help channels will be clearly displayed both internally to the company and externally to government websites, as those seeking information may typically be considering reporting an issue and look for further councelling.

## User Stories
### User Story 1:
As a user, I want to see a section displaying contact information so that I know who to reach out to and how to contact them..
### Acceptance Criteria:
* The section must clearly display the name, role (e.g., counselor, support staff), and contact details (phone number, email) for each relevant contact person.
* Each contact detail should be clickable:
Email addresses should be clickable, opening the user's default email client (using mailto:).
Phone numbers should be clickable, enabling dialing on mobile devices (using tel:).
* The section should have a clean layout, using Bootstrap's grid system to ensure information is presented clearly and responsively on all screen sizes (mobile, tablet, desktop).
* Each contact should be visually distinguishable, using clear labels or icons (e.g., an envelope icon for email, a phone icon for phone numbers).
* The section should provide clear, accessible styling (e.g., font size, colors) to ensure readability for all users, adhering to web accessibility guidelines (WCAG).
* Optionally, the section may include office hours or availability for each contact person, if applicable.
* The section should feature a title (e.g., "Contacts") to ensure users understand the purpose of the section at a glance.

### User Story 2:
As a user I wish to be able to report an issue I am concerned about at home or within the CI community, anonymously.
### Acceptance Criteria:
* The form should allow users to report an issue without requiring any personal information (e.g., name, email, etc.)
* The form should contain a "Feedback" text area that is required before submission.
* The "Submit Anonymously" button should be enabled only after the required feedback field is filled.
* Upon clicking the "Submit Anonymously" button, the form data should be successfully submitted without collecting any identifiable user information.
* The form should not require any user authentication or login.
* After successful submission, the user should receive a confirmation message (e.g., "Thank you for your feedback").
* The form must be responsive and display correctly on various screen sizes (mobile, tablet, desktop) using Bootstrap's grid system.
* The form must not store or log IP addresses or any other potentially identifying information in the backend.

### User Story 3:
As a user, I would like to be able to find information on safeguarding practices.
### Acceptance Criteria:
* The page or section must clearly display detailed information about safeguarding practices, including policies, procedures, and responsibilities.
* The information should be organised under relevant headings for easy navigation.
* The section must be mobile-responsive, ensuring the content is readable and well-organised on all screen sizes using Bootstrap's grid system.
* The safeguarding information should be presented in clear, plain language to ensure that users of all backgrounds can easily understand it.
* Key safeguarding documents (e.g., policies, guidelines) must be clearly linked.
* The information must adhere to accessibility guidelines (e.g., contrast, font size, readable formats) to ensure users with disabilities can access the content.
* The page should be easy to find, linked from the homepage or in a dedicated menu, with clear labels.

## Design Decisions
### Wireframes
### The landing page
![Wireframe](https://share.balsamiq.com/c/brVwrak8UdtKB7FS1V6JU3.png)
---
The landing page will feature a hero that includes a title, a nav bar (which will be fixed), a home button (which will navigate the user to the top of the page). Underneath, there will be important contacts available to scroll through. Pressing on one of these contacts will navigate the user to their section on the website. This is to make it quick and easy for the user to get in contact with a professional.

### Information sections
![Wireframe](https://share.balsamiq.com/c/rdv2FqpTkb7Hh9C5cf9Tnm.png)
---
There will be three information sections dedicated to:
* What is safeguarding?
* Signs to watch for
* Action steps

These will take up the length of the page for an enhanced user experience.

### Contact Section
![Wireframe](https://share.balsamiq.com/c/usBE5eqzy9H56tB9Kb3TVh.png)
---
Like the information section, these contacts will each take up the entirety of the screen.

### Anonymous reporting
![Wireframe](https://share.balsamiq.com/c/jZz77EkeHVC5JfmbDXR9jz.png)
---
A section dedicated to anonymous reporting of potential issues to the CI safeguarding team.



## Colour Palette
![palette](Assets/Images/AdobeColor-My%20Color%20Theme.jpeg)
---
For a clean, minimal design, following a familiar structure seen on the code institute website, I'll use **Soft White (#F8F9FA)** as the main background colour. I'll highlight important elements like buttons and calls to action with **Bright Orange (#FF6F3C)**. To keep things warm but subtle, I'll use **Soft Peach (#FFA552)** for section backgrounds or navigation menus. For readability, I'll ensure the body text is in **Dark Charcoal (#333333)** and use **Deep Burnt Orange (#D35400)** for headings or key information. Finally, I'll add **Light Warm Grey (#E5E5E5)** for borders and dividing lines to subtly separate content areas.

## Typography

* Montserrat for headings, owing to its modern and professional look that is slightly bolder and eye-catching.
* Roboto for the body: clean and professional looking.

### Final Look

![Screenshot](Assets/Images/Screenshot%202024-10-02%20at%2009.33.49.png)

## Accessibility Considerations

### Colour Contrast:
Use of colours with strong contrast to make text easy to read. For example, **Dark Charcoal (#333333)** text on **White (#FFFFFF)** or **Soft White (#F8F9FA)** backgrounds provides clear contrast, meeting accessibility standards. Buttons in **Bright Orange (#FF6F3C)** also stand out clearly against light backgrounds, ensuring visibility for all users.

### Alt Text for Images:
All images include descriptive alt text to help screen readers convey the content. Decorative images have empty alt tags (alt="") to avoid distracting screen reader users.

### Aria-label for Icons:
All icons include descriptive aria-labels to help screen readers convey the content.

### Other Accessibility Measures:
Font sizes are large enough to read, and line spacing ensures easy readability.

# AI Usage

Script taken from OpenAI to close navigation menu on screens of 768px and smaller once menu option has been selected.

# Features Implementation

## Feature: Contact cards

Whilst the initial design featured an image carousel for important contacts, the current card feature was a more practical element to include, proving to be a time saver. 

Most acceptance criteria has been met, excluding additional contact links, which are not available.

![image](Assets/Images/ContactSS.png)

## Feature: Inforamtion Section

Meeting the acceptance criteria, this section offers easy to understand information surrounding safeguarding.

The text was given a line-height of 2 and a font family of #333 against a white background to make it clear for users. 
 
Links have been provided below each paragraph, so that users can verify the sources.

Action steps were built using bootstraps list component.

![image](Assets/Images/informationSec.png)

![image](Assets/Images/Actionsteps.png)

## Feature: Anonymous Reporting

Built using bootstraps form components, this is a simple form for users to raise any concerns anonymously. The feedback field is required before submission.

![image](Assets/Images/anonR.png)

# Testing and Validation

* Testing was conducted across various devices and screen sizes, including mobile phones, tablets, and desktops.
* Chrome DevTools was used to simulate different device environments.
## Issues Found:
* Mobile responsiveness: Some elements were misaligned on smaller screens, which was fixed by adjusting media queries.
* Mobile responsiveness: navigation menu would take up entire screen and not leave when location on page navigated to. Use of ChatGPT to create script that would hide the nav menu once location reached.

## The HTML and CSS were validated using the W3C Markup Validator and the Jigsaw CSS Validator.
### Results:
* HTML: There are many errors, of which, are mostly referring to imported bootstrap code-which works. So, I am apprehensive to alter.
* CSS: No issues detected.

# Deployment Process

## The project was deployed to GitHub Pages following these steps:

* Pushed the MVP to the main branch of the GitHub repository.
* Navigated to the repository's Settings > Pages section.
* Selected the branch to deploy from (e.g., main) and the root directory for deployment.
* After saving the settings, the website was deployed automatically.

### Challenges Encountered:

* CSS not loading: The issue was resolved by ensuring the correct file paths were used, relative to the repository structure.

