# Replit Agent Task: green_lantern_ink_website

## Goal
Rebuild the Green Lantern Ink website from its current minimal HTML/CSS/JS stub into a professional tattoo studio site with a full artist portfolio gallery, embedded Calendly booking, and an atmospheric dark aesthetic that reflects NYC tattoo culture.

## Tasks
1. Redesign index.html as a single-page scrollable site with sections: Hero → About → Artists → Portfolio Gallery → Booking → FAQ → Footer (or keep multi-page with smooth nav — choose what's cleaner)
2. **Hero section**: full-viewport dark background (#0d0d0d) with green neon accent (#39FF14 — lantern green), studio name in bold condensed font (Bebas Neue via Google Fonts), tagline "Custom Ink. NYC Legacy.", and a "Book Your Session" CTA that scrolls to booking
3. **About section**: studio history paragraph (2–3 sentences, placeholder), 3 value icons (Custom Designs, Sterile Environment, 10+ Years Experience), a high-contrast photo placeholder of the shop interior
4. **Artists section**: 3 artist cards — each with a circular profile photo placeholder, artist name, specialties (e.g., "Japanese Traditional, Blackwork"), Instagram handle with link, and "View Portfolio" button
5. **Portfolio Gallery**: masonry or CSS grid of 18 tattoo image placeholders (use Unsplash dark art/tattoo images), organized by style tags: Traditional, Neo-Traditional, Blackwork, Geometric, Realism; add a filter bar at the top to filter by tag
6. **Booking section**: embed a Calendly inline widget using the placeholder URL `https://calendly.com/greenlanternink` — add a fallback message "Contact us directly at greenlanternink@gmail.com if booking isn't loading"; surround with a dark card with "Schedule Your Consultation" heading
7. **FAQ section**: 5 questions (Does it hurt? How much does a tattoo cost? How do I prepare? What's the healing process? Do you do walk-ins?) with CSS accordion expand/collapse — no JS library
8. **Footer**: studio address placeholder (Brooklyn, NY), phone, email, Instagram link, copyright
9. **Style**: dark background (#0d0d0d), green neon accent (#39FF14), white body text, Bebas Neue headings, Inter body font — atmospheric, not garish; subtle green glow on hover states
10. Ensure mobile-first responsive design, hamburger nav on mobile, touch-friendly gallery (pinch-zoom optional but not required)
11. Add SEO meta tags: title "Green Lantern Ink | Custom Tattoo Studio — Brooklyn NYC", description, OG image

## Tech Stack
- Vanilla HTML5 / CSS3 / JavaScript (keep existing stack, no build tool)
- Google Fonts: Bebas Neue + Inter
- Calendly embed (inline widget script)
- CSS Grid / Flexbox
- CSS accordion for FAQ (no jQuery)

## Deploy Target
Cloudflare Pages (static site). Never Vercel.

## Done When
- [ ] All 7 sections render correctly on desktop and mobile
- [ ] Artist cards display with profile photo, name, specialties, and Instagram link
- [ ] Portfolio gallery shows 18 images with working style filter buttons
- [ ] Calendly booking widget embedded and visible in booking section
- [ ] FAQ accordion opens/closes on click without JavaScript libraries
- [ ] Dark neon aesthetic consistent across all sections
- [ ] Mobile nav hamburger works on 375px viewport
- [ ] SEO meta tags and OG tags present in <head>
- [ ] No console errors on load
