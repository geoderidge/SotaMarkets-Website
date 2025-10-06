
# Project Context: SotaMarkets Unattended Retail and Vending Machine Business

## 1. Project Overview
**Goal:** A minimal, modern multi-page static website for an unattended retail vending machine business. Primary purpose is lead generation and service display with strong SEO.

**Core Features:** 
- Contact information display
- Service/product showcase with images
- Contact form for lead capture
- Mobile-responsive design
- Location-based SEO targeting

**Target Audience:** high-traffic venue owners, managers, and facility operators of apartments, manufacturing facilities, gyms, offices, urgent cares, and related businesses in Apple Valley, Lakeville, Farmington, Burnsville, Rosemount, and Eagan - all within Minnesota.

## 2. Tech Stack
- **HTML5** - Semantic markup only
- **CSS** - Tailwind CSS v4 via CDN
- **JavaScript** - Vanilla JS for form handling and navigation highlighting
- **Hosting** - GitHub Pages with custom domain (sotamarkets.com - already purchased through NameCheap)
- **Forms** - Formspree (free tier)

## 3. Design Principles
**Style:** Minimal and modern
- Clean white space, professional typography
- Modern sans-serif fonts, subtle hover effects only
- High contrast for readability but not gaudy
- Consistent visual identity across all pages

**Color Palette:** 
- Brand colors from logo - #051b4d
- Neutral grays/whites as base
- High contrast for accessibility, but not gaudy

## 4. Project Structure
/
├── index.html # Homepage with hero & overview
├── services.html # Detailed service/product showcase
├── areas.html # Locations served / service areas
├── contact.html # Contact form & business info
├── assets/
│ ├── images/ # Logo and product images
│ └── js/
│   └── main.js # Form validation & nav highlighting
├── GEMINI.md
└── README.md

## 5. **CRITICAL: Shared Components Consistency**

**ALL pages must include identical:**

**Header Section:**
- Company logo (left-aligned, links to homepage)
- Horizontal navigation menu (right-aligned on desktop, hamburger on mobile)
  - Links: Home | Services | Areas Served | Contact
  - Active page should have distinct styling (bg-blue-600 text-white)
- Sticky header on scroll
- Mobile-responsive with hamburger menu toggle

**Footer Section:**
- Business name and tagline
- Contact info: Phone, Email, Service Area
- Copyright notice
- Social links (if applicable)
- Same styling across all pages

**Page Container:**
- Consistent max-width container (max-w-7xl mx-auto px-4)
- Uniform spacing between sections (py-16 or py-20)
- Same heading hierarchy (h1: text-4xl, h2: text-3xl, h3: text-2xl)

## 6. Page-Specific Requirements

**Homepage (index.html):**
- Hero section with value proposition and CTA button
- Services overview (3-column grid with icons/images)
- Benefits section (why choose us)
- CTA section driving to contact page

**Services (services.html):**
- Page title/hero
- Detailed product showcase (grid layout with 4-6 products)
- Each product: image, name, description, key features
- CTA to contact page

**Areas Served (areas.html):**
- Page title/hero
- Map or list of service locations
- Minnesota cities listed above focus
- Benefits by location type (gyms, offices, apartments, urgent care, offices, manufacturing, etc.)
- CTA to contact page

**Contact (contact.html):**
- Page title
- Contact form: name, email, phone, location type, message
- Business contact info sidebar
- Form validation and Formspree integration

## 7. Coding Standards

**HTML:**
- Use semantic HTML5 (header, nav, main, section, footer)
- Consistent class naming across pages
- All images have alt text
- Meta tags on every page (unique title/description per page)

**CSS/Tailwind:**
- Inline utility classes
- Custom CSS only in `<style type="text/tailwindcss">` if needed
- Mobile-first responsive (sm:, md:, lg:)
- Consistent spacing scale (use Tailwind defaults)

**JavaScript:**
- Vanilla JS only
- main.js loaded on necessary pages only
- Form validation on contact page only

## 8. Constraints
- No build process - direct GitHub Pages deployment
- Fast load time priority
- Consistent brand experience across all pages