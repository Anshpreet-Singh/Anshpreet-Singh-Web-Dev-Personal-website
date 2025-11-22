LABWORK-3
Portfolio Website — Simple Responsive Design

This project is a personal portfolio website created using HTML and CSS.
It showcases sections such as Home, About, Skills, Projects, and Contact.

The design focuses on:

Clean and simple UI

Soft colors and readable layout

Easy-to-understand CSS

Fully responsive structure for mobile, tablet, and desktop

🔧 Features

Sticky navigation bar

Hero section with image

Skills displayed using CSS grid

Simple project cards

Contact form (non-functional template)

Responsive design with smooth layout adjustments

📱 Responsive Behavior — How to View

To test the website’s responsiveness, follow these steps:

1. Open the Website in a Browser

Open index.html in Chrome, Firefox, Edge, or any modern browser.

2. Open Developer Tools

Right-click → Inspect

Or press:

Ctrl + Shift + I (Windows)

Cmd + Option + I (Mac)

3. Enable Device Toolbar

Click the mobile/tablet icon (top-left in DevTools).
This allows you to test different screen sizes.

📏 Breakpoints Tested

The layout was tested at commonly used breakpoints:

Device Type	Width (approx)	Behavior
Laptop / Desktop	900px and above	Full 2-column hero layout, grid for skills & projects
Tablet	600px – 899px	Slightly compressed layout, grid adjusts columns
Mobile	below 600px	Hero stacks vertically, grids collapse into single column
Key CSS breakpoint inside the stylesheet:
@media (max-width: 900px) {
    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero-img img {
        width: 65vw;
    }
}


This breakpoint ensures the hero section adapts correctly on tablets and mobile devices.

📂 Project Structure
/portfolio
│── index.html
│── style.css
│── README.md
│── photo.jpg
**
