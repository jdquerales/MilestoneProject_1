# Jose's Resumé

## Stream One Project: User-Centric Frontend Development - Code Institute

This project is part of my journey as a Software Developer in Code Institute. Here, you will find
a clear and organized resumé of myself. I have included my work and education history, including
my academic track record as a researcher in physics as well as my tech training in areas of data science 
and software development. You will also find link to public social networks profiles such as Google Scholar, ResearchGate and LinkedIn,
and my development projects available on GitHub. You will be able to download two different versions of my Resumé:
a full academic curriculum and a summarised one highlighting my background, experience and skills.

## Demo

A live demo can be found [here](https://jdquerales.github.io/MilestoneProject_1/).

![responsive mockups](/assets/images/responsive_screenshot.png)


## UX
 
### User stories:


#### As a recruiter:


-  I want to view the developer’s educational background, so that I can determine 
   the suitability of the candidate for the position.

![education_background](/assets/images/education_background.png)

-  I want to be able to learn about the developer technical skills, so that I can assess whether they can fit 
   within the position requirements.

![skills](/assets/images/skills.png)


-  I want to see the developer’s projects portfolio, so that I can assess his hands-on experience.

![portfolio](/assets/images/portfolio.png)


-  I want to be able to contact the developer, so that I can schedule meeting and/or interview.

![portfolio](/assets/images/contact.png)

#### As a potential collaborator:

-  I want to view the developer’s educational background, so that I can assess his field of expertise and education level.

-  I want to have access to the researcher’s full list of publications, so that I can assess his track record and leadership in the his field of research. 

-  I want to learn about the researcher’s scientific interest and current field of research, so that I can consider him as a potential collaborations in areas of common interest.

![about](/assets/images/about.png)

-  I want to learn about the researcher’s computational skills, so that I can assure the feasibility of the methods to be employed in our research.


#### As a recruiter or potential collaborator, I want to be able to download a full curriculum vitae of the developer/researcher, so that I can see more details on his achievements and career progression.

![CV1](/assets/images/CV1.png)

![CV2](/assets/images/CV2.png)



### Strategy:

The goal of this project is to get noticed among potential recruiters and scientific collaborators. 
In the design of this project, my main goal was to make it attractive by highlighting main aspects
in the different sections and adding link to external sources. 


### Scope:

## Stage 1 (current release)

As the initial stage of this project:

- I wanted to include the most important pieces of my resumé:
About Me, Education Background, Work Experience, Portfolio (including different pilars of my professional profile,
 i.e. data analytics, software development and scientific research), Summary of my Tech Skills.

- I also wanted to have a responsive design including mobile, tablet and desktop screen sizes.

- I wanted to include just a bit of animation by using JavaScript capabilities provided by Bootstrap, in particular
for the field validation in the contact form.

- I wanted to include a scroll animation by using **ScrollReveal** library.

- I wanted to improve the user experience by adding a link to another page (with a short message) when clicking "Send Message" button.

## Stage 2 (Future release)

As future capabilities:

- I would like to include more interactive features to the website by using JavaScript.
In particular, it will have and interactive showcase of my projects in the Portfolio Section, Send messages fully operational
and live chat option.

- Update projects.


### Structure:

As it can be noticed in the initial wireframes, I was initially considering to organise my website in different pages. However, 
in order to make the user experience more comfortable I decided to organise my website in a single page with different separated 
sections.

- Home Section: I have included a horizontal navegation bar fixed to the top (for desktop screen size), which collapses to
  one icon for mobile screen size. I have included my own background picture (taken in Bariloche - Patagonia, Argentina in 2014)
  providing a beautiful eye-catching initial impression of the website. I present myself, with call outs buttons for downloading CV and
  contacting me. Social media links are also included.

- The following sections are organized in a logical way as typical resumes are presented.

- About Me Section: Including personal picture, with personal details and a summary of background and main interests.

- My Tech Skills Section: Including a progress bar of my main Tech Skills (the percentages included are quite representative
  of my experience).

- My Resumé Section: Including a descending chronological showcase of my university degrees and professional experience.  

- My Portfolio Section: Divided in three main subsections, i.e. Data Science, Software Development and Research, with link to external
  websites.

- Contact Me Section: Including contact information and a contact form.  

- Footer: Divided in three columns, i.e. brief summary of my profile, social links and download CV options. 


### Skeleton:

I used Balsamiq to create my initial wireframes, starting with the Desktop design as an overall idea and helping me to make the design responsive afterwards.

[Home wireframe](/assets/wireframes/Home.png)

[About wireframe](/assets/wireframes/About.png)

[Education History wireframe](/assets/wireframes/Education.png)

[Skills wireframe](/assets/wireframes/Skills.png)

[Work Experience wireframe](/assets/wireframes/Work_Experience.png)

[Portfolio wireframe](/assets/wireframes/Portfolio.png)

[Contact form wireframe](/assets/wireframes/Home.png)

### Surface:

- The CSS Family Blue Color Scheme was chosen for backgrounds, in order to make compatible with color in Home page background
picture.

- The CSS Family Orange Color Scheme was chosen for progress bars, social links and hoover effects on the desktop navegation bar.

- The CSS Family White Color Scheme was chosen for text on Home and Footer pages.

- The CSS Family Gray Color Scheme was chosen for text on other body sections.


## Features
 
### Existing Features
- Feature 1 - This site uses the **ScrollReveal** feature
  added to create an "scrolling" effect.
- Feature 2 - The navegation bar collapses for mobile screen sizes to
  promote a minimalist design
- Feature 3 - This site uses a valid feedback for the contact form feature in Bootstrap with 
  an extra JavaScript function added to improve the user experience.
- Feature 4 - This site uses a smooth zoom-in effect for the home page background.


### Features Left to Implement
- I will include more animations in the portfolio section using JavaScript.

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
    - The project uses **HTML** as building block.
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
    - The project uses **Cascading Style Sheets (CSS)** for adding style to the website.

## Libraries and Tools Used 

- [Bootstrap (4.5.2)](https://getbootstrap.com/)
    - The project uses **Bootstrap** to design and customize responsive mobile-first sites.
- [ScrollReveal](https://scrollrevealjs.org/)
    - The project uses **ScrollReveal** to animate elements as they scroll into view.
- [Balsamiq](https://balsamiq.com/wireframes/)
    - The project uses **Balsamiq** as wireframing tool.
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/)
    - I use **Chrome DevTools** to inspect and test styling and responsive desing during my development process.
- [W3C](https://validator.w3.org)
    - I use **W3C** to check the HTML and CSS files.
- [AmIResponsive](http://ami.responsivedesign.is)
    - I use **Am I Responsive?** to check my responsive design and take screenshots of the deployed website.
- [Fontawesome](https://fontawesome.com)
    - This project uses **FontAwesome** for including vector icons and social logos.
- [GoogleFonts](https://fonts.google.com)
    - This project uses **GoogleFonts** to import the font styles.
- [GitHub](https://github.com)
    - I used **GitHub** as my project repository.
- [GitHub Pages](https://pages.github.com)
    - I used **GitHub Pages** to deploy my project.
- [GitPod](https://www.gitpod.io)
    - I used **GitPod** as the cloud-based development environment to write my code.
 
## Testing

### Responsive design

I tested my site on Safari, Firefox and Google Chrome. The desktop version of the website
looks good and it is working as desired.

I used the chrome DevTools to test that the website is fully responsive. I tested the following
devices (mobile and tablet sizes):

- Moto G4.

- Galaxy S5.

- Galaxy S9 (my own device).

- iPhone 5/SE, iPhone 6/7/8, iPhone 6/7/8 Plus and  iPhone X.

- iPad and iPad Pro.

- Surface Duo.

I also used **Am I Responsive?** to check my responsive design.


### Code validation

I used **W3C** to check my HTML and CSS files, they are OK and without warnings or error messages.

## HTML file validation:

![HTML validation](/assets/images/html_validation.png)

## CSS file validation:

![HTML validation](/assets/images/css_validation.png)



### Testing user stories

1.  **I want to view the developer’s educational background, so that I can determine 
   the suitability of the candidate for the position.**
    
    1. Go to Home Page.
    2. Click on Resume icon on navegation bar (this will take the user to My Resume section).
    3. The user can see the education background.
    4. **Everything working fine**


2. **I want to see the developer’s projects portfolio, so that I can assess his hands-on experience**
     
    1. Go to Home Page.
    2. Click on Portfolio icon on navegation bar (this will take the user to My Portfolio section).
    3. The user can see the Portfolio page.
    4. Click on the four buttons in this section.
    5. **Everything working fine, links are properly shown in a new tab**.

Other user stories are related to the above described. **Everything working fine**. 

### Testing contact form

1. Contact form:
    1. Go to the "Contact Me" page
    2. Try to submit the empty form and verify that an error message about the required fields appears. **Everything working fine**. 
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears. **Everything working fine**. 
    4. Try to submit the form with all inputs valid and verify that a success message appears (Looks good! message). **Everything working fine**. 
    5. Try to submit the form with all inputs valid and verify that a new tab is opened with the message:
       Thank you very much for your message. I'll get back to you as soon as possible. **Everything working fine**. 


### Testing social links

1. Social links on home page:
   1. Go to Home page.
   2. Try to click on each of the four social links being shown.
   3. All links are working as expected. All new pages are displayed on a new tab.

1. Social links on footer:
   1. Go to Footer.
   2. Try to click on each of the four social links being shown.
   3. All links are working as expected. All new pages are displayed on a new tab.


### Testing download CV

1. My Resumé from Home page:
   1. Go to Home page.
   2. Try to click on the My Resumé button.
   3. Verify that a new tab is opened with a pdf file.
   4. **Everything working fine**. 

2. Curriculum Vitae and Resumé from footer:
   1. Go to Footer.
   2. Try to click on the Resumé button.
   2. Try to click on the Curriculum Vitae button.
   2. Verify that a new tab is opened with a pdf file.
   3. **Everything working fine**. 

### Testing scrolling effects

1. ScrollReveal effects:
   1. Refresh the page.
   2. Scroll down the entire website.
   3. Verify that every section is appearing as we scroll through them.
   4. **Everything working fine**. 

### Testing hovering effects

1. Hovering  effects:
   1. Refresh the page.
   2. Hoover on navegation bar.
   3. Hoover on buttons and icons in Home page.
   4. Hoover on buttons in Portfolio page.
   5. Hoover on icons in Footer.
   6. **Everything working fine**.


## Deployment

### Public deployment

This site is hosted using GitHub pages, deployed directly from the master branch.
I followed the procedure:

- I first created a new repository on my GitHub account.

- Then, I linked my repository the my GitPod environment by clicking on the "GitPod" green button available in GitHub.

- Once in GitPod environment, I initialised my repository by using the command `git init`.

- I used the GitPod terminal in order to add files, commit and push using Git version control.
  For instance, `git add file_name` for adding changes to a particular file the stagging area or
  `git add file_name` for adding all changes since the last commit.

- Then, I sent all changes to the remote repository in GitHub by using the command `git push`.

- Inmediately after, I went to my GitHub page and enter to the repository named: MilestoneProject_1.

- Once in the repository I went to setting, on the right top side of the page, and scrolled down to GitHub pages.

- I selected the master branch.

- Finally a link to the live website appeared.

Note:  The deployed site will update automatically upon new commits to the master branch.


### Local deployment 

To run locally, you can clone this repository directly into the editor of your choice by pasting
`git clone https://github.com/jdquerales/MilestoneProject_1.git` into your terminal
into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Media
- The photos used in portfolio section were obtained from [Pixabay](https://pixabay.com).

### Acknowledgements

- I received inspiration for this project from [Bootstrap Made](https://bootstrapmade.com/).
- I would like to thank my mentor Dick Vlaanderen for his support and helpful suggestions.
- I would like to thank my friends and colleagues from the Tyndall Institute, Ransell D'Souza and Manuel Odelli
  for their feedback on the deployed website.
- I would like to give an special thanks to Dermot Crinnigan for his support and feedback on the design of my project.