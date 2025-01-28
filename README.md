Welcome Anastasiya McAvoy,

## Code Institute - Milestone project 1: User-Centric Frontend Development
## Anastasiya's nail salon

### About
Anastasiya’s Nail Salon is a newly opened small independent business that would benefit from online presence to increase visibility, showcase a gallery of work & various services offered. 
As well as an enquiry form for existing or new customers.  

View live website [HERE](https://anastasiya-m4c.github.io/Anastasiya-s-nail-salon/)

![image from am I responsive to demonstrate responcivmess on the site in all screen sizes](https://github.com/user-attachments/assets/07d44c09-295f-4439-a406-8313a54916b5)

## Table Of Contents:
1. [Design & Planning](#design-&-planning)
    * [User Stories](#user-stories)
    * [Wireframes](#wireframes)
    * [Typography](#typography)
    * [Colour Scheme](#colour-scheme)

2. [Features](#features)
    * [Navigation](#Navigation)
    * [Footer](#Footer)
    * [Home page](#Home-page)
    * [Other features](#Other-features)

3. [Technologies Used](#technologies-used)
4. [Testing](#testing)
5. [Bugs](#bugs)
6. [Deployment](#deployment)
7. [Credits](#credits)

### User Stories

### 1. User Story: Browse Nail Service
As a customer,
I want to browse the various nail services offered by the salon,
So that I can choose the one that best fits my needs.
Acceptance Criteria:
Users can view detailed descriptions of services (manicures, pedicures, gel nails, nail art, etc.).
Each service includes pricing, duration, and any special offers.

### 2. User Story: Contact & how to find us
As a customer,
I want to find contact details, address and parking information about the salon,
So that I can find the salon and contact the salon if I need to.
Acceptance Criteria:
Users can view a contact number & email address of the salon.
Users can be directed to a map to find the salon. 
Users can see information about parking. 

### 3. User Story: Make an enquiry or book a Nail Appointment
As a customer,
I want to make an inquiry about a service or contact the salon about booking a nail appointment.
So that I can receive a call back or an email regarding my enquiry. 
Acceptance Criteria:
Users can enter their name, email address and contact number along with a preferred method of contact. 
Users must have a free text message where they can leave a message or details of their enquiry for the salon.  
All fields must be required. 
From should have a submit button and be responsive so that is can be viewed of devices with various screen sizes. 

### 4. User Story: Gallery
As a customer,
I want to see gallery of work,
So that I can decide if I like the work and if the salon style suits my needs.
Acceptance Criteria:
A responsive gallery of images that can be viewed on devices with various screen sizes. 

### 5. User Story: Success message!
As a potential customer,
I want To receive a confirmation that my form has been submitted,
So that I know that my inquiry has been successful. 
Acceptance Criteria:
The website displays a success message with user information once the enquery form has been submitted. 

### 4. User Story: View Salon Reviews
As a potential customer,
I want to read reviews from other clients about their salon experience,
So that I can make an informed decision before booking my appointment.
Acceptance Criteria:
The website displays customer reviews and ratings for the salon.
Reviews include feedback on service quality, staff, ambiance, etc.
Users can filter reviews by service type or rating.

### 6. User Story: Sign Up for Loyalty Program
As a regular customer,
I want to sign up for a loyalty program,
So that I can earn rewards and discounts for future appointments.
Acceptance Criteria:
Users can sign up for the loyalty program.
The program tracks points or rewards based on visits or money spent.
Users can redeem loyalty rewards directly through the website when booking future services.

### Wireframes
Wireframes created using balsamic: 
WEB VIEW
![web view wireframe image 1](https://github.com/user-attachments/assets/673db412-75ae-4740-9e83-6efd3e04fac8)
![web view wireframe image 2](https://github.com/user-attachments/assets/24eda3eb-1da5-462b-b8bb-eefb9a04796f)
APP VIEW
![app view wireframe image](https://github.com/user-attachments/assets/5ecf95ab-66d0-4268-961d-23b9fd41a3ec)

### Typography
I have researched fonts that are most comonly ussed in the beauty industry and have settled on Montserrat imported from google fonts. 

### Colour Scheme
![image](https://github.com/user-attachments/assets/d9f3e43a-c592-48eb-b937-6e6dd0d53dff)
![image](https://github.com/user-attachments/assets/04a162a6-edef-4f96-8b68-f6c92828e97e)
![image](https://github.com/user-attachments/assets/8bdc41c4-6be5-4791-9b65-f84d44c34f22)
![image](https://github.com/user-attachments/assets/3c17d7f3-d5e8-4116-868c-5902b4e5d7b3)


## Features:
Explain your features on the website,(navigation, pages, links, forms.....)
### Navigation
### Footer
### Other features

## Technologies Used
### Languages Used
- HTML - To create a basic site.
- CSS - To create custom styles and make a responsive site. 
- Bootstrap - For consistent styling and imroved responsivness. 
- JavaScript - To improve the navigation bar in mobile view.

### Frameworks Libraries and Programmes Used
- Font Awesome - for icons.
- Favicon.io - to create a favicon.
- Colormind.io - to create a colour scheeme.
- Google Fonts - for custome font size that fits with the of the indusrtry.
- GitHub - to create board, host repository & deploy site.
- GitPod - to develop project and organise version control.
- Devtools - for debugging and adjusting layouts.
- Lighthouse - for testing especially performance realted issues.
- Wave evaluation tool - for any accesibility related issues.
- Chat GPT - for generating site content. 

## Testing
Important part of your README!!!
### Google's Lighthouse Performance
Screenshots of certain pages and scores (mobile and desktop)
### Browser Compatibility
Check compatability with different browsers
### Responsiveness
Screenshots of the responsivness, pick few devices (from 320px top 1200px)
### Code Validation
![image](https://github.com/user-attachments/assets/d0f7913e-89fc-4598-ae1d-bb75de418029)

### Manual Testing user stories or/and features
Test all your user stories, you an create table 
User Story |  Test | Pass
--- | --- | :---:
paste here you user story | what is visible to the user and what action they should perform | &check;
- and attach screenshot

## Bugs

*Issue*: site.manifest file error in dev tools - failed to load resource: the server responded with a status of 404 ()  
*Cause*: broken file path, needed help of a tutor to understand the error. 
*Solution*: Updated to a relative file path.  

*Issue*: Footer spacing looks odd for small screens.  
*Cause*: Sapcing issues as content is different size but padding only looks good on big screen.  
*Solution*: applying card sizes for different screens.  

- *Issue*: Button turns blue on click 
- Cause: Boostrap default styles 
- Solution: Fixed by removing btn primary

- Issue: Gallery text in the nav is not highlighted when on gallery page 
- Cause: Active class is in the worng place, copy and paste error.
- Solution: Added active class and aria cuttent to correct page. 

## Deployment
#### Creating Repository on GitHub
1. First make sure you are signed into [Github](https://github.com/) and go to the code institutes template, which can be found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
2. Then click on **use this template** and select **Create a new repository** from the drop-down. Enter the name for the repository and click **Create repository from template**.
3. Once the repository was created, I clicked the green **gitpod** button to create a workspace in gitpod so that I could write the code for the site.
  
#### Deloying on Github
The site was deployed to Github Pages using the following method:
1. Go to the Github repository.
2. Navigate to the 'settings' tab.
3. Using the 'select branch' dropdown menu, choose 'main'.
4. Click 'save'.

## Credits
### Special thanks: 
- David Bowers - for mentoring & general support and motivation and help to get brilliant ideas flowwing. 
- Marco - for support & continuous guidence.
- Kyle - supportive husband by taking on my slack to allow me the time to create this project and for not letting me give up.

### List of used resources:
This project has been hevaily influenced by code institute learning resourses and LMS content and use of boostrap systems. 
Chat GPT used for generating content for the site cards.    

### Images:
StockSnap, Pixels.com, kamboompics.com, unsplash & pixabay.  
Photo's by:
Matt Moloney, Tiko Giorgadze, Kristina Paukshtite,  Valeria Boltneva, Lisa Fotios, ttonbro studio, Adrienne Andersen, cottonbro studio, solod_sha, Brandon Richardson, Rune Enstad, Giorgio Trovato, Andreas160578, Chelson Tamares, Viktorya  Sergeeva, Andrea Mosti, Artem Podrez.

------
