![preview](https://github.com/sulav-gautam/Sidcup-Family-Golf-Clone/assets/159540990/dadbaa4a-75ab-4957-9727-3cb8d1486a5d)

# Overview
This project replicates the front-end of the Sidcup Family Golf website using HTML, CSS, and JavaScript. It aims to provide a responsive and visually appealing user interface similar to the original site.

# Structure
## HTML
The structure is organized into different sections (#nav, #main, #page1 to #page4, #footer) mirroring the original website's layout. Each section contains appropriate elements like headers, paragraphs, images, and videos.

## CSS
The stylesheet (style.css) defines the layout, colors, typography, and animations used throughout the site. Notably, it includes custom scrollbar styling, hover effects, and layout adjustments for various screen sizes.

## JavaScript
The script (script.js) enhances user interaction with features such as a custom cursor (#cursor and #cursor-blur), animated transitions using GSAP library (gsap and ScrollTrigger), and hover effects on navigation items (#nav h4). Additionally, it manages dynamic content scrolling within #scroller.

# Key Features and Techniques
## Custom Cursor
Implemented using JavaScript to track mouse movement (mousemove event) and adjust position (#cursor) and blur effect (#cursor-blur).

## Scroll Animations
Utilizes GSAP (gsap and ScrollTrigger) for scroll-based animations (#nav, #main, #about-us img, .card, #colon1, #colon2, #page4 h1), enhancing user experience with smooth transitions.

## Dynamic Content Scrolling
Achieved through #scroller and #scroller-in, animating horizontally scrolling text content indefinitely using CSS animations (@keyframes scroll).

## Responsive Design
Ensures adaptability across devices with fluid layouts (@media queries in style.css) and scalable typography (vw, % units).

## Hover Effects
Enhances interactivity with hover effects (h4 elements in #nav, .card:hover .overlay, .elem:hover h2, etc.) using CSS transitions and JavaScript event listeners.

# Challenges and Solutions
## Custom Cursor Implementation
Ensuring the cursor remains responsive and visually appealing across different screen sizes and elements required careful positioning and transition handling.

## Scroll Animations Synchronization
Adjusting GSAP's ScrollTrigger parameters (start, end, scrub) for each animation to synchronize with scrolling events and achieve seamless transitions.


## Dynamic Content Management
Managing dynamically scrolling content (#scroller) involved CSS animations and careful structure to avoid layout disruptions or performance issues.



