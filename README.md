# Kenechukwu Nwobu — Personal Portfolio

A single-page, responsive portfolio website built with semantic HTML5 and modern CSS (Flexbox + Grid). Dark navy + teal theme, mobile-first, no JavaScript required for core functionality.

**Live:** *(add your GitHub Pages / Netlify URL once deployed)*

## File Structure

```
kenechukwu_portfolio/
├── index.html            Main HTML file (all 7 sections)
├── css/
│   └── styles.css        Stylesheet (mobile-first, 2 breakpoints)
├── images/
│   ├── profile.jpg       Hero portrait
│   ├── about.svg         About section illustration
│   ├── project1.svg      Travel Agency preview
│   ├── project2.svg      Restaurant preview
│   ├── project3.svg      E-commerce preview
│   └── project4.svg      Portfolio preview
├── .gitignore
└── README.md
```

## Features

- Sticky navigation with hamburger menu on mobile (CSS-only, no JS)
- Smooth in-page scrolling (`scroll-behavior: smooth`) with scroll-padding for the sticky nav
- All 7 required sections: Nav, Hero, About, Skills, Projects, Contact, Footer
- CSS Grid for About, Skills, Projects, and Contact layouts
- Flexbox for navigation, buttons, social links, and footer
- Responsive breakpoints: 320–767 (mobile), 768–1023 (tablet), 1024+ (desktop)
- Google Fonts: Poppins (headings) + Inter (body)
- Font Awesome icons for skills and social links
- Hover effects, transitions, and focus states on form inputs
- Accessible: semantic tags, `alt` attributes, `aria-label`s on icon-only links

## How to View

Open `index.html` in any browser — double-click the file, or right-click → Open With → your browser. Test responsiveness with Chrome DevTools: right-click → Inspect → toggle the device toolbar (Ctrl+Shift+M / Cmd+Shift+M).

## Tech Stack

- HTML5 (semantic tags)
- CSS3 (custom properties, Flexbox, Grid, media queries)
- Google Fonts (Poppins, Inter)
- Font Awesome 6

---

Built as part of a 2-week CSS Personal Project assignment. © 2026 Kenechukwu Nwobu.
