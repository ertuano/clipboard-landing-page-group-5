# clipboard-landing-page-group-5
# Clipboard Landing Page – Group 5

![Clipboard Website Preview](images/preview-desktop.png)

**Live Demo:** [https://ertuano.github.io/clipboard-landing-page-group-5](https://ertuano.github.io/clipboard-landing-page-group-5)  
**Challenge by:** [Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-BKQm1uI4Z)  
**Coded by:** **Group 5 (10 Members)**

---clipboard-landing-page-group-5/
│
├── index.html
├── style.css
├── README.md
│
├── images/
│   ├── logo.svg
│   ├── image-computer.png
│   ├── image-devices.png
│   ├── icon-.svg
│   ├── logo-.png
│   ├── bg-header-mobile.png
│   ├── bg-header-desktop.png
│   └── favicon-32x32.png
│
└── .git/ (Git version control)
## How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/ertuano/clipboard-landing-page-group-5.git

# 2. Go to folder
cd clipboard-landing-page-group-5

# 3. Open in browser
start main.html    # Windows
open main.html     # macOS
xdg-open main.html # Linux

## Project Overview

A **fully responsive**, pixel-perfect **Clipboard landing page** built with **HTML & CSS**.  
Includes mobile & desktop layouts, hover effects, and smooth typography.

---

## Features

- **Responsive Design** (Mobile, Tablet, Desktop)  
- **Google Fonts** (`Bai Jamjuree`)  
- **Hover Effects** on buttons & links  
- **iOS & Mac Download Buttons**  
- **Social Media Icons**  
- **Clean, Semantic HTML**  
- **Modern CSS (Flexbox, Media Queries)**  

---

## File Structure
Tech Stack

HTML5
CSS3 (Flexbox, Media Queries)
Google Fonts
Git & GitHub (Collaboration)


Development Workflow

Pull latest: git pull origin main
Create branch: git checkout -b yourname-task
Edit files
Commit: git commit -m "yourname: did X"
Push: git push -u origin yourname-task
Create Pull Request on GitHub
Leader merges to main


Screenshots
Desktop View
<img src="images/preview-desktop.png" alt="Desktop">
Mobile View
<img src="images/preview-mobile.png" alt="Mobile">

Challenges Faced & Solved
Issue,Solution
Images not loading,                    Fixed paths: images/image-devices.png
Footer not responsive,                Used @media queries
Buttons too small on mobile      ,Increased padding & font size
Git conflicts,                                      Used git pull before editing


What We Learned

Git collaboration with 10 members
Responsive design with mobile-first
CSS hover effects & transitions
Teamwork using branches & PRs


Future Improvements

Add JavaScript for clipboard copy
Dark mode toggle
Animation on scroll
Deploy with Netlify/Vercel/* LOGOS */
.logos {
  display: flex;
  flex-direction: column;
  gap: 50px;
  align-items: center;
}
.logos img {
  width: 120px;
}

/* FOOTER */
footer {
  background: hsl(201, 11%, 95%);
  padding: 50px 20px;
  text-align: center;
}
.footer-logo {
  width: 60px;
  margin-bottom: 30px;
}
footer ul {
  list-style: none;
  margin-bottom: 40px;
}
footer ul li {
  margin: 12px 0;
}
footer ul li a {
  color: hsl(210, 10%, 33%);
  text-decoration: none;
  font-size: 1rem;
}
footer ul li a:hover {
  color: hsl(171, 66%, 44%);
}
.social a {
  margin: 0 10px;
}
.social img {
  width: 24px;
  filter: brightness(0) saturate(100%) invert(50%);
}
.social img:hover {
  filter: brightness(0) saturate(100%) invert(40%) sepia(80%) hue-rotate(140deg);
}

/* DESKTOP STYLES */
@media (min-width: 768px) {
  body {
    background-image: url('images/bg-header-desktop.png');
  }
  .btn-group {
    flex-direction: row;
    justify-content: center;
  }
  .snippets-grid {
    flex-direction: row;
    text-align: left;
    align-items: center;
    gap: 80px;
  }
  .computer-img {
    margin: 0;
    transform: translateX(-40px);
  }
  .snippets-text {
    flex: 1;
  }
  .workflow-grid {
    flex-direction: row;
    justify-content: center;
    gap: 30px;
    text-align: center;
  }
  .workflow-grid > div {
    flex: 1;
    max-width: 300px;
  }
  .logos {
    flex-direction: row;
    justify-content: space-between;
    max-width: 1000px;
    margin: 0 auto;
  }
  footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    text-align: left;
  }
  footer ul {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    margin: 0;
  }
  .social {
    margin-left: auto;
  }
}