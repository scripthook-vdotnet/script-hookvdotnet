================================================================================
                    SCRIPTHOOKVDOTNET WEBSITE
                    Professional Multi-Page Website
================================================================================

📌 PROJECT OVERVIEW
--------------------------------------------------------------------------------
This is a modern, responsive, professional website built with HTML, CSS, and 
JavaScript for ScriptHookVDotNet. The website features a clean design with 
smooth animations and excellent user experience across all devices.

📌 FILE STRUCTURE
--------------------------------------------------------------------------------
scripthookvdotnet.info/
│
├── index.html          - Home page with hero section and features
├── about.html          - About page with mission, vision, and values
├── contact.html        - Contact page with Google Form integration
├── download.html       - Download page with system requirements
├── style.css           - All styling and responsive design
├── script.js           - JavaScript for interactivity and animations
└── README.txt          - This file (setup and customization guide)

📌 HOW TO RUN LOCALLY
--------------------------------------------------------------------------------
1. Extract all files to a folder on your computer
2. Open any HTML file directly in your web browser:
   - Double-click index.html to view the home page
   - Or right-click → Open with → Your preferred browser
3. Navigate between pages using the navigation menu

Alternative: Use a local server (recommended for testing):
   - Python 3: python -m http.server 8000
   - Python 2: python -m SimpleHTTPServer 8000
   - Then open: http://localhost:8000

📌 CUSTOMIZATION GUIDE
--------------------------------------------------------------------------------

🎨 CHANGING COLORS
------------------
Edit style.css and modify the CSS variables at the top:

:root {
    --primary-color: #BBFE6C;      /* Main accent color (lime green) */
    --secondary-color: #FFFFFF;    /* Background/white */
    --accent-color: #1E1E1E;       /* Dark gray/black */
    --text-color: #1E1E1E;         /* Text color */
    --text-light: #666666;         /* Lighter text */
}

Change these hex values to your preferred colors.

🔗 UPDATING LINKS
-----------------
1. Google Form Link (Contact Page):
   - Open contact.html
   - Find: href="https://docs.google.com/forms/d/e/1FAIpQLSd4EKhtkytt-26izhOtx03F5GQ9bAs6iZHxvPK0wUkMTPSjIg/viewform?usp=header"
   - Replace with your Google Form URL

2. Download Link (Download Page):
   - Open download.html
   - Find: href="https://scripthookvdotnet.info/download/"
   - Replace with your download URL

3. GitHub Link (All Pages):
   - Open each HTML file
   - Find: href="https://github.com/scripthook-vdotnet"
   - Replace with your GitHub repository URL

4. Official Site Link (Home Page):
   - Open index.html
   - Find: href="https://scripthookvdotnet.info/"
   - Replace with your official site URL

✍️ CHANGING TEXT CONTENT
-------------------------
1. Open any HTML file in a text editor (Notepad, VS Code, etc.)
2. Find the text you want to change
3. Edit directly in the HTML
4. Save and refresh the browser to see changes

Example sections to customize:
- Hero titles and subtitles
- Feature descriptions
- About page mission and vision
- Footer information
- Page titles and meta descriptions

🔑 UPDATING KEYWORDS
--------------------
The keyword "scripthookvdotnet" is integrated naturally in:
- index.html (home page content)
- All page titles and meta descriptions

To update:
1. Search for "scripthookvdotnet" in each HTML file
2. Replace with your focus keywords
3. Ensure links remain natural and contextual

📱 RESPONSIVE BREAKPOINTS
-------------------------
The website is responsive at these breakpoints:
- Desktop: 968px and above
- Tablet: 768px - 968px
- Mobile: Below 768px
- Small Mobile: 480px and below

To adjust, edit the @media queries in style.css

📌 BROWSER COMPATIBILITY
--------------------------------------------------------------------------------
✓ Chrome (latest)
✓ Firefox (latest)
✓ Safari (latest)
✓ Edge (latest)
✓ Opera (latest)
✓ Mobile browsers (iOS Safari, Chrome Mobile)

📌 FEATURES INCLUDED
--------------------------------------------------------------------------------
✓ Responsive design for all devices
✓ Smooth scroll animations
✓ Mobile-friendly navigation menu
✓ Interactive hover effects
✓ Button ripple animations
✓ Lazy loading support
✓ Accessibility improvements
✓ SEO-friendly semantic HTML
✓ Clean, modern design
✓ Professional color scheme
✓ Google Fonts integration (Inter, Poppins)

📌 SOCIAL MEDIA & SEO
--------------------------------------------------------------------------------
To improve SEO, consider adding:

1. Open Graph tags (in <head> section):
   <meta property="og:title" content="Your Title">
   <meta property="og:description" content="Your Description">
   <meta property="og:image" content="your-image.jpg">

2. Twitter Card tags:
   <meta name="twitter:card" content="summary_large_image">
   <meta name="twitter:title" content="Your Title">

3. Favicon:
   <link rel="icon" type="image/png" href="favicon.png">

📌 ADDING YOUR LOGO
--------------------------------------------------------------------------------
1. Create or obtain your logo image (PNG recommended)
2. Save it in the same folder as the HTML files
3. In each HTML file, replace this section:

   <a href="index.html" class="logo">
       <span class="logo-text">ScriptHook</span>
       <span class="logo-accent">VDotNet</span>
   </a>

   With:

   <a href="index.html" class="logo">
       <img src="your-logo.png" alt="Your Brand" style="height: 40px;">
   </a>

📌 DEPLOYMENT OPTIONS
--------------------------------------------------------------------------------
1. GitHub Pages (Free):
   - Create a GitHub repository
   - Upload all files
   - Enable GitHub Pages in repository settings
   - Access at: https://yourusername.github.io/repo-name/

2. Netlify (Free):
   - Create account at netlify.com
   - Drag and drop your folder
   - Get instant hosting with custom domain support

3. Vercel (Free):
   - Create account at vercel.com
   - Import project from GitHub or upload folder
   - Deploy with one click

4. Traditional Web Hosting:
   - Upload all files via FTP to your hosting server
   - Ensure index.html is in the root directory

📌 TROUBLESHOOTING
--------------------------------------------------------------------------------
Problem: Navigation menu not working on mobile
Solution: Ensure script.js is properly linked and JavaScript is enabled

Problem: Styles not loading
Solution: Check that style.css is in the same folder as HTML files

Problem: Links not working
Solution: Verify all href attributes have correct URLs

Problem: Google Form not opening
Solution: Test the Google Form URL directly in browser

📌 ADVANCED CUSTOMIZATION
--------------------------------------------------------------------------------
Adding New Pages:
1. Copy any existing HTML file (e.g., about.html)
2. Rename it to your new page name (e.g., services.html)
3. Update the content inside <main> section
4. Add navigation link in all pages:
   <li><a href="services.html" class="nav-link">Services</a></li>

Changing Fonts:
1. Visit fonts.google.com
2. Select your preferred fonts
3. Replace the Google Fonts link in <head> section
4. Update font-family in style.css

Adding Images:
1. Place images in the same folder or create an "images" subfolder
2. Use <img src="images/your-image.jpg" alt="Description">
3. For optimization, use WebP format when possible

📌 MAINTENANCE & UPDATES
--------------------------------------------------------------------------------
Regular maintenance tips:
- Test all links monthly
- Update copyright year annually
- Check cross-browser compatibility after updates
- Validate HTML at validator.w3.org
- Test mobile responsiveness at different screen sizes
- Backup files before making major changes

📌 SUPPORT & RESOURCES
--------------------------------------------------------------------------------
HTML/CSS Learning Resources:
- MDN Web Docs: developer.mozilla.org
- W3Schools: w3schools.com
- CSS-Tricks: css-tricks.com

Web Design Tools:
- Color Palette: coolors.co
- Icons: fontawesome.com, heroicons.com
- Images: unsplash.com, pexels.com
- Fonts: fonts.google.com

Development Tools:
- Visual Studio Code: code.visualstudio.com
- Chrome DevTools: F12 in Chrome browser
- HTML Validator: validator.w3.org

📌 LICENSE & CREDITS
--------------------------------------------------------------------------------
This website template was created for ScriptHookVDotNet.
Designed & Developed with passion for the modding community.

Technologies Used:
- HTML5
- CSS3
- JavaScript (ES6+)
- Google Fonts (Inter, Poppins)

Feel free to modify and customize this website to fit your needs!

📌 CONTACT
--------------------------------------------------------------------------------
For questions or support, use the contact form on the website.

================================================================================
                    Thank You for Using This Template!
                    Happy Coding! 🚀
================================================================================
