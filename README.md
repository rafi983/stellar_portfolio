# Rafi Zaman - Personal Web Developer Portfolio 🚀

Welcome to the central repository for Rafi Zaman's personal portfolio website! 

This is a sleek, highly-responsive, single-page professional portfolio meticulously built to showcase web development projects, showcase an extensive technical skills matrix, and present a professional background. The project implements a custom dark aesthetic blended with modern UI/UX principles, emphasizing a clean developer identity.

---

## ✨ Comprehensive Feature List

### 🎨 Design & UI
- **Custom Dark Theme:** The core UI boasts a deep dark background (`#1a1a1a`) contrasted brilliantly by striking cyan (`#00d2d3`) and light slate (`#6c757d`) highlights.
- **Parallax Galaxy Banner:** A beautiful, animated galaxy background spanning from the navigation bar seamlessly through the hero section with a fixed-attachment parallax scrolling effect.
- **Dynamic 'R' Logo:** The navigation bar features a completely CSS-built gradient logo, using dynamic hover states and text-fill clipping for a modern, lightweight branding touch.
- **Fully Responsive Navigation:** Implements Bootstrap 5's collapsing mobile hamburger menu to ensure seamless device scaling from 4K desktop to small mobile endpoints.
- **3D Neumorphic Shadows:** Advanced CSS `box-shadow` implementations give the contact section a unique glowing, physical structure.

### 📑 Core Sections
1. **Hero Intro:** A welcoming centralized introduction mapping out professional titles, integrated interactive FontAwesome social icons, and direct access to a downloadable PDF Resume.
2. **Featured Portfolio:** Neatly mapped Grid cards utilizing an "Image-Left / Description-Right" split structure. These cards display project snapshots using Bootstrap 5 Carousels to support multiple images per project, alongside descriptive feature lists, precise tech-stack badging (e.g., React, Node.js), and fully functional active links (Live Site & GitHub) opening seamlessly in new tabs.
3. **Skills & Expertise Array:** A robust data presentation categorizing developer strength into clear tiers: *Expertise, Comfortable, Familiar,* and *Tools*, rendering dynamic CSS-styled tech-tags next to educational credentials.
4. **Contact Gateway:** An interactive form styled to perfectly match the site's dark aesthetic, inviting users to reach out directly.

---

## 🛠️ Tech Stack & Architecture

This project is intentionally lightweight, avoiding JavaScript frameworks for maximum speed and simplicity.

- **HTML5:** Semantic HTML providing accessibility and clean page structuring.
- **CSS3:** Externalized styling located in `/css/style.css`, covering layout nuances, responsive queries, shadow generation, gradients, and custom logo drawing. 
- **Bootstrap 5 (v5.3.0):** Leveraged heavily via CDN for the underpinning flexbox grid, fluid container system, buttons, and navigation classes.
- **FontAwesome (v6.0.0):** Used exclusively for high-clarity SVGs across GitHub, LinkedIn, YouTube, and generic icon placements.

---

## 📁 Repository Structure

```text
Portfolio-Site/
├── css/
│   └── style.css            # Centralized styles governing themes and layouts
├── icons/
│   └── logo.png             # Legacy graphic logo (if graphical branding is preferred)
├── images/
│   ├── galaxy.gif           # The parallax animated banner background
│   └── rafi.jfif            # Profile picture used within the Hero section
├── projects-img/
│   ├── space-tourism.png    # Preview of the Space Tourism project
│   ├── slider1.png          # Secondary slider image for Space Tourism
│   ├── eschool.png          # Preview of the Online School project
│   └── slider2.png          # Secondary slider image for Online School
├── resume/
│   └── riz_v2.pdf           # Target PDF for the Resume download functionality
├── index.html               # The singular HTML core markup
└── README.md                # Project documentation
```

---

## 💻 Installation & Local Usage

Running this portfolio locally is incredibly straightforward:

1. **Clone the Repository:** 
   Download or clone the files to your local machine.
2. **Launch the Application:** 
   Navigate to the root directory and open `index.html` in any modern web browser (Edge, Chrome, Firefox, Safari).

### 🚨 Note on the Resume Download Feature
If you are directly opening the HTML file from your hard drive (`file:///C:/path/to/site`), modern web browsers enforce security protocols preventing forced unprompted downloads via the HTML `download` attribute. Instead, clicking the Resume button locally will open the PDF safely in a new tab. 
*Once you host this website on a live server (HTTP/HTTPS), the native "Download" functionality will work perfectly as intended.*

---

## 🔧 Customization Guide

Want to fork this and make it your own? 
- **Colors:** Open `css/style.css`. Run a Find & Replace for `#00d2d3` (Cyan) and replace it with your own hex color code. 
- **Profile Image:** Replace `rafi.jfif` inside the `/images` folder with your own square photo, then update the filename link inside the `<img class="profile-img">` tag in `index.html`.
- **Text:** Scroll through `index.html` to update the Title, Hero description, Education parameters, and Footer copyright dates.

---

## 🚀 Deployment

Since it is a fully static website, it can be deployed for **free** on multiple highly performant hosting services. Just point the specific service to this repository!

* **GitHub Pages**
* **Vercel**
* **Netlify**
* **Cloudflare Pages**
* **Firebase Hosting**

---

### 📝 License & Copyright
**Copyright © 2026 | Rafi Zaman**  
*Mymensingh, Bangladesh*  
All rights reserved.
