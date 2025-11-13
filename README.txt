================================================================================
PORTFOLIO WEBSITE - MAAJID DHIROTTSAHA
Junior Data Scientist & AI Enthusiast
================================================================================

PROJECT STRUCTURE
-----------------

/PORTOFOLIO
├── index.html          - Main HTML file with all sections
├── style.css           - Complete styling with light theme and blue/gray tones
├── script.js           - JavaScript with Chart.js, animations, and interactions
├── README.txt          - This file
├── /images             - Folder for project images and visuals
└── /assets             - Folder for icons, logos, and additional assets


WEBSITE SECTIONS
----------------

1. HOME
   - Animated headline and introduction
   - Interactive data visualization chart
   - Call-to-action buttons

2. ABOUT ME
   - Biography and background
   - Education details (Institut Teknologi PLN)
   - Technical exposure overview

3. SKILLS
   - Data Processing (Pandas, NumPy, SQL)
   - Data Visualization (Matplotlib, Seaborn, Power BI/Tableau)
   - Machine Learning (Scikit-learn, Regression, Clustering, Classification)
   - Tools & Platforms (Jupyter, Google Colab, GitHub)
   - Animated skill bars

4. PROJECTS
   - Real-Time Data Warehouse (SDG 11)
   - Traveling Salesman Optimization
   - Microprocessor Data Logger
   - Image Recognition Experiment
   - Each project includes description, tools, and GitHub links

5. RESEARCH & LEARNING
   - Blog-like section showcasing ongoing experiments
   - Topics: House Price Prediction, SCD in Data Warehousing, Kaggle participation

6. DATA GALLERY
   - Interactive charts using Chart.js
   - Sales Trend Analysis (Bar Chart)
   - Customer Segmentation (Doughnut Chart)
   - Performance Metrics (Line Chart)

7. CONTACT
   - Contact form (Name, Email, Message)
   - Contact information and social links
   - Download CV button


TECHNICAL FEATURES
------------------

- Responsive Design: Mobile-friendly layout using Flexbox and Grid
- Chart.js Integration: Interactive data visualizations
- Smooth Scrolling: Enhanced navigation experience
- Animate On Scroll (AOS): Elements animate when scrolled into view
- Form Handling: Contact form opens email client via mailto link
- Modern UI: Clean, scientific aesthetic with blue/gray color scheme
- SEO Optimized: Meta tags, semantic HTML, alt text support
- Accessibility: Proper heading structure, ARIA-friendly markup


DEPLOYMENT INSTRUCTIONS
------------------------

OPTION 1: GitHub Pages
----------------------

1. Create a new repository on GitHub (e.g., "portfolio-website")

2. Upload all files to the repository:
   - index.html
   - style.css
   - script.js
   - README.txt
   - /images folder (with project images)
   - /assets folder (with icons/logos)

3. Go to repository Settings > Pages

4. Under "Source", select "main" branch and "/ (root)" folder

5. Click "Save"

6. Your site will be available at:
   https://[your-username].github.io/[repository-name]/


OPTION 2: Netlify
-----------------

1. Create account at https://www.netlify.com

2. Drag and drop the PORTOFOLIO folder to Netlify dashboard

3. Or connect your GitHub repository for automatic deployments

4. Your site will be live immediately with a custom URL


OPTION 3: Vercel
----------------

1. Create account at https://vercel.com

2. Import your GitHub repository

3. Deploy with default settings

4. Your site will be live with a custom URL


LOCAL DEVELOPMENT
----------------

1. Open index.html in a web browser

2. Or use a local server:
   
   Python 3:
   python -m http.server 8000
   
   Node.js (with http-server):
   npx http-server
   
   VS Code Live Server extension:
   Right-click index.html > Open with Live Server


CUSTOMIZATION GUIDE
-------------------

COLORS:
- Primary Blue: #2563eb (var(--primary-blue))
- Secondary Blue: #3b82f6 (var(--secondary-blue))
- Accent Cyan: #06b6d4 (var(--accent-cyan))
- Edit colors in :root section of style.css

FONTS:
- Primary: Inter (from Google Fonts)
- Mono: Roboto Mono (from Google Fonts)
- Change in style.css :root section

CONTENT:
- Update personal information in index.html
- Modify project descriptions and links
- Add/remove skills in Skills section
- Update contact information

IMAGES:
- Add project images to /images folder
- Update image paths in HTML if needed
- Recommended size: 800x600px for project images


ADDING PROJECT IMAGES
---------------------

1. Place images in /images folder
2. Update project-card divs in index.html:
   Replace:
   <div class="project-placeholder">
       <span class="project-icon">📊</span>
   </div>
   
   With:
   <img src="images/your-image.jpg" alt="Project description">


CHART CUSTOMIZATION
-------------------

Charts are created using Chart.js in script.js:
- Modify data arrays to update chart values
- Change chart types (line, bar, doughnut, etc.)
- Customize colors in datasets
- Adjust animation settings


CONTACT FORM
------------

The contact form currently uses mailto: links to open the user's email client.
To use a backend service:

1. Replace form submission handler in script.js
2. Add your backend endpoint URL
3. Update form action attribute in index.html


BROWSER SUPPORT
---------------

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)


PERFORMANCE OPTIMIZATION
------------------------

- Images: Compress images before uploading (use tools like TinyPNG)
- Fonts: Already loaded from Google Fonts CDN
- Charts: Chart.js loaded from CDN
- Consider minifying CSS/JS for production


TROUBLESHOOTING
---------------

Charts not showing?
- Check browser console for errors
- Ensure Chart.js CDN is loaded (check network tab)
- Verify canvas elements exist in HTML

Animations not working?
- Check if elements have data-aos attributes
- Verify JavaScript is loaded correctly
- Check browser console for errors

Mobile menu not working?
- Ensure JavaScript is enabled
- Check for JavaScript errors in console
- Verify hamburger and nav-menu IDs exist

Form not submitting?
- Check browser console for errors
- Verify form has proper IDs
- Ensure JavaScript event listeners are attached


CREDITS
-------

- Chart.js: https://www.chartjs.org
- Google Fonts: Inter & Roboto Mono
- Design inspiration: Modern data science portfolios


LICENSE
-------

This portfolio template is created for Maajid Dhirottsaha.
Feel free to customize and use for your own portfolio.


CONTACT
-------

For questions or issues, contact:
- Email: Update in contact section
- GitHub: https://github.com/majojodeden
- Instagram: @mjeeed.d


Last Updated: 2024
================================================================================

