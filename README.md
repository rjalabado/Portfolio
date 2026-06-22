# RJ Alabado - Software Developer Portfolio

A modern, responsive portfolio website showcasing my software development projects and skills.

## 🌟 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Project Sections**: Dedicated areas for school projects and work projects
- **Interactive Elements**: Smooth scrolling, hover effects, and navigation highlighting
- **Professional Presentation**: Detailed project pages with technical specifications

## 🚀 Projects Showcased

### School Projects
- **Bokjab Chat**: Android chat application with weather integration
- **Aimlab 2.0**: Web-based aim training game

### Personal/Work Projects
- **Amazon Bot**: Automated purchasing assistant using Python and Selenium

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Modern CSS Grid, Flexbox, Custom Properties
- **Animations**: CSS Transitions, Intersection Observer API
- **APIs**: Pointer Lock API, Web Audio API
- **Design**: Responsive design principles, Mobile-first approach

## 📁 File Structure

```
Portfolio/
├── index.html              # Main portfolio page
├── styles.css              # Main stylesheet
├── script.js               # Interactive JavaScript
├── Bokjab_Chat.html        # Bokjab Chat project details
├── Amazon_Bot.html         # Amazon Bot project details
├── Aimlab_2.html          # Aimlab 2.0 project details
├── images/                 # Project images and assets
└── README.md              # This file
```

## 🎨 Design Features

- **Color Scheme**: Professional purple gradient with clean whites and grays
- **Typography**: Modern font stack with proper hierarchy
- **Layout**: CSS Grid and Flexbox for responsive layouts
- **Cards**: Elevated project cards with hover effects
- **Navigation**: Sticky navigation with smooth scrolling

## 📱 Responsive Design

The portfolio is fully responsive and includes:
- Mobile-optimized navigation
- Flexible grid layouts
- Scalable images and typography
- Touch-friendly interactive elements

## 🔗 Live Links

- **LinkedIn**: [Ruelito Alabado](https://www.linkedin.com/in/ruelito-alabado-894423158/)
- **GitHub**: [rjalabado](https://github.com/rjalabado)
# RJ Alabado — Software Developer Portfolio

A concise, professional portfolio showcasing selected projects, technical skills, and recent work highlights.

**Features**

- **Responsive design**: Optimized for desktop, tablet, and mobile.
- **Clean UI**: Professional layout with subtle transitions and clear hierarchy.
- **Project pages**: Focused technical summaries for each project with implementation notes.
- **Accessible interactions**: Smooth scrolling and keyboard-friendly navigation.

**Projects**

The site consolidates school, personal, and professional work under a single `Projects` section. Key pages include:

- `Eversource.html` — Client dashboards (two production sites delivered; see recent updates).
- `Microsoft_SDET.html` — Test engineering and validation work.
- `Varo.html` — Android/Kotlin project details.
- `Bokjab_Chat.html` — Android chat application project.
- `Amazon_Bot.html` — Personal automation project.
- `Aimlab_2.html` — Web-based aim-training project.

**Technologies**

- Frontend: HTML5, CSS3, JavaScript
- Styling: CSS Grid, Flexbox, CSS Custom Properties
- Tooling & infra referenced on project pages: Azure (App Service, AD, Key Vault, Application Insights), Redis, Playwright + TypeScript for test automation
- Note: `Eversource.html` references `Azure CLI` in its tech tags

**Recent site updates (this repository)**

- Removed informal / emoji language across pages and tightened copy for a professional tone.
- Merged separate "School" and "Personal/Work" project lists into a single `Projects` section on `index.html` and removed the previous "Future Projects" placeholder.
- Added an `AI-Assisted Development` skill chip to the main about/skills area on `index.html`.
- Footer year is now dynamic — `script.js` sets the year at runtime (`document.getElementById('year').textContent = new Date().getFullYear();`).
- `Eversource.html` now documents delivery of two client sites and includes both live links: `https://www.masssavedata.com/` and `https://www.ctenergydashboard.com/`.
- Added wording to `Eversource.html` describing the delivery approach: "Maintained a single modular repository for both client sites, reusing shared sections and components while supporting client-specific configuration." 
- Consolidated and simplified the SDET page (`Microsoft_SDET.html`) into a single "Testing Strategy and Validation" section.
- Minor style update: contact link/button styling adjusted in `styles.css` for a filled primary appearance.

**Repository file overview**

```
Portfolio/
├── index.html
├── styles.css
├── script.js
├── Eversource.html
├── Microsoft_SDET.html
├── Varo.html
├── Bokjab_Chat.html
├── Amazon_Bot.html
├── Aimlab_2.html
├── images/
└── archived/
```

**Links**

- LinkedIn: https://www.linkedin.com/in/ruelito-alabado-894423158/
- GitHub: https://github.com/rjalabado
- Email: rjalabado@gmail.com

**Development / Local preview**

To preview locally, serve the site from a simple HTTP server (do not open files directly in some dev tools):

```bash
# from the repository root
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

**Notes & next steps**

- Verify visual layout locally after serving the site (images and CSS load correctly when served over HTTP).
- Consider a short accessibility sweep and a final content sanity-check to confirm no missed references.

Footer year is generated at runtime by `script.js`.

© Ruelito (RJ) Alabado Jr. All rights reserved.
