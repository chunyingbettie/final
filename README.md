# final
Final Project writeup

1 Description 
The website I submitted is my personal portfolio that contains four pages.
2 Minimum Requirement Content
2.1	Four website pages: 
•	Design projects
•	Illustrations
•	About me
•	Hello UM
           Header: my profile picture in every page
           Navigation: Design Projects/Illustrations/About Me/Hello UM
           Footer: Copyright@Chunying Zhang at each page
2.2	Clearly display the current page: 
page has been underlined.
2.3	Jump to content: 
   press tab and enter button, users will be directed to the main content.
2.4	Minimum content included:
Page1: 2 pictures/2 paragraphs
Page2: 5 pictures/1 paragraph
Page3: 2 pictures/2 paragraphs
Page4: 4 pictures/3 paragraphs
3.Other requirements
3.1 Responsive design:
      The website is mobile first (iphone6/7/8 screen size, which is 768px), 
      so the two media queries are:
•	The screen size is larger than 768px, less than 1024px; applicable for ipad uses.
•	The screen  size is larger than 1024px; applicable for PC screen.
 How it improves the page: taking illustration page as an example:
•	When users check this page on their phone (less than 768px), the four pictures are placed in one column, easy for them to scroll down to check, rather than scroll left or right to check pictures.
•	When users check it on their ipad, the pictures are placed in two columns and two rows, looks neat. 
•	When users check it on PC screen, the pictures are placed in one row that will not waste the screen space.
3.2 Two Grid or Flexbox: 
•	Profile picture as header at each page -- Using flexbox on all four pages. I created a container with the class name “myself” that contains the profile picture element. 
•	Illustration page -- four pictures in one row uses grid. I use grid to create four columns and one row and fill each area with one picture, this is easy for me to create responsive design changes when shown on different screen size.
3.3 Two JavaScript:
•	Blink eye effect of profile picture with JavaScript: 
At any page. when the curser is hovering over the profile picture, the girl with blinking eye picture will be displayed, when the curser leaves, the original picture will be displayed.
•	Form validation at AboutMe page with JavaScript:  
At the bottom of aboutme page, there’s a form that enables users to contact me. If any of the form area is empty, there will be an alert to let users fill all form before submitting.
3.4 W3 and aXe validation
   All pages passed the w3 and aXe validations. 
  
  3.5 Great responsive design: Please check Illustration page.  

  3.6 Visually Appealing: Yes, I think so!   

4 Extra points: 
4.1 Full check of accessibility:
12 accessibility checks:
•	Color: color is not the only element to express the content on my website, there are also texts to express things. When I greyscale the website, all the information is still understandable.
•	Color contrast: aXe did not report any error regarding color contrast, so all color contrast ratios fulfill the requirements.
•	Image alternative text: all images has a text alternative to get users understand the image content.
•	Alternative text meaning: all text alternative reflects image content.
•	Image link: right now no image at my website has a link.
•	CSS Background image: my website does not contain any background image with css.
•	Text embedded in image: No image has text embedded in it on my website.
•	Tab order: The tab order follows the content logic, which makes sense.
•	Keyboard Focus: When tab through the page, users can always recognize which element is focused.
•	Access to full functionality: yes, users can purely use keyboard to scan the website to submit form or click button.
•	Form labels: Yes, all the input areas are given a corresponding label which makes sense.
•	For screen readers: yes, every page at my webpage follows a good structure easy to present to people who cannot see the webpage. 
4.2 Advanced JavaScript or jQuery: 
4.2.1 Modals: At About me page - contact me area, I added a modal that allows users to check my holiday plan so that they can have some anticipations about my message reply speed.
4.2.2 Flip Card:  The profile pic is like a flip card where when the mouse is hovering over it, it shows a different image.
4.3 Proficiency in grid: please check illustration page.
4.4 Proficiency in Bootstrap: At About me page, I’m using bootstrap to create the modal at contact me area. Try click the “Check Holiday Plan” button. 




