# Tutoring Joy

Tutoring Joy is a (fictitious) company that offers tutoring services to parents wanting the extra support for their children. This website has been created as a first point of contact for any parent who was to look up various tutoring options, and is meant to be a basic representation of what a fully-fledged website for such a company could look like. I have used a variety of tools, encomprising HTML and CSS to create this website.

![Tutoring Joy on Different Screens](https://github.com/immanueligwe151/tutoring-joy/blob/main/assets/images/screenshots-of-all.png)

# Features
![](https://github.com/immanueligwe151/tutoring-joy/blob/main/assets/images/screenshot-1.png)
## Header, Navigation and Sections
In the above screenshot, there is a header with a the company name Tutoring Joy, as well as a logo, which I created myself. I have used responsive design in such a way that on larger screens the logo is on the same line with the company name and the tagline, and on smaller screens the logo is on top, with the rest below it.

The Navigation Bar consists of links to the 4 sections of the page: About Us, Our Packages, Sign Up and Contact Us. These links have been designed to take you to the relevant part of the page.

I have used Semantic HTML to design the different sections of the page. I have also utilized Flexbox CSS in designing the layout of the sections. The About Us and Our Packages sections follow the same pattern, where there's some text to the side outlining that section, and a supplementary image as well. Using responsive design, I've made it so that on larger screens the images are on one side of the screen, and the text on the opposite side, and for smaller screens the image is stacked on top of the relevant text. I've also made the position of the images and text alternate for each section (for larger screens).

The two images that are used in this website are not mine. I got them from the free image resource [Pexels](www.pexels.com). The first image was gotten from [here](https://www.pexels.com/photo/black-teacher-explaining-presentation-to-diverse-elementary-pupils-5905440/) and the second from [here](https://www.pexels.com/photo/teacher-scolding-her-students-6936074/). This has also been referenced in the relevant HTML code.

![](https://github.com/immanueligwe151/tutoring-joy/blob/main/assets/images/screenshot-3.png)
## Sign Up and Contact Us
In the above screenshot, there is a form in which the parent can sign up their child for a tutoring package. This would prompt the members of staff at Tutoring Joy to contact the parent to give them more information regarding tutoring for their child. I have used form validation to ensure that no important data is missed out. For the sake of functionality, I have used Code Institute's [FormDump](https://formdump.codeinstitute.net/), where the data sent is displayed back at you as a means to show that the form has been coded correctly.

And then on the bottom of the page, there are various options displayed as means of contact. A phone number, email and social media handles have been provided. For the social media icons displayed on the bottom of the page, I had done some research and got my code from [W3Schools](https://www.w3schools.com/howto/howto_css_social_media_buttons.asp), which I have referenced in their respective places.

# Testing
I have tested this website using Google Chrome and Microsoft Edge on my Windows PC, adjusting the window size and seeing its outlook on different screen sizes. I have also tested it on my personal mobile device.

I have tested and confirmed that all the links are working, and all the external links open in new tabs.

I have tested and confirmed that the form is working, and that data is sent on correctly.

I have tested and confirmed that all text is easy to read.

# Bugs
Whilst writing this README document I found that I had omitted one of my HTML id attributes, which made the site not work properly. I hence went to put it back

Whilst coding the form, I forgot to add the POST method and the action URL, which led to the form not working, hence I had to add those after finding that out

The responsive design for the form isn't 100% good and it might still mess up a bit on smaller screens

The Contact Us section could be a bit more compact as there seems to be too much whitespace between elements


# Validator Testing
I have tested the HTML code with W3C Validator testing and there are no errors with my code. Except with the warning of my self-closing tags ending with </>, which is attributed to Codeanywhere automatically putting that when the file is saved.

I have tested the CSS code with W3C Jigsaw testing and there are no errors with my code.

I have tested my site's accesibility with Chrome's Lighthouse and have been given an overall score of 99%.
![](https://github.com/immanueligwe151/tutoring-joy/blob/main/assets/images/lighthouse-report.png)

# Deployment
The site was deployed with GitHub pages. In the repository of this code on GitHub, the main branch was selected, and then a link was automatically generated for the website.