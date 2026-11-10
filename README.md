# Personal Homepage

A personal portfolio website built with HTML, CSS and JavaScript for CS50x Problem Set 8.

**Live site:** https://YOUR-USERNAME.github.io/homepage/

## About

This site is about me, YOUR NAME, and shows what I have built and learned so far. It has four pages:

- **Home** (`index.html`): a welcome page with a link to my projects
- **About** (`about.html`): who I am and what I am learning
- **Projects** (`projects.html`): cards linking to my work, including the tree problems in Python and my SQL queries
- **Contact** (`contact.html`): a contact form

## Features

- A navigation bar on every page that links all four pages together
- Valid HTML5 on every page
- A separate stylesheet (`css/style.css`) linked with `<link>`
- A responsive layout that works on phones and desktops, using flexbox, grid and a media query
- A **dark mode** button that saves the visitor's choice
- A contact form that checks the fields before "sending" (it does not send anything anywhere)

## Project structure

```
homepage/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
```

## How the JavaScript works

`js/main.js` has two parts:

1. **Dark mode:** when the visitor clicks the button, the code toggles a `dark` class on the page, which swaps the color variables in the CSS. The choice is saved in the browser so it stays the same on the next visit.
2. **Form check:** when the visitor submits the contact form, the code stops the page from reloading, checks that every box is filled in and that the email contains an `@`, and shows a message.

## Built with

HTML5, CSS3, JavaScript, and GitHub Pages for hosting.
