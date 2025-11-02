clipboard-landing-page-group-5/
├── main.html
├── style2.css
├── README.md
└── image/
    ├── logo.svg
    ├── image-computer.png
    ├── image-devices.png
    ├── icon-blacklist.svg
    ├── icon-facebook.svg
    ├── icon-instagram.svg
    ├── icon-preview.svg
    ├── icon-text.svg
    ├── icon-twitter.svg
    ├── logo-google.png
    ├── logo-hp.png
    ├── logo-ibm.png
    ├── logo-microsoft.png
    ├── logo-vector-graphics.png
    ├── bg-header-mobile.png
    ├── bg-header-desktop.png
    ├── preview-desktop.png
    ├── preview-mobile.png
    └── favicon-32x32.png
   ** How to Run Locally **
# 1. Clone the repository
git clone https://github.com/ertuano/clipboard-landing-page-group-5.git

# 2. Navigate to the project folder
cd clipboard-landing-page-group-5

# 3. Open in your default browser
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
Development Workflow (For Team Members)
bash# Always start with the latest code
git pull origin main

# Create a new branch for your feature
git checkout -b yourname/feature-name

# Make your changes (edit HTML/CSS/images)

# Stage and commit
git add .
git commit -m "yourname: added X / fixed Y"

# Push your branch
git push -u origin yourname/feature-name

# Open a Pull Request on GitHub → Leader reviews & merges to main

Screenshots
Desktop View
<img src="images/preview-desktop.png" alt="Desktop Preview" width="100%">
Mobile View
<img src="images/preview-mobile.png" alt="Mobile Preview" width="350">
**Challenges Faced & Solutions**
Issue,Solution
Images not loading,    Fixed paths to images/filename.png (added leading folder)
Footer not responsive,  Used Flexbox with @media queries for desktop alignment
Buttons too small on mobile,  "Increased padding, font-size, and used min-height"
Git conflicts,           Resolved by git pull --rebase and clear communication in PRs
Background image cutoff,       Adjusted background-position and used separate mobile/desktop images

**What We Learned**

Effective Git collaboration with 10+ members using branches & PRs
Mobile-first responsive design
Advanced CSS hover effects & transitions
Team coordination via GitHub Issues & Discussions
Importance of consistent file naming and folder structure


Thank you for visiting!
Made with 💻 and ☕ by Group 5
Frontend Mentor Challenge Completed ✅
