# Replit Agent Task Spec — green_lantern_ink_website

## Instructions for Replit Agent
The index.html has been fully rebuilt with a complete tattoo studio site.
Your job is to add CSS (style.css) and enhance the JavaScript (script.js).
Commit all changes with prefix "replit: " and push to main when done.

## Current State After Rebuild
- index.html: Complete — hero, styles grid, 3 artist profiles, 8-item FAQ, booking form, contact
- style.css: Needs full CSS to match the site structure in index.html
- script.js: Needs scroll/nav enhancement

## Stack Rules
- Static HTML/CSS/JS only
- No Vercel — deploy on Cloudflare Pages

## CSS Variables to Use (style.css)
--black: #0a0a0a
--dark: #111111
--card: #1a1a1a
--green: #22c55e
--green-dim: rgba(34,197,94,0.15)
--white: #f5f5f5
--muted: #888888
--border: #2a2a2a
--font-display: Bebas Neue
--font-body: Inter

## Tasks

### 1. Write Full style.css
Implement all classes used in index.html:
- nav: fixed, 64px, backdrop-filter blur, border-bottom
- nav-logo: Bebas Neue, green accent on "Ink" span
- nav-links: flex, hidden on mobile
- nav-book: green CTA button
- nav-hamburger: visible only on mobile
- hero: 100vh, centered, radial green glow background
- hero-title: Bebas Neue, clamp(4rem, 12vw, 9rem), line-height 0.9
- btn-primary: green bg, black text, bold, uppercase
- btn-outline: border only, white text
- hero-badge: pill shape, dark card bg
- styles section: dark background
- styles-grid: CSS grid auto-fit minmax(260px, 1fr), 1.5px gap, border color bg for gap effect
- style-card: dark card bg, hover slightly lighter
- style-name: Bebas Neue, green color
- artists-grid: CSS grid auto-fit minmax(280px, 1fr)
- artist-card: border, rounded, hover border turns green
- artist-img: 1:1 aspect ratio, dark green gradient bg
- artist-img-placeholder: Bebas Neue, giant faded green letters
- style-tag: green pill badge
- faq section: dark background
- faq-grid: CSS grid auto-fit minmax(400px, 1fr)
- faq-item: left border green, padding-left
- booking section: centered, radial glow
- booking-title: Bebas Neue, clamp(3rem, 8vw, 6rem)
- booking-form: max-width 600px, centered
- form inputs/select/textarea: dark bg, border, white text, full width
- contact-grid: CSS grid auto-fit minmax(200px, 1fr)
- footer: flex space-between, border-top
- All responsive: mobile breakpoint at 768px (hide nav-links, show hamburger, stack grids)

### 2. Enhance script.js
Add:
- Scroll reveal: IntersectionObserver on elements with class "reveal" — adds "visible" on viewport entry (fade up transform)
- Nav shrink: after 100px scroll, add "scrolled" class to nav (reduce height to 48px, slightly more opaque bg)
- Active nav link: highlight current section link as user scrolls
- Mobile hamburger: toggle nav-links visibility on click, close on outside click
- Form success: after Formspree submit redirect or fetch, show "We will be in touch within 24 hours" message

### 3. Add Gallery Section (insert between artists and faq in index.html)
9-tile dark grid with style labels, then Instagram CTA button.
Each tile: dark green gradient, centered style name in Bebas Neue.
Styles to label: Blackwork, Fine Line, Traditional, Neo-Trad, Custom, Script, Cover-Up, Color, Portrait

### 4. SEO
Add to head: Open Graph tags (og:title, og:description, og:image placeholder, og:url)