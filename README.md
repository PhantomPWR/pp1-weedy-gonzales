

# Weedy Gonzales - Make lawns green again

## Diploma in Full Stack Software Development - Portfolio Project 1

![Mockup](assets/readme/device-mockups.png)

Weedy Gonzales is a fictional lawn care and weed control company, operating in West Sussex, England. The site will target homeowners and tenants who are looking for lawn care services and advice.

The site's main objective is to guide the visitor towards getting in contact, using the shortest route possible - with ample opportunity to do so along the way.

The visitor's journey is laid out in a concise, lighthearted fashion, inspired by the ["Jobs To Be Done"](https://www.amazon.co.uk/Jobs-Be-Done-Playbook-Organization/dp/1933820683/ref=asc_df_1933820683/?tag=googshopuk-21&linkCode=df0&hvadid=427902758346&hvpos=&hvnetw=g&hvrand=470378916435561382&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1006628&hvtargid=pla-899714836217&psc=1&th=1&psc=1&tag=&ref=&adgrpid=103526071910&hvpone=&hvptwo=&hvadid=427902758346&hvpos=&hvnetw=g&hvrand=470378916435561382&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1006628&hvtargid=pla-899714836217) framework.

1. This journey starts by picturing the ideal outcome (Hero Image)
2. Reminding the visitor of the reasons they want a healthy lawn in the first place (Your Job)
3. How Weedy Gonzales can help them achieve the outcome (Our Job)
4. An opportunity to take action and get in contact (Let's Go)

Not all visitors might decide to take action only at the end of the journey, hence the Booking buttons in each section.

<br>

---
## [View the live website in github pages](https://phantompwr.github.io/pp1-weedy-gonzales/)
---

<br>

# Table of contents

- [UX](#ux)
    - [Website owner business goals](#website-owner-business-goals)
    - [Website visitor goals](#website-visitor-goals)
        - [New visitor goals](#new-visitor-goals)
        - [Returning visitor goals](#returning-visitor-goals)
    - [User stories](#user-stories)
    - [Site structure](#site-structure)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
- [Features](#features)
- [Technology](#technology)
- [Testing](#testing)
    - [Functionality testing](#functionality-testing)
    - [Compatibility testing](#compatibility-testing)
    - [User stories testing](#user-stories-testing)
    - [Issues found during site development](#issues-found-during-site-development)
    - [Contact form testing](#contact-form-testing)
    - [Accessibility](#accessibility)
    - [Code validation and performance testing](#code-validation-and-performance-testing)
- [Deployment](#deployment)
- [Credits](#credits)



# UX

## Website owner business goals

The aim of this website is to make potential customers aware of the service and capture leads.

## Website visitor goals

### New visitor goals:
- find information about lawn care and weed control
- easily get in touch with the service provider to arrange a home visit

### Returning visitor goals:
- find up-to-date information and advice on lawn care and weed control
- arrange follow-up home visits

<br>

## User stories
---

### As a business owner:
* I want to introduce my services to potential customers
* I would like to encourage potential and existing customers to book home visits

### As a new customer:
* I wish to find information about lawn care and weed control
* I would like advice on my specific needs

### As a returning customer:
* I would like to find advice and tips on keeping my lawn healthy
* I would like to know how to keep my outdoor spaces clean and weed-free

<br>

## Site structure
---

The website is designed to guide the visitor towards getting in contact, using the shortest route possible - with ample opportunity to do so along the way. The aim is to give the visitor a pleasant experience, whether they use a desktop computer, tablet, mobile device or screen reader. There should also be feedback from the interface, including hover effects on links and buttons.

<br>

## Wireframes
---

The website wireframes were created using Balsamiq.
The tablet and phone wireframes show the different screens when scrolled.

<br>

### ***Desktop***
----

![Desktop](assets/readme/wireframes/01-desktop.png)

<br>

### ***Tablet***
----
![Tablet](assets/readme/wireframes/02-tablet.png)

<br>

### ***Phone***
----
![Phone](assets/readme/wireframes/03-phone.png)

<br>

## Surface
---

### Colours
Main colours used for the website:
* background: #3b6110
* body text (dark): #3a3a3a
* body text (light): #ffffff
* section heading (dark): #3b610f
* section heading (light): #ffffff
* hover colour: #3b610f
* button colour: #ffa41c

### Fonts
[see credits](#credits)
* body: Lato
* headings: Oswald
* fallback: sans-serif

### Images
[see credits](#credits)
* Photos: sourced from  [pexels.com](https://www.pexels.com/)
* Logo & favicon: Created myself

<br>

[Back to Table of contents](#table-of-contents)
___

<br>
<br>

# Features


The website consists of 1 main page containing 4 sections, a 404 error page and thank-you page. The features of the site are as follows:

## Main Header

<br>

### ***Desktop/Landscape Header***
----

![Desktop/Landscape Header](assets/readme/features/header-nav/01-main-header-desktop.png)

<br>

* The header is fixed to the page top, for easy access to navigation
* On the left is the company logo, which also doubles as a "home" link
* On the right is the navigation bar

<br>

### ***Mobile Portrait Header***
----

![Mobile Portrait Header](assets/readme/features/header-nav/02-main-header-mobile.png)

<br>

* Because the header is fixed at the top, it inevitably occupies valuable screen real estate. As a result, the navigation links will wrap on smaller-width devices/orientations. This in turn, would increase the height of the header and reduce the visible content even more
* Replacing the navigation links with a menu button(hamburger) means the height of the header can be kept to a minimum

<br>

## Navigation

* Navigation consists of links to the different page sections
* Navigation link appearance and behaviour is consistent across devices
* The links are:
    * Your Job - scrolls to the introduction/benefits section
    * Our Job - scrolls to the section containing the services on offer
    * Let's Go! - scrolls to the contact form


<br>
<br>

### ***Desktop/Landscape Navigation***
----

![Desktop/Landscape Navigation](assets/readme/features/header-nav/03-navigation-menu-desktop.png)

<br>

* Each navigation link has an icon, which matches the heading icon of the relevant section
* Link hover action is confirmed by adding a bottom border and changing the link colour

<br>
<br>

### ***Mobile Portrait Navigation***
----

![Mobile Portrait Navigation](assets/readme/features/header-nav/04-navigation-menu-mobile.png)

<br>

* The menu button(hamburger), activates a menu which slides in from the right of the screen
* Tapping on a link is, once again, confirmed by the appearance of a bottom border and a change in colour

<br>

## Hero Section
----

![Hero & CTA](assets/readme/features/hero-section/hero-cta.png)

<br>
<br>

### Hero Image
Below the header, is the hero section, containing:

* an image of a healthy, well-kept lawn
* clean, weed-free paving
* a pleasant, relaxing seating area - overlooking the garden

The image was specifically chosen to showcase the result of a healthy lawn, i.e. relaxing while enjoying your garden. Coupled with the company logo and motto/strapline at the top left, the perspective and angle of the image lead the visitor's eye towards the call to action on the right-hand side.

### Call to Action
* The call to action clearly states its purpose, what is on offer and a button encouraging the visitor to take action
* The "Book Now!" button opens the contact form in a modal window, offering the visitor the opportunity to provide their contact details on the spot

<br>
<br>

## Modal Window
![Modal Window](assets/readme/features/modal-window.png)

In order to encourage the visitor to provide contact details, the site also features a modal window, containing a contact form.
* The modal window is unobtrusive and initiated by the visitor
* A semi-opaque background gives a visual clue that the visitor is still on the the same page, yet focuses attention on the call-to-action and contact form
* An introductory paragraph reminds the visitor of the modal window's purpose and encourages them to fill in the form


<br>

----


## Footer
![Footer](assets/readme/features/footer/01-footer.png)


* Contains links to the company's various social media pages
* A back-to-top button provides a shortcut to the top of the page, without having to manually scroll multiple times. This is especially helpful on smaller screens
* The final element in the footer is the copyright notice

<br>

### ***Social Media Links***
----

![Social Media Links](assets/readme/features/footer/02-social-media.png)


* Familiar, easily identifiable icons, link to each corresponding social platform
* Both `title` and `aria-label` attributes remind the visitor where the icon links to, as well as informing them that the link opens in a new browser tab
* A border and change of colour give visual feedback when interacting with the links
* *PLEASE NOTE:* As this is a fictitious company website, all social media links go to the main URLs of the respective platforms - NOT real Weedy Gonzales accounts 

<br>

### ***Back to Top Button***
----

![Back to Top Button](assets/readme/features/footer/03-back-to-top.png)

* The back-to-top button contains both text and an icon, which makes its purpose clear
* Once again, visual feedback confirms purpose and interaction

<br>

### ***Mobile Footer***
----

![Mobile Footer](assets/readme/features/footer/04-footer-mobile.png)

* On small mobile screens, the order of the elements changes so the back-to-top button is above all other footer elements. This makes it easier to access
* In line with the "design for big thumbs" principle, social media icons have sufficient space to avoid touching unintended links

<br>


## Content Sections
____

<br>


### Your Job (Benefits)
----

![Your Job](assets/readme/features/content-sections/01-your-job.png)

* This section reaffirms the ideal scenario pictured by the hero image, i.e. the visitor has better things to do than slaving away over weeds
* The title - Your Job - breaks away from the hard-sell "benefits" approach, which is almost the norm in many industries. Instead, it puts the visitor first
* The visitor is presented with a checklist, which deliberately doesn't include maintaining the lawn, paving, etc.
* A prominent, yet friendly button invites the visitor to take action

<br>

### Our Job (Services)
----

![Our Job](assets/readme/features/content-sections/02-our-job.png)

* In a similar vein to the previous section, the message is simple: lawn treatment & weed control isn't the job of the visitor
* This is why the section is titled "Our Job"; the time, equipment and experience involved is not something the visitor wants to be trammeled by
* Once again, the visitor is offered the opportunity to unload the burden of maintaining their lawns and/or hard surfaces

<br>

### Let's Go! (Contact)
----

![Let's Go!](assets/readme/features/content-sections/03-lets-go.png)

* The heading, paragraph and form button all urge the visitor to take action - again, without using the usual pushy sales language

<br>

### 404 Page
----

![404 Page](assets/readme/pages/404-page.png)

* The light-hearted language is used to defuse a potentially frustrating situation
* The button text reassures the visitor that it has come to the rescue


<br>

### Thank You Page
----

![Thank You Page](assets/readme/pages/form-thank-you-page.png)

* When the visitor completed any of the contact forms, it is a good user experience to receive acknowledgement that the form has been submitted successfully
* Once a form has been submitted, the site visitor is redirected to a branded thank-you page, containing a friendly confirmation message, as well as the various familiar navigation links
____

<br>
<br>


#  Future Implementations

### **Technology**
**As this is purely an HTML & CSS project, my aim was to avoid JavaScript at all costs, and see how far I could take CSS.**

After extensive research, I've come to the conclusion that the following implementations/improvements would require JavaScript:
* A floating back-to-top button, appearing after scrolling past a certain point
* Running a fading-out animation, when closing the modal window
* Stop the page from scrolling behind the open modal
* Prevent anchors adding unnecessary, meaningless browser history

### **Content**
* A calendar booking system to view availability and book a home visit
* A blog containing lawn care and weed control tips
* A live chat function for handling enquiries and offering advice
* A page showing before & after photos, as well as customer feedback


[Back to Table of contents](#table-of-contents)
___

<br>
<br>

# Technologies Used

### **HTML5**
* For page markup.

### **CSS3**
* For visual presentation and interactive feedback.

### **Font Awesome**
* An icon library for navigation links, social links, page section visual cues and back-to-top button.

### **Google Fonts**
* For serving custom fonts.

### **GitHub**
* Hosting the site repository.

### **GitHub Pages**
* Hosting the live site.

### **Git**
* For version control.

### **Gitpod**
* Online, cross-device IDE.

### **Balsamiq**
* Wireframing application.

### **Affinity Designer**
* Graphic editor for creating the site logo.

### **Affinity Photo**
* Photo editor for manipulating the hero & services images.

### **Cloudconvert.com**
* Converting images to .webp format

### **Tinypng.com**
* Image compression & optimisation

<br>


[Back to Table of contents](#table-of-contents)
___

<br>
<br>

# Testing

<br>

## Functionality testing
---

 I mainly used Chrome developer tools throughout the project for testing and troubleshooting.
 
  The Chrome browser extention, [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) was very helpful in identifying elements overflowing their containers.

<br>

## Compatibility testing
---

 Testing was done on various browsers, virtual and physical devices.

<br>

 ### Desktop Browsers
| Browser | Device | Operating System |
|--|--|--|
| Google Chrome (v103.0.5060.134) | iMac 27 inch | MacOS Big Sur (v11.6.7) |
| Mozilla FireFox (v103.0.1) | iMac 27 inch | MacOS Big Sur (v11.6.7) |
| Apple Safari (v15.6) | iMac 27 inch | MacOS Big Sur (v11.6.7) |
| Microsoft Edge (v103.0.1264.77) | iMac 27 inch | MacOS Big Sur (v11.6.7) |

<br>

 ### Laptop Browsers
| Browser | Device | Operating System |
|--|--|--|
| Google Chrome (v103.0.5060.134) | Macbook Pro 13 inch | MacOS Big Sur (v11.6.1) |
| Mozilla FireFox (v103.0.1) | Macbook Pro 13 inch | MacOS Big Sur (v11.6.1) |
| Apple Safari (v15.6) | Macbook Pro 13 inch | MacOS Big Sur (v11.6.1) |
| Microsoft Edge (v103.0.1264.77) | Macbook Pro 13 inch | MacOS Big Sur (v11.6.1) |

<br>

### Mobile Devices
| Browser | Device | Operating System |
|--|--|--|
| Safari (v15) | iPhone Xs | iOS (v15.6) |
| Safari (v15) | iPhone 12 Pro | iOS (v15.5) |

<br>

### Virtual Devices

The following virtual devices were tested in Chrome Developer Tools:

<br>

**Phones**

 * iPhone 5/SE
 * iPhone X
 * iPhone SE
 * iPhone XR
 * Google Pixel 5
 * Samsung Galaxy S8+
 * Samsung Galaxy S20 Ultra

<br>

**Tablets**

* iPad Mini
* iPad Air
* iPad Pro
* Surface Pro 7

<br>

**Other**

* Google Nest Hub
* Google Nest Hub Max

<br>
<br>

## User stories testing
---

<br>

### As a business owner:

- I want to introduce my services to potential customers
    > An overview of available services is presented in the "Our Job" section

- I would like to encourage potential and existing customers to book home visits
    > In addition to the contact form in the "Let's Go" section, buttons to access the modal contact form are present in every section of the page

<br>

### As a new customer:
- I wish to find information about lawn care and weed control
    > Once again, essential information is available in the "Our Job" section, along with an invitation to get in touch

- I would like advice on my specific needs
    > As a minimum viable product, the website offers this opportunity via a response to providing contact details

<br>

### As a returning customer:
- I would like to find advice and tips on keeping my lawn healthy
- I would like to know how to keep my outdoor spaces clean and weed-free
    > In this first version of the website, all enquiries are handled by the contact form.
    >  Future iterations will include blog articles containing hints & tips, and a live chat function for handling questions and enquiries


---

<br>
<br>

## Issues found during site development

<br>

### **Shortcut icon (favicon) missing on the deployed site**
![Favicon Missing on GitHub Pages](/assets/readme/issues/favicon-missing-github-pages.png)

The shortcut icon displayed correctly, when viewing the site locally. However, the icon didn't appear on GitHub Pages.
* I placed the favicon.ico file in the root directory of the site, but nothing else

### **Fix**
* I did a Google search for "favicon not displaying on github pages"
* I then found an answer in a GitHub discussion (https://github.com/reposense/RepoSense/issues/897)
* Added the below code snippet to the `<head>` of all `.html` files, which resolved the issue:
* `<link rel="shortcut icon" href="favicon.ico">`

![Favicon Fixed on GitHub Pages](/assets/readme/issues/favicon-fixed-github-pages.png)

<br>
<br>

### **Macbook Pro Compatibility**

The layout of the call-to-action inside the hero section, broke on the 2020 13inch Macbook Pro.

![2020 13inch Macbook Pro - Aside Broken](assets/readme/issues/2020-macbook-pro-aside-broken.jpg)

### **Fix**
Inside my Laptops media query, I added a rule to set the min- and max-height of the aside element:
```
aside {
        min-height: 300px;
        min-width: 300px;
    }
```

<br>
<br>

### **Samsung Galaxy S20 Ultra Compatibility**

The layout of the call-to-action inside the hero section, broke on the Samsung Galaxy S20 Ultra in landscape orientation.

![Samsung Galaxy S20 Ultra (landscape) - Aside Broken](assets/readme/issues/samsung-galaxy-s20-ultra-landscape-aside-broken.png)

### **Fix**
Inside my Phone Large (Landscape) media query, I changed the max-width condition from:

<br>

`@media (max-width: 914px)`

to

`@media (max-width: 915px)`

<br>
<br>

## Contact Form Testing
---

<br>

### **Form Submission**

1. As a test, I set the the contact form `action` attribute to the Code Institue form dump URL (https://formdump.codeinstitute.net)
2. I filled out and submitted the form
3. All the input field data was sent and recorded correctly:

![Form Data Sent Correctly](assets/readme/form-tests/form-data-sent-correctly.png)

<br>

### **Form Validation**

<br>

**Email Field**

The email field validation works correctly:

![Email Field Validation Pass](assets/readme/form-tests/form-validation-email-pass.png)

<br>

**Phone Number Field**

On testing the phone (tel) field validation, I noticed that any input was accepted - not just numbers:
![Phone Field Validation Fail](assets/readme/form-tests/form-validation-type-tel-fail.png)

<br>

### **Fix**
After asking on Slack and searching [W3Schools](https://www.w3schools.com/html/html_form_input_types.asp), I realised that the input `type="tel"` needs a `pattern` attribute, containing the desired format to use as a reference.

As the company's target audience is located in the Southern England, I decided to use the following pattern:

`pattern="[0-9]{11}"`

I tested the form again and the field validation worked as expected:

![Phone Field Validation Pass](assets/readme/form-tests/form-validation-type-tel-pass.png)

After all tests have been completed successfully, I did the following:
* Changed the form `action` attribute to a thank-you page URL
* Changed the form `method` from `POST` to `GET`, in order to prevent errors caused by the submitted data not being sent anywhere
* Added a note above the form HTML, to remind future developers working on the site that the `method` must be updated when the `action` is changed to a URL receiving/processing the form data

<br>

### **Accessibility**

<br>

My initial Lighthouse tests revealed a contrast issue on the buttons: 

![Phone Field Validation Pass](assets/readme/accessibility/lighthouse-accessibility-button-contrast-fail.png)

I used [WAVE](https://wave.webaim.org/) to check and adjust the ratio until I found a combination that pass both AA and AAA tests.

<br>
* After applying a flatter shade of orange for the background and a very dark grey for the text, the button contrast passed
* I also applied a deeper shade of green for headings, link hover colours and relevant backgrounds. Although this wasn't a flagged issue, it did improve the contrast ratio.

<br>

WAVE also reported a couple of failed ARIA tests:

<br>

![Failed ARIA Tests](assets/readme/accessibility/lighthouse-accessibility-aria-ids-fail.png)

<br>

* When I created the modal window, I duplicated the contact form
* This meant that the ARIA IDs for the form elements weren't unique anymore
* I rectified the errors by adding `-modal` to the relevant IDs
---

<br>
<br>

![No ARIA Landmarks](assets/readme/accessibility/wave-no-aria-landmarks.png)

<br>

* As the 404 page only contains one main container, I used a `<div>`, which resulted in the error above
* I changed the `<div>` to a `<section>`, which also didn't work
* After reviewing a list of semantic HTML elements, I finally used `<main>`, which passed the test

<br>

## **Code Validation and Performance Testing**
---
 I used the following services for code validation and final testing:
 
 * [WAVE](https://wave.webaim.org/) to test accessibility
 * Lighthouse (Chrome Developer Tools) to test performance
 * [Nu Html Validator](https://validator.w3.org/) to validate HTML
 * [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to validate CSS
 

 <br>

 ### **Test Results**
 ---

 <br>

### **WAVE**
![WAVE Test main-page](assets/readme/test-results/main-page/main-page-wave.png)
![WAVE Test thank-you-page](assets/readme/test-results/thank-you-page/thank-you-page-wave.png)
![WAVE Test 404-page](assets/readme/test-results/404-page/404-page-wave.png)

 ---

 <br>

### **Lighthouse**
![Lighthouse Test main-page](assets/readme/test-results/main-page/main-page-lighthouse.png)
![Lighthouse Test thank-you-page](assets/readme/test-results/thank-you-page/thank-you-page-lighthouse.png)
![Lighthouse Test 404-page](assets/readme/test-results/404-page/404-page-lighthouse.png)

 ---

 <br>

### **HTML Validator**
![HTML Validator Test main-page](assets/readme/test-results/main-page/main-page-html-validator.png)
![HTML Validator Test thank-you-page](assets/readme/test-results/thank-you-page/thank-you-page-html-validator.png)
![HTML Validator Test 404-page](assets/readme/test-results/404-page/404-page-html-validator.png)

 ---

 <br>

### **CSS Validator**
![CSS Validator Test main-page](assets/readme/test-results/main-page/main-page-css-validator.png)
![CSS Validator Test thank-you-page](assets/readme/test-results/thank-you-page/thank-you-page-css-validator.png)
![CSS Validator Test 404-page](assets/readme/test-results/404-page/404-page-css-validator.png)

<br>

[Back to Table of contents](#table-of-contents)

___

<br>

# Deployment

The project has been deployed on GitHub Pages. As my development environment I used Gitpod, from where I commited all changes to the Git version control system.

**To save changes, used the following commands:**
1. [cmd]+s to save changes
2. `git add .` - to add all changes to the queue
3. `git commit -m "commit message"` - to commit changes
4. `git push` - to push changes to the remote main repository

<br>

**To deploy the project onto GitHub Pages, I did the following:**

1. Log into GitHub and click on the relevant repository ([pp1-weedy-gonzales](https://github.com/PhantomPWR/pp1-weedy-gonzales))
2. Click on `Settings`
3. On the left, find and click on Pages
4. Leave `Source` as is
5. Under `Branch`, select `main`
6. click `save`
7. After an automatic page refresh the message will read: 
>  Your site is live at https://phantompwr.github.io/pp1-weedy-gonzales/

<br>

**To run a local instance:**

1. Log into GitHub and click on the repository to be downloaded ([pp1-weedy-gonzales](https://github.com/PhantomPWR/pp1-weedy-gonzales))
2. Select `Code` and click on `Download ZIP`
3. After downloading, you can extract the file and use it in your local environment

Alternatively you can [Clone](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
or [Fork](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)
this repository ([pp1-weedy-gonzales](https://github.com/PhantomPWR/pp1-weedy-gonzales)) into your github account.

<br>

[Back to Table of contents](#table-of-contents)
___

<br>
<br>

# Credits


* To complete this project I used Code Institute's student template: [gitpod full template](https://github.com/Code-Institute-Org/gitpod-full-template)

* Ideas and knowledge library:

    * [w3schools.com](https://www.w3schools.com)

    * [css-tricks.com](https://css-tricks.com/)


### **Code**

* Font-size reset to multiples of 10: CSS Double Reset, thanks to [Eventyret_mentor](https://code-institute-room.slack.com/team/U4MVA9YQP) at Code Institute
* Links transition: [CSS transition Property](https://www.w3schools.com/cssref/css3_pr_transition.asp)
* Pure CSS modal, using the ":target pseudo-class" technique [CSS-only modal](https://www.w3schools.com/cssref/sel_target.asp)

#### **README File**
* [marcin-kli](https://github.com/marcin-kli) whose [README.md](https://github.com/marcin-kli/MP1/blob/45f9748e8bccecbb3de182fbbabe521e4974064b/README.md) file I used as an example for creating mine.

### **Content:**
*  Content reference and inspiration:
[Greensleeves UK](https://www.greensleeves-uk.com/)
[Luxury Lawns UK](https://luxurylawns.co.uk/)

* **Copywriting:**
My VERY patient wife, Nikki, for her copywriting services

* **Website/company name**
  * I thought of the name after a throwaway comment from my wife, about a similarly-named cartoon mouse
  * I did a Google search for Weedy Gonzales, and came across an existing [Weedy Gonzales](https://soundcloud.com/pluegel), who appears to be a songwriter/DJ - so I doubt anybody would mistake him for a lawn care company.


### **Images**

#### Pexels.com:
* [Pexels - Filipe Delgado](https://images.pexels.com/photos/1601495/pexels-photo-1601495.jpeg?cs=srgb&dl=pexels-filipe-delgado-1601495.jpg&fm=jpg)

* [Pexels - Kaboom Pics](https://images.pexels.com/photos/6083/garden-moss-stone-sett.jpg?cs=srgb&dl=pexels-kaboompics-com-6083.jpg&fm=jpg)

* [Pexels - Anastasiia Goncharova](https://images.pexels.com/photos/12515537/pexels-photo-12515537.jpeg?cs=srgb&dl=pexels-anastasiia-goncharova-12515537.jpg&fm=jpg)

* [Pexels - Max Artbovich](https://images.pexels.com/photos/7061662/pexels-photo-7061662.jpeg?cs=srgb&dl=pexels-max-vakhtbovych-7061662.jpg&fm=jpg)

<br>

[Back to Table of contents](#table-of-contents)
___
