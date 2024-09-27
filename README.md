# Safeguarding Project

## This project aims to display easy-to-understand information on safeguarding practices, including how to recognise and respond to safeguarding concerns.

To do this it will include:
* A Hero Section: A Jumbotron with a brief statement about the importance of safeguarding, using a bold heading and a relevant image.

* Key Information Sections: Using Bootstrap’s grid system to divide the page into sections like “What is Safeguarding?”, “Signs to Watch For,” and “Action Steps.”

* Bullet Points for Action Steps: Presenting the safeguarding steps as a list using Bootstrap’s list group or standard bullet points, ensuring clarity.

* A Contact Section: Include a simple contact form or a list of important contacts, styled with Bootstrap’s form components, for reporting safeguarding concerns.

## Target Audience: Code Institute members
This project will benefit Code Institute (CI) members by presenting them with easy access to a 'one stop shop' for safeguarding information. This information will be presented concisely, with CI members valued time in mind and hopefully be aesthetically pleasing. Help channels will be clearly displayed both internally to the company and externally to government websites, as those seeking information may typically be considering reporting an issue and look for further councelling.

## User Stories:
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
* The section should feature a title (e.g., "Important Contacts") to ensure users understand the purpose of the section at a glance.

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
* No validation errors should occur if the feedback is the only field filled out.
* The form must not store or log IP addresses or any other potentially identifying information in the backend.

### User Story 3:
As a user, I would like to be able to find information on safeguarding practices.
### Acceptance Criteria:
* The page or section must clearly display detailed information about safeguarding practices, including policies, procedures, and responsibilities.
* The information should be organised under relevant headings (e.g., "Child Protection," "Reporting Concerns," "Staff Responsibilities") for easy navigation.
* The section must be mobile-responsive, ensuring the content is readable and well-organised on all screen sizes using Bootstrap's grid system.
* The safeguarding information should be presented in clear, plain language to ensure that users of all backgrounds can easily understand it.
* Key safeguarding documents (e.g., policies, guidelines) should be available for download in common formats (e.g., PDF) and must be clearly linked.
* The information must adhere to accessibility guidelines (e.g., contrast, font size, readable formats) to ensure users with disabilities can access the content.
* The page should be easy to find, linked from the homepage or in a dedicated menu, with clear labels (e.g., "Safeguarding Practices" or "Safety Information").

## Design Decisions
### Wireframes
![Wireframe](https://share.balsamiq.com/c/brVwrak8UdtKB7FS1V6JU3.png)