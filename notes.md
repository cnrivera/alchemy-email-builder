# Noel Rivera Email Builder Notes

## General thoughts on the assessment

I started the project by reading the Foundation for Emails documentation and setting up the project on my system. The documentation was straightforward enough, and the two additional videos I reviewed covered the basics of Inky tags and images in Foundation for Emails.

Following this, I blocked in the text and main images to match the Invision artboard. I then started focusing on individual items that needed to be addressed. I started with the global width of the project, then adjusting the image sizes to approximate the widths on the artboard, followed by adjusting the typography and adding the custom header font. I moved onto smaller items, such as button styling, in sequence.

Colors were sampled from the PSD files in Photoshop, and image sizes of the slices were viewed the same way. Image widths were applied inline, as my research suggested this was the most appropriate way to resize the images for email.

For the typography, I updated the sizes of the global line height and font size to be larger, and the font weight to be heavier, as more of the text was this size and weight, and only one section was smaller. For the smaller text, I created a new class.

As all buttons were the same color, I changed the global settings for background color, border color, font size, and padding. I created a class to affect the case of the text.

For elements without specific reference in the documentation (mentioned under challenges), I used my best judgement and applied css styles inline and with classes after additional research.

## What I learned

## Challenges

There was a problem with my npm start command that slowed me down at the beginning of the project. The command failed, which meant I was unable to open the server and view the email as it would appear when completed. While I could do a handful of things without npm to orient myself to Foundation for Emails, it ultimately had to be resolved before I could correctly render my work in the browser and complete the project. This required me to research several npm errors and to learn where to locate the npm modules folder in my project so I could delete it and reinstall npm. After updating my packages, deleting the folder, and reinstalling, I was able to run and view the project correctly.

I was unable to locate concrete information regarding adding padding to paragraph elements, so I used my best judgement and added it inline.

I was unable to locate specific information regarding unordered lists in the documentation. After additional research, I found that unordered lists are generally acceptable to use in emails. After that it was simply a matter of finding css to create the custom bullet.

## What I would do if I had more time
