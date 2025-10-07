================================================================================
                    ATMOSPHERE SWITCH WEBSITE
                Professional Multi-Page Website Documentation
================================================================================

TABLE OF CONTENTS
-----------------
1. Introduction
2. File Structure
3. How to Run the Website Locally
4. Customization Guide
5. Color Palette
6. Important Links to Update
7. SEO Keywords & Internal Links
8. Responsive Design
9. Browser Compatibility
10. Support & Resources

================================================================================
1. INTRODUCTION
================================================================================

This is a professional, modern, responsive multi-page website designed for 
Atmosphere Switch. The website includes:

- Home Page (index.html) - Hero section with keyword links and content
- About Page (about.html) - Mission, vision, and values
- Contact Page (contact.html) - Google Form integration
- Download Page (download.html) - Resource download section
- Responsive design for mobile, tablet, and desktop
- Modern UI/UX with smooth animations and transitions

================================================================================
2. FILE STRUCTURE
================================================================================

atmosphereswitch5/
│
├── index.html          # Home page with hero section and keyword links
├── about.html          # About page with mission and vision
├── contact.html        # Contact page with Google Form button
├── download.html       # Download page with download button
├── style.css           # All styling and responsive design
├── script.js           # JavaScript for interactivity and navigation
└── README.txt          # This documentation file

================================================================================
3. HOW TO RUN THE WEBSITE LOCALLY
================================================================================

OPTION 1: Double-Click Method (Simplest)
-----------------------------------------
1. Navigate to the website folder
2. Double-click on "index.html"
3. The website will open in your default web browser

OPTION 2: Using Live Server (Recommended for Developers)
---------------------------------------------------------
If you use Visual Studio Code:
1. Install the "Live Server" extension
2. Right-click on "index.html"
3. Select "Open with Live Server"
4. The website will open with auto-reload functionality

OPTION 3: Using Python (For Testing)
-------------------------------------
1. Open terminal/command prompt in the website folder
2. Run: python -m http.server 8000
   (or: python3 -m http.server 8000)
3. Open browser and go to: http://localhost:8000

OPTION 4: Deploy to Web Hosting
--------------------------------
Upload all files to your web hosting provider via:
- FTP/SFTP client (FileZilla, Cyberduck)
- cPanel File Manager
- GitHub Pages (if using version control)

================================================================================
4. CUSTOMIZATION GUIDE
================================================================================

CHANGING TEXT CONTENT
----------------------
To update text on any page:
1. Open the HTML file in a text editor (Notepad++, VS Code, Sublime Text)
2. Find the text you want to change
3. Replace it with your new text
4. Save the file

CHANGING IMAGES
---------------
Currently, the website uses placeholder gradients for images.
To add real images:
1. Place your images in an "images" folder
2. Find the relevant section in HTML (e.g., .hero-card, .image-placeholder)
3. Replace the div with: <img src="images/your-image.jpg" alt="Description">

ADDING NEW PAGES
----------------
1. Copy an existing HTML file (e.g., about.html)
2. Rename it to your new page name (e.g., services.html)
3. Update the content inside the <main> section
4. Add a link to it in the navigation of all pages:
   <li><a href="services.html" class="nav-link">Services</a></li>

================================================================================
5. COLOR PALETTE
================================================================================

The website uses the following color scheme:

Primary Color:   #5982D6 (Blue)
Secondary Color: #FAFAFA (Light Gray/White)
Accent Color:    #7534F7 (Purple)
Text White:      #FFFFFF (White)
Text Dark:       #1a1a1a (Almost Black)
Text Gray:       #666666 (Medium Gray)

TO CHANGE COLORS:
-----------------
Open style.css and modify the CSS variables at the top:

:root {
    --primary-color: #5982D6;      /* Change this */
    --secondary-color: #FAFAFA;    /* Change this */
    --accent-color: #7534F7;       /* Change this */
    --text-white: #FFFFFF;         /* Change this */
}

All colors throughout the website will automatically update!

================================================================================
6. IMPORTANT LINKS TO UPDATE
================================================================================

GOOGLE FORM LINK (Contact Page)
--------------------------------
Current Link: https://docs.google.com/forms/d/e/1FAIpQLScQfW5_cmuD6E85Dh0GEeyvJUUYjRMA-_inEbviXO1_xx_-BA/viewform?usp=header

To Change:
1. Open contact.html
2. Find: href="https://docs.google.com/forms/..."
3. Replace with your new Google Form URL
4. Save the file

GITHUB REPOSITORY LINK
----------------------
Current Link: https://github.com/atmospher-switch/AtmoSphere-Switch

To Change:
1. Open each HTML file (or use Find & Replace in your editor)
2. Find: https://github.com/atmospher-switch/AtmoSphere-Switch
3. Replace with your GitHub URL
4. Save all files

DOWNLOAD PAGE LINK
------------------
Current Link: https://atmosphereswitch.com/download/

To Change:
1. Open download.html
2. Find: href="https://atmosphereswitch.com/download/"
3. Replace with your download page URL
4. Save the file

OFFICIAL WEBSITE LINK
---------------------
Current Link: https://atmosphereswitch.com/

To Change:
1. Use Find & Replace in all HTML files
2. Find: https://atmosphereswitch.com/
3. Replace with your official website URL
4. Save all files

================================================================================
7. SEO KEYWORDS & INTERNAL LINKS
================================================================================

The home page includes these focus keywords with natural internal linking:

1. "atmosphere switch" → https://atmosphereswitch.com/
2. "how to install sigpatches switch" → https://atmosphereswitch.com/switch-game-issues-after-sigpatches/
3. "tinfoil not working" → https://atmosphereswitch.com/tinfoil-not-working-beginners-guide/
4. "how to update fusee" → https://atmosphereswitch.com/atmosphere-and-fusee-not-working/

TO UPDATE KEYWORD LINKS:
------------------------
1. Open index.html
2. Find the keyword text (e.g., "atmosphere switch")
3. Update the href attribute in the <a> tag
4. Ensure keywords appear naturally in content
5. Don't overuse - each link appears only once for natural SEO

TO ADD NEW KEYWORDS:
--------------------
1. Write natural content in paragraphs
2. Wrap the keyword in an anchor tag:
   <a href="your-url" class="inline-link">your keyword</a>
3. Use the "inline-link" class for consistent styling

================================================================================
8. RESPONSIVE DESIGN
================================================================================

The website automatically adapts to different screen sizes:

Desktop:  1200px and above (Full layout)
Tablet:   768px - 1199px (Adjusted columns)
Mobile:   Below 768px (Single column, hamburger menu)

The mobile navigation menu:
- Appears as a hamburger icon on mobile
- Slides in from the right
- Closes when clicking outside or on a link

TO TEST RESPONSIVENESS:
-----------------------
1. Open the website in a browser
2. Press F12 to open Developer Tools
3. Click the device toolbar icon (or press Ctrl+Shift+M)
4. Test different device sizes

================================================================================
9. BROWSER COMPATIBILITY
================================================================================

The website is compatible with:
✓ Google Chrome (latest)
✓ Mozilla Firefox (latest)
✓ Safari (latest)
✓ Microsoft Edge (latest)
✓ Opera (latest)

Features used:
- CSS Grid & Flexbox
- CSS Custom Properties (variables)
- ES6 JavaScript
- IntersectionObserver API
- Smooth scroll

================================================================================
10. SUPPORT & RESOURCES
================================================================================

DOCUMENTATION RESOURCES
-----------------------
HTML:  https://developer.mozilla.org/en-US/docs/Web/HTML
CSS:   https://developer.mozilla.org/en-US/docs/Web/CSS
JavaScript: https://developer.mozilla.org/en-US/docs/Web/JavaScript

FONTS USED
----------
- Inter: Professional, clean sans-serif font
- Poppins: Modern, friendly font for headings
- Loaded from Google Fonts (requires internet connection)

To use custom fonts:
1. Download font files (.woff, .woff2)
2. Create a "fonts" folder
3. Add @font-face rules in style.css

ICONS & SVG
-----------
The website uses inline SVG icons for:
- Navigation icons (GitHub)
- Feature icons
- Button icons
- Social media icons

Benefits of inline SVG:
- No external dependencies
- Easy to style with CSS
- Scalable without quality loss
- Small file size

================================================================================

QUICK CUSTOMIZATION CHECKLIST
------------------------------
[ ] Update Google Form URL in contact.html
[ ] Update GitHub repository URL in all pages
[ ] Update official website URLs
[ ] Change color palette in style.css (if needed)
[ ] Replace placeholder images with real images
[ ] Update footer copyright year
[ ] Test on mobile, tablet, and desktop
[ ] Test all links work correctly
[ ] Optimize images before uploading
[ ] Deploy to web hosting

================================================================================

TIPS FOR BEST RESULTS
----------------------
1. Always backup files before making changes
2. Test on multiple browsers and devices
3. Optimize images for web (compress to reduce file size)
4. Keep content concise and easy to read
5. Update regularly to keep content fresh
6. Monitor page load speed (use Google PageSpeed Insights)
7. Ensure all external links open in new tabs
8. Check spelling and grammar
9. Maintain consistent branding across all pages
10. Keep the design clean and professional

================================================================================

NEED MORE HELP?
---------------
- Refer to the inline comments in the HTML, CSS, and JavaScript files
- Check browser console for any JavaScript errors (F12 → Console)
- Validate HTML: https://validator.w3.org/
- Validate CSS: https://jigsaw.w3.org/css-validator/
- Test mobile-friendliness: https://search.google.com/test/mobile-friendly

================================================================================

VERSION INFORMATION
-------------------
Version: 1.0
Created: 2024
Design: Modern, Professional, Responsive
Technology: HTML5, CSS3, JavaScript (Vanilla)

================================================================================

Thank you for using this website template!
For the best experience, follow the customization guide and test thoroughly
before deploying to production.

Good luck with your Atmosphere Switch project!

================================================================================
