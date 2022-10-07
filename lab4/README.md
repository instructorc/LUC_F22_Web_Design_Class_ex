# Lab 4 Implementing Responsive Design
Complete the following steps to make MPLS dob boarding website responsive.

1.  Download the files from this repository into a folder titled  “lab4”.

2.  Open the project folder in your text editor and comment your name at the top the home.html page.

3.  Include the required meta tags discussed in class within the head of your site. The content attributes for each meta tag should be adjusted to reflect site content.

4. **Observing the need for responsive design:** Using Chrome or Firefox browser make sure the site is set to 100% zoom.  Within the browser, inspect the MPLS Dog Boarding homepage by pressing F12.  Slowly reduce the width of the browser by holding the mouse and dragging the edge of the screen into a smaller view.  
    * Underneath the comment that contains your name, Identify at least 1 areas of the site that would improve the site responsiveness and appeal at smaller screen widths. Keep in mind, in most cases a horizontal scroll bar indicates a need for adjustment to make site responsive.

5.  **Implement Media Queries:** Implement two media queries into your site. One media query with a max-width break-point of 1024px and the other with a max-width break-point of 768px.  Test to make sure the media queries work by temporarily changing the presentation of your site at each break-point.

6. **Media Query for Break-point max-width 1024** - Make the follow changes:

    * Override the style rule that targets the 3 aside box elements and change the height value to auto
    * Override the style rule that targets the ```<main id=”flexcontainer”>``` element and change the background-size value to auto.

7.  **Media Query for Break-point max-width 768px** - Make the following changes:

   * Override the style rule that targets the ```<main id=”flexcontainer”>``` element and provide the background-image with a new relative file path to the “dog_bg_768.jpg” image.
   * Change the background-size value to cover for ```<main id="flexcontainer">```
   * Override the style rule that targets the 3 aside box elements and make the following changes:
      * Change the background-color value to #000000cf
      * Change the background-position value to center;
      * Change the color of the text to white.
Override the style rule that targets the ```<button id=”location_button”>``` and change the display value to block.
8.  Triggering animation using pseudo class of hover: Create a pseudo class for the style rule that targets the 3 aside box elements and make the following changes

    * Add a background-color of # #ff4500bd;
    * Add a height of 325px
    * Change the color of the text to white.
9.  Implement the transition property – Add the declaration “transition: all .2s ease-in-out;” to the element that controls the three aside box elements

10.  Validate HTML and CSS code and fix all errors and warnings related to homepage.

11.  Remove all borders and visual inspect site in browser

12.  Commit your work the repository provided to you by the instructor

## Submission
Your project folder will need to be submitted to the assigned GitHub repository provided to you by the instructor. In Sakai, you will need to submit the link to your repository by the due date and time listed in the write-up. Make sure you receive confirmation from Sakai that your assignment has been submitted. Submission video instructions [here](https://instructorc.github.io/site/slides/presentation/video/github_upload.mp4) 
