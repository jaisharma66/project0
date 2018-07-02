# Project 0

Web Programming with Python and JavaScript

Hello! Welcome to my first project, and thus my first website. Through this README, I hope to clarify some of the decisions that I made for this website.

The first thing that I did was create the pages required for this project. This included "Index.html", "page1.html", "page2.html", "page3.html", "page4.html", and "style.css".
I left the names for the files ambiguous on purpose so I could recognize the files even through the numerous title changes the pages underwent.
The scss files were created independently as the project went on to style very specific items. For the rest of the README, I will talk through each file.

styles.css
This file contained most of the various styles that are used throughout the code. I used .class the most; the implementation was quite and easy, and it was applicable over multiple
items as well, making it an obvious choice. The first 2 containers are used for the navbar and the flexboxes. The container for the navbar applied over all the pages, while the
container for the flexboxes only applied to page 3. Container 2 applied to the flexboxes that appear on page 2, and had specific styling for those flexboxes. Before continuing on, I
would like to acknowledge that for the navbar, I used Bootstrap, and thus I used their online resources to aid with the styling. In terms of the flexboxes, I used the available resources
from lectures 0 and 1 to aid in creating those. The next selector used was the ID selector. This styled the ID on page 4. For some specific attributes available for styling photos I
used w3 schools. (https://www.w3schools.com/css/css3_images.asp) Overall, throughout the project, I used that website, but I will cite the areas where I acquired new knowledge so that
this README is not inundated with links. That being said, I will cite where I used their resources. Continuing on, the rest of the styling is much of the same, with items such as
hover being referenced from w3. (https://www.w3schools.com/cssref/sel_hover.asp) The other items such as media queries and more were referenced from the lectures.

navbar_style.scss
The navbar_style has examples of both inheritance and variables. Beginning with varibales, I used the variable $color to set a color to that variable. The inheritance occurs
from %navigation and affects the other 2 inheriting from it. I wanted all of the navbar items to have the same font size, yet different font weights, thus requiring inheritance.
Again, I used the lecture 1 notes for help on this part.

table_style.scss
This file shows examples of nesting. Everything within the ol and ul have the color #474747 applied to them, but each list has its own specific attributes. In the individual lists, the uls
have different attributes. Here, the one thing that I needed to search was the !important, which makes that styling the most important for css to style. This overwrites any other style which
was necessary in this condition.

index.html
This is the first html sheet and is simply the main menu linking to different parts of the website. Two things that I included from the lecutres were the bootstrap and viewport style
sheets, as I remember the recommendation that we should include those in all of our files. The rest of the file is quite simple, with it linking to the other pages.

page1.html
Page 1 includes the ordered list that was styled by table_style. This page was quite simple aswell. I used w3 schools here as well to have an example of how to structure the table.
The code from the lecture also came in handy.

page2.html
page2 includes the table, which was styled by style.css. The attribute of importance on this page is the flexboxes. I had trouble getting the boundaries exactly correct, and was
helped by Alex Mariano during the office hours. This rectified the issue.

page3.html
page3.html was the most difficult, and took the longest time in referencing each link with the correct image. I had to create multiple divs for the flexboxes and for the reference id
that was used. I used w3 and the example code here aswell to link everything in a more coherent manner.

page4.html
page4 was very simple. I wanted a photo of myself as well as a short description of the website, which follows after the photo. For this page, however, I have the photo styled by a specific
reference id from style.css so that its size adjusts to the screen

Conclusion
Overall, the project was very fun and challenging. I want to say thank you to all of the TFs who helped during sectionals and office hours with the project. I would also like to thank
you, the grader, for spending time reviewing this project.
