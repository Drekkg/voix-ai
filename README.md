# Voix-ai
Voix-ai is a website designed to drive traffic to an A.I voice modelling service.
The website is aimed at content creators, whether it is somebody making YouTube videos, product promotional vidoes
or audio books - in fact anybody that needs audio narration.
After landing on the home page the user would click on the link to the samples. After listenig to the samples,
and being suitably impressed, they would then signup for a free account, which would acquaint the user with the functionality and usefulness of Voix-ai. Professional and frequent users would become monthly subscribers.

![screenshot of Voix-ai on am i responsive](assets/images/screenshot-responsive.png)

## Features
An outline of features the user can expect.
### Existing Feautures
- __Navigation Bar__
- The Nav Bar is identical on all three pages making it easier for the user to traverse the website.
- It contains links to Home, samples and the Signup page.
- The Voix-ai logo is a clickable link back to the homepage.

![screenshot of navbar](assets/images/screenshot-nav-bar.png)

- __Landing page__
- The landing page consists of an image of a microphone, overlayed with text briefly describing
how the software functions, what the user can expect and a pitch as to why the user 
would want to use our software. 
![screenshot of landing-page](assets/images/screenshot-landing-page-new.png)

- __Navigation Button__
- The landing, Sign-up and Thank you page all contain a button that takes the user to the samples page.
- The button is a distinctive colour that draws attention to itself. 
- The aim is to get the user to hear the samples.

![clickable orange button](assets/images/screenshot-nav-button.png)

- __Footer__
- The footer is found on all pages including the Thank you page.
- It contains logos taht are links to websites and social media acoounts that use our software. 


![screenshot of footer](assets/images/screenshot-footer.png)

- __Samples Page__
- The Samples page contains four different samples of our voice modelling software.
- The audio is embedded in the website and only plays when clicked.
- An orange icon of a microphone adorns each sample, making it easier for the user to choose between samples.
- Each sample is labelled with the model and mode of voice it uses.
- Playback as well as volume is user defined.
- The samples are there to fascinate the user and compel them to sign up.

![screenshot of samples page](assets/images/screenshot-samples.png)

- __Sign Up Page__
- The Sign Up page contains a form so that the user can sign up for a free account.
- The form is responsive,  with a styled submit button underneath.
- Text below the sign up form informs the user about the benefita of signing up and also the benefits and price of subscribing.
- the user will be asked to submit their full name, create a user name and submit their email address.
- After submission the user will be referred to a thank you page.
- The form checks that all input fields are filled out and a valid email address is supplied.

![screenshot of sigup form page](assets/images/screenshot-signup.png)

- __Thank You Page__
- After succesful submission the user is rediredćted to a thank you page.
- The Thank You page displays a message thanking the user for joining and instructing them to check their emails 
- The background image is a man giving the thumbs up sign. Meant to be light hearted.
- The thank you page also contains the header and footer. 

![screenshot of thank you page](assets/images/screenshot-thank-you.png)

### Future Features to come.
-__Text Input Page__
- A feature to be added in the future, will be a text input box. Which will accept text input from the user and turn it into a narrated audio.
 
 ## Testing
 Voix-ai the website was tested on a variety of physical devices: Laptops, larger 27 inch monitors, various Android phones and Tablets. Where it loooked and performed as expected on a variety of browsers(Edge, Chrome, Firefox, Samsung browser). Responsiveness was tested in Google chrome using numerous of simulated devices(Apple iphones, ipads, Google Phones and Samsung).

 The Github deployed site was checked many times, mainly on mobile devices.
 The site was called up and the landing page was checked for legibility and responsiveness. The links in the header were clicked to ensure the appropriate page was opended. The sample link took me to the samples.html page. The signup link to signup.html. The logo-link in the header also works on all pages and takes the user back to the landing page. The samples all work and play in all browsers and on all devices tested. The sign up form works and requires valid input in all fields. The email field requires an @ sign and trailing letters. After a successful sign up the thank you page is displayed. The thankyou page responsiveness is not 100percent to my liking. It looks and works great on mobile, but on larger screens the image is a little large. 
 The "Click here for Samples" button also didn't work a few times - the problem was tracked to some invalid html and solved(More in Bugs section).

 ## HTML Validation
 The HTML was validated using NU HTML Validator.

 __Index HTML__
 ![screenshot of HTML testing](assets/images/screenshot-index-html.png)
 The first pass failed because of some errors: trailing slashes, incorrectly nested divs.

 __Samples HTML__
 ![screenshot of HTML samples testing](assets/images/screenshot-sample-html.png)
 This file had similar problems with trailing slashes.

 __Signup Html__
 ![screenshot of signup HTML validation](assets/images/screenshot-signup-html.png)
 This file had similar problems with trailing slashes.

 __Thank You__
 ![screenshot of Thank You HTML](assets/images/screenshot-thankyou-html.png)

 ## CSS Validation
The CSS styles file was validated using The W3C validation Service.
![screenshot of css validation](assets/images/screenshot-style-css.png)
Checking the CSS file turned up no errors.

