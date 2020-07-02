# Portfolio Description

## link to deployed page

## https://proflonghair07.github.io/Murphy_Vaughn_Portfolio/

## ![](assets/images/Portfolio_Screenshot.PNG)

## This project contains 3 html pages. The pages are index, contact, and portfolio. It uses bootstrap css and a stylesheet I created locally, in that order. My style sheet is second so that I am able to overwrite styles from bootstrap to get the results needed. All three pages contain identical nav bars and sticky footers. I activated the drop down menu for the header by adding bootstrap's javascript in a script tag. I placed this at the bottom of the page just before the closing body tag. I did this so that browser could load all of the graphical elements before loading the javascript. All three pages utilize Bootsraps components and grid system. The pages look good in all sizes of scalability. This was achieved by heavily using bootsraps classes. Especially the container row and col classes. These characteristics are shared by all 3 pages, but they are different from each other in other ways.

## The index page is an about me page. Aside from the header and footer all of this pages elements are contained in a singe main tag with a container class called from bootstrap. The container has the pages title in an h1 tag, a horizontal rule, an image nested in an img tag, and a short paragraph about me wrapped in a p tag. The container is responsive to different screen sizes because the tags within it contain bootstrap's row and col classes.

## The portfolio page is a short list of "accomplishments" that contains pictures and links. Like the index page, the portfolio page has an h1 tag with the pages title a horizontal rule beneath it. Also all of this pages elements are nested in a main tag with a container class from bootstrap. The container contains 4 sections with col classes from bootstrap. Each section has an anchor tag with an image, an h2 with a title, and a p with some text. Because all of these elements are contained within an a tag the whole container functions as a link when clicked.

## The contact page is a page that has a from where the user can enter their name, email, and a message. Like the other two pages, it contains an h1 tag with the title followed by a horizontal rule. All of this pages elements are in a main tag with a container class. The user inputs are all contained in a form tag with divs inside that have a form-group class pulled from bootstrap. Below the inputs is a submit button made with a button tag.

## The local css file is fairly minimal. I tried to utilize bootstrap's classes whenever possible and used my own css for minor tweaks. There are some tag selectors, but for the most part it uses class selectors. All three pages use the same stylesheet. I did all of the color styling for the my pages in my css file. I created classes for the elements and used the background-color element to style them with hexadecimal codes for the colors I chose.
