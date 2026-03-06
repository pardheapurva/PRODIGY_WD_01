# PRODIGY_WD_01

Blooming Bliss – Interactive Navigation Menu

A responsive and interactive navigation menu built using HTML, CSS, and JavaScript. The navigation bar remains fixed at the top of the page and dynamically changes style when the user scrolls or hovers over menu items, improving user experience and website interactivity.

Task Description

Task 1
 - Create an interactive navigation menu that changes color or style when:
    The page is scrolled
    The user hovers over menu items

Requirements:
    The navigation menu should have a fixed position
    It must remain visible on all pages
    Use HTML for structure
    Use CSS for styling
    Use JavaScript to add interactivity such as:
    Changing background color when scrolling
    Changing font color on hover

# Live Demo
https://pardheapurva.github.io/PRODIGY_WD_01/


# Features

 - Fixed navigation bar visible on all pages
 - Navigation color changes on scroll
 - Hover animation on menu items
 - Smooth UI interactions
 - Clean and modern design
 - Multiple pages (Home, About, Shop, Contact)

Technologies Used

HTML5 – Page structure

CSS3 – Styling and layout

JavaScript – Interactivity and dynamic behavior

 Project Structure
PRODIGY_WD_01/
│
├── index.html
├── about.html
├── shop.html
├── contact.html
│
├── style.css
├── script.js
│
└── images/

# How It Works
1️. Fixed Navigation Bar

The navigation bar is positioned using:

position: fixed;
top: 0;
width: 100%;

This ensures the menu stays visible while scrolling.

2️. Scroll Effect

JavaScript detects page scrolling and changes the navbar style.

Example logic:

window.addEventListener("scroll", function() {
    const navbar = document.querySelector("nav");
    navbar.classList.toggle("scrolled", window.scrollY > 50);
});

This adds a new style when the user scrolls down.

3️. Hover Effect

CSS handles hover animations.

nav a:hover {
color: pink;
transition: 0.3s;
}

This improves user interaction feedback.

# What I Learned

Through this project, I learned:

How to build interactive UI components

Using JavaScript scroll events

Implementing hover animations in CSS

Creating a fixed navigation bar

Structuring multi-page websites

Improving user experience through UI behavior

# Future Improvements

Add mobile responsive navigation

Add dropdown menu

Add smooth scrolling

Implement dark mode

# Author

Apurva Pardhe

