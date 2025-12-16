Project: DIGIMIZE – AI Automation Agency Website
About This Project
This is a high-performance corporate website I built for DIGIMIZE, an agency specializing in AI Clones and Social Media Automation. It includes 4 core pages (Home, Services, About, Contact) and features a fully responsive design that converts visitors into leads.

The goal was to build a site that looks premium, loads instantly, and captures data without needing a paid backend server.

What I Learned
HTML5 Structure: I implemented semantic tags (<header>, <nav>, <article>, <footer>) to improve SEO and accessibility.

CSS Layouts: I mastered CSS Grid for complex card layouts (Services/Pricing) and Flexbox for alignment in the Navbar and Hero sections.

Modern CSS: Instead of preprocessors, I utilized CSS Variables (:root) to manage the color palette, fonts, and spacing globally, making future updates instant.

JavaScript Animations: I used the Intersection Observer API to trigger fade-in, zoom-in, and slide-left animations only when elements scroll into view, ensuring high performance.

Serverless Backend: I learned how to connect a standard HTML form to Google Sheets using Google Apps Script, effectively creating a free database for leads.

Challenges & Solutions
Challenge 1: Complex Mobile Navigation
The design required a fullscreen mobile menu where links appear one by one.

Solution: I created a custom hamburger toggle animation (morphing from 3 lines to an "X") using CSS transforms. For the links, I used CSS variables (--i) to add staggered transition-delays, creating a smooth cascading effect when the menu opens.

Challenge 2: Handling Form Submissions without a Server
I needed the contact form to actually work and save data, but I didn't want to set up a Node.js or PHP server.

Solution: I wrote a custom script in Google Apps Script to act as a Web App API (doPost). I then used JavaScript's fetch() API in the frontend to send the form data asynchronously to the script, which appends the data to a private Google Sheet.

How to View This Website
https://digimize.netlify.app/
Download the project files.
Open index.html in your browser.
