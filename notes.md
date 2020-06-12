# Noel Rivera Email Builder Notes

## General thoughts on the assessment

The Foundation for Emails documentation was straightforward, and the two videos I watched covered the basics of Inky tags and images in Foundation for Emails. After reviewing those resources, I felt I had a firm grasp of the basics.

I began by blocking in the text and main images to match the InVision artboard. I then focused on addressing individual items that affected increasingly smaller aspects of the email. First, I changed the global width of the project to 640px, then I adjusted the image sizes to approximate the widths on the artboard. I followed by adjusting the typography and adding the custom header font, then continued on to button styling, text padding, and border images.

Colors were sampled from the PSD files in Photoshop, and image sizes  were viewed the same way. Image widths were applied inline, as my research suggested this was the most appropriate way to resize the images for email.

For the typography, I increased the global line height, font size, and font weight, as most of the text was larger and heavier, and only one section was smaller. For the smaller text, I created a new class.

As all buttons were the same color and size, I changed the global settings for background color, border color, font size, and padding. I created a class to affect the case of the text using the text-transform property.

For elements without specific reference in the documentation (mentioned under challenges), I used my best judgement and applied css styles inline and with classes after additional research.

I chose not to make the header and footer border images smaller, as leaving them at their standard widths provided the design with symmetry.

Though I wasn't given a design specific to mobile, I set a small column width on the hiring block that would allow the text in the second column to fall beneath the Hand of Fatima image on a small screen.

If designing this project myself, I might make the Alchemy logo and the sun and moon image a little larger on larger screens. But as they appear now, they should work for both.

Also regarding images, I've assigned them locally, but I'm aware that I would need to hard code them to an external location to make them viewable in an actual email.

## What I learned

I had not used Foundation for Emails before, nor had I used Inky or Sass, but after working on this project, I feel I've gained an understanding of these new tools. The Foundation folder structure is quite similar to the structure in Vue, which made navigating more intuitive. The Inky tags simplified the HTML portion of the project considerably, and the Sass global options made it easy to change most of the styling that I would have otherwise needed to write as CSS.

I also learned that some CSS involving images will render when using npm run start but not when using npm run build. These are issues I would continue working to resolve.

## Challenges

There was a problem with my npm start command that slowed me down at the beginning of the project. The command failed, which meant I was unable to open the server and view the email as it would appear when completed. While I could do a handful of things without npm to orient myself to Foundation for Emails, it ultimately had to be resolved before I could correctly render my work in the browser and complete the project. This required me to research several npm errors and to learn where to locate the npm modules folder in my project so I could delete it and reinstall npm. After updating my packages, deleting the folder, and reinstalling, I was able to run and view the project correctly.

I was unable to locate concrete information about adding padding to paragraph elements, so I used my best judgement and added it inline.

I was unable to locate specific information regarding unordered lists in the documentation. After additional research, I found that unordered lists are generally acceptable to use in emails. After that, it was simply a matter of finding CSS to create the custom bullet. However, I found that the custom CSS did not render after using the npm build. The spacing of the list remaind the same, but the images did not render. With the 3-5 hour time limit, I was unable to resolve this issue with the build, but I would continue to work on resolving this to find the correct way to render the bullet images.

The border edges were the last elements I addressed, and they took a little time to recreate, as I had to figure out both the correct CSS code as well as how to implement it using Inky. In the end, I created rows and columns into which the repeated images could be placed. These were then butted against the header and footer. I did notice that when using npm run build, these borders appear, but if I open the index file directly from the dist folder, they don't appear. I would be interested in learning more about why this happens.

## What I would do if I had more time

- Resolve the issues with the bullet list images when using npm run build (noted in challenges).
- Continue to work on the fonts. I recognize that something doesn't match between the artboard and my re-creation, but I haven't quite determined how to resolve it. While I did put the Vollkorn font in the global settings, I may need to do something else to fully import it for use, but I was unable to find specific documentation for this.
- Research whether there are additional ways to improve and/or streamline the code I've written. 
- Create partials for this design. Given that none of the elements were precise duplicates, I chose not to go down that path. But with more time, I might experiment with creating partials for some of the blocks, such as the About Us and the header/footer, as they could potentially be used in future projects.
