# ABC Boxing Club

The ABC Boxing Club website is a landing page for parents who have children interested in amateur boxing. The ages that are accepted are 10 to 18 years of age.

Users of the website will be able to find all the information they need about the club. What they offer in the facility in full detail, including opening times, pricing, contact information, a full list of what the club offers in these sessions and a sign up form. 

![website preview on all different screen sizes](<AM i responsive.png>)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured at the top of the page, the navigation shows the club name in the top left corner:ABC BOXING CLUB that also links back to the top of the page when clicked.
  - The other navigation links are to the right: About us, Sign up, Opening times and Contact us which all link to the different sections of the same page when clicked.
  - The navigation clearly tells the user the name of the club and website and makes the different sections of information easy to find. 

![image of navbar on ABC boxing website](navbar-1.png)

- __The header__

  - The header shows an image of a girl boxing with a trainer who has padding gear on. 
  - The header shows the name of the club in a clear and large font size.
  - The header explains that the boxing club is for children aged 10 to 18.
  - This section provides the user with clear information about what the site is and who the club is for.

![image of the header image and landing page](<header image landing page.png>)

- __The About Us Section__

  - The About Us section gives details about what the club offers their members in a list format.
  - This section shows the user the important information they need to know about the club in detail giving the user confidence knowing the club ethos and services provided. 

![About us section](<About us-1.png>)

- __The Opening Times section__

  - This section will allow the user to see exactly when the club sessions start and end on the different days of the week.
  - This section also shows the get together the club has once a week where members and non-members are welcome. 

![Opening times section](<opening times.png>)

- __The Sign Up Form__ 

  - The sign up section has a form to collect details from parents so they can sign up to ABC Boxing Club.
  - The form collects the child's name, parent/guardian's name, an email address and a contact phone number.
  - The sign up form is valuable to the user as it gives them the ability to sign up to join the ABC Boxing Club.

![sign up form image](<sign up.png>)

- __The Contact Section__

  - The contact section encourages users to get in contact and provides a phone number, email address and street address where they can be found.
  - The contact section includes social media icons so users can find ABC Boxing Club on facebook, twitter and instagram.
  - The contact section is valuable to the user as it gives them the ability to find and contact ABC Boxing Club if they need to.

![contact us section image](<contact us.png>)
- __The Sign Up Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)



### Features Left to Implement

- Gallery page/section with images of the facilities and some of training sessions.
- Member and parent/guardian testimonials.

## Testing 

- I tested that this page works in different browsers: Chrome, Safari, Firefox.
- I confirmed that the navigation, header, about us, opening times, sign up and contact text are all readable and easy to understand.
- I confirmed that when clicking on any of the navbar options you are taken to that part of the website page and also the logo on the top left takes the user to the top of the page.
- I have confirmed that the form works: entries in every field, will only accept an email in the email field and a number in the contact number field.

### Bugs

##### Solved bugs

- When I copied and pasted my index.html head onto my success page i'd neglected to copy a closing head tag and also part of the code in the stylesheet link which resulted in my css not being linked to my success page.
- This issue was resolved after checking the code and amending the missing attributes.



### Validator Testing 

- HTML
  - No errors were returned when passing through the official W3C validator
![W3C Validator html](<html checker.png>)
- HTML SUCCESS PAGE
 - No errors were returned when passing through the official W3C validator
 ![W3C validator success page](<html success.png>)
- CSS
  - No errors were found when passing through the official Jigsaw validator
![jigsaw validator](<css validator.png>)
- Accessibility
   - I confirmed that the colours and fonts are easy to read and accessible by running it through lighthouse in devtools.
   ![lighthouse report](lighthouse.png)


### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 


