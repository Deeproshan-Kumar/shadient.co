# Project Title

Shadient.co

## Project Description
This is a dark theme based animated website built using set of libraries like swiperJS, locomotiveJS, GSAP ScrollTrigger and more.

## Issues I Faced and How I Resolved Them

While developing this website, I faced an issue where LocomotiveJS hijacks the scroll functionality of the entire application, preventing other scroll events from working. After researching the problem, I found an article with a code snippet that helped me fix the issue.
Article: https://gsap.com/docs/v3/Plugins/ScrollTrigger/static.scrollerProxy()/
Codepen: https://codepen.io/GreenSock/pen/ExPdqKy

## Table of Contents
- Folder structure
shadient(root)
- assets
    fonts
        afrandir
            fonts
    images
        clients
            img1, img2, ..., imgn
        services
            img1, img2, ..., imgn
        sponsors
            img1, img2, ..., imgn
    other images...

- src
    css
        app.css (Application Stylesheet)
        fonts.css (Fonts Import)
        responsive.css (Responsive CSS)
        utility.css (Global CSS)
    scripts
        app.js (Application Scripts)
index.html
about.html
services.html
favicon.ico
readme.md


## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Deeproshan-Kumar/shadient.co
