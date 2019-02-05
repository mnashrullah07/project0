# Project 0

Web Programming with Python and JavaScript

At project 0, I created a simple personal website, which contained important information such as my education, my skills, and my work experience.
In this project I created 4 html files and 1 css file (generated from scss using scout-app). I also added bootstrap according to the task requirements.

Index.html, its function is as the main page of the website, containing H1 tags that call @media queries for the purpose of displaying responsive mobile websites, so that when opened in a browser below 500 pixels the title "Personal Biodata" will become "personal bio.
Then I use a grid system which is a bootstrap component to divide into 2 parts, in the first part which is class = "col-sm-auto", I add the "nav flex-column" navigation which is a bootsrap component for mobile responsiveness. In the second part, namely class = "col-md-auto" which uses top and middle id. in the top contains img tags that display photos, there are also calling the "responsive" class so that the size is limited to 250 pixels. In the middle section contains my description, along with the name, email, phone and address.

In Menu1.html containing my work experience, like in the index.html file, I divide 2 parts of the page, fist part is class = "col-sm-auto" for me to add navigation and second part also class = "col-md-auto" which contains and ordered list

In Menu2.html, containing my skills, also like in the index.html file, I divide 2 parts of the page with the same class name, first for navigation & second part class = "col-md-auto" which contains an unordered list

And the last html menu3.html, apart from the same class division at the second part i created a table that showing my education history.
At the styles file i add table border 2px, a solid black, collapse and font-family sans-serif.
