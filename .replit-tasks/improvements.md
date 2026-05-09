# Replit Agent Task: green_lantern_ink_website

## Goal
Build a premium tattoo studio website for Green Lantern Ink with an artist portfolio gallery, online booking system, and about/FAQ sections — dark and artistic aesthetic.

## Tasks
1. Build a cinematic hero section: full-viewport dark background with dramatic typography, studio name "Green Lantern Ink", tagline, and "Book a Session" CTA
2. Create an Artists section: profile cards for each tattoo artist with photo placeholder, name, specialty style (traditional, neo-trad, blackwork, realism, etc.), and a link to their portfolio
3. Build a Portfolio/Gallery section: masonry grid of tattoo photos organized by style — use high-quality placeholder images; implement a style filter (All / Traditional / Blackwork / Realism / Color / Fine Line)
4. Integrate online booking: embed Calendly or build a custom booking form (artist, style, date preference, description of tattoo idea, size, body placement) — submit to Supabase `booking_requests` table
5. Add an About section: studio story, location (NYC address placeholder), years in business, awards/recognition
6. Build a Care Instructions page (linked from nav): tattoo aftercare guide with illustrated steps
7. Add an FAQ section: 8-10 common questions (pricing, touch-ups, deposits, healing time, cover-ups)
8. Add a Reviews section: 5 real-feeling client reviews with star ratings
9. Implement smooth scroll navigation: Home, Artists, Gallery, Book, About, FAQ
10. Add structured data: JSON-LD for LocalBusiness (tattoo parlor) with address, phone, hours
11. Open Graph tags + custom favicon (green lantern icon SVG)
12. Full mobile responsiveness
13. Deploy to Cloudflare Pages

## Tech Stack
- React 18 + TypeScript (or plain HTML if repo is static)
- Vite (if React)
- Tailwind CSS
- Supabase (booking requests)
- Cloudflare Pages

## Deploy Target
Cloudflare Pages — connect `Kaoz625/green_lantern_ink_website`. Never Vercel.

## Done When
- [ ] Hero, Artists, Gallery, Booking, About, FAQ all built
- [ ] Gallery has working style filter tabs
- [ ] Booking form submits to Supabase
- [ ] JSON-LD LocalBusiness schema present
- [ ] Mobile-responsive at 375px
- [ ] All changes pushed to `Kaoz625/green_lantern_ink_website` main branch
