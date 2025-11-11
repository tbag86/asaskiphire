# ASA Skips - Project Documentation

## Business Information

**Company:** ASA Skips
**Service:** Skip Hire in Tameside
**Phone:** 07828131272
**Address:** 53 Repton Avenue, Hyde, Cheshire, SK14 2LG
**Website:** Running on local server at http://localhost:8000/index.html

---

## Current Services & Pricing

### Skip Hire Only (Rubbish Removal & Waste Consultation REMOVED)

1. **2 Yard Skip - Mini**: £140
2. **4 Yard Skip - Midi**: £180
3. **8 Yard Skip - Ton Bags**: £280

**All prices include up to 1 week hire. Extra time available - call for quote.**

---

## Areas Covered

Hyde, Oldham, Saddleworth, Ashton-under-Lyne, Stalybridge, Dukinfield, Denton, Droylsden, Audenshaw, Mossley, Glossop, Marple, Hattersley, Mottram

**Note:** Areas section is positioned BELOW contact form, ABOVE footer (user's specific request)

---

## File Structure

```
ASA-Skips/
├── index.html                 # Main website (formerly index-premium.html)
├── tameside-skips.svg         # Company logo
├── images/                    # Gallery images folder
│   ├── WhatsApp Image 2025-11-11 at 14.33.09 (2).jpeg  # Gallery 1
│   ├── WhatsApp Image 2025-11-11 at 14.33.09.jpeg      # Gallery 2
│   ├── WhatsApp Image 2025-11-11 at 14.33.11.jpeg      # Gallery 3
│   ├── WhatsApp Image 2025-11-11 at 14.33.14 (1).jpeg  # Gallery 4
│   ├── WhatsApp Image 2025-11-11 at 14.33.17.jpeg      # Gallery 5
│   └── WhatsApp Image 2025-11-11 at 14.33.25.jpeg      # Gallery 6
├── README.md                  # General documentation
├── DESIGN-COMPARISON.md       # Design rationale (legacy)
└── PROJECT-NOTES.md          # This file - complete project reference
```

---

## Website Sections (In Order)

1. **Header** - Black background, white "ASA SKIPS" text, tameside-skips.svg logo
2. **Hero** - Gradient mesh background, pricing card showing £140 starting price
3. **Gallery 1** - "Our Work in Action" - 3 images showcasing service
4. **Services** - 3 skip hire cards with pricing (£140, £180, £280)
5. **Testimonials** - Customer reviews
6. **About** - Company information and features
7. **FAQ** - 8 accordion-style questions
8. **Gallery 2** - "Trustworthy, Prompt Service" - 3 different images
9. **Contact Form** - Callback request with skip size dropdown
10. **Areas Covered** - Grid of service areas
11. **Footer** - Updated services links (2 Yard - £140, 4 Yard - £180, 8 Yard - £280)

---

## Design Features (Award-Winning Style)

### Visual
- **Gradient mesh background** with floating animated orbs
- **Glassmorphism effects** (frosted glass cards with backdrop blur)
- **Premium typography** (Inter + Space Grotesk fonts)
- **Gradient text effects** on keywords
- **Dark background** (#000000 header, #0A0E27 sections)

### Brand Colors
- Primary Yellow: #FFC527
- Deep Blue: #1e306e
- Bright Blue: #267ECE
- Dark BG: #0A0E27
- Accent Purple: #7C3AED

### Animations
- Floating orbs in hero (20s & 15s loops)
- Floating card animation on price display
- Hover transformations (cards lift 12px with shadows)
- Gradient transitions on area items
- Gallery image zoom + overlay slide-up on hover
- FAQ accordion with smooth expand/collapse

### Accessibility
- ✅ WCAG AA compliant contrast ratios
- ✅ White text on dark backgrounds (no black on blue)
- ✅ Proper focus states with glowing borders
- ✅ Semantic HTML structure

---

## Gallery Images (6 Total)

### Top Gallery: "Our Work in Action"
1. **WhatsApp Image 2025-11-11 at 14.33.09 (2).jpeg** - Truck with skip
2. **WhatsApp Image 2025-11-11 at 14.33.09.jpeg** - Skip being lifted (action shot)
3. **WhatsApp Image 2025-11-11 at 14.33.11.jpeg** - Multiple skips showing variety

### Bottom Gallery: "Trustworthy, Prompt Service"
4. **WhatsApp Image 2025-11-11 at 14.33.14 (1).jpeg** - Professional truck
5. **WhatsApp Image 2025-11-11 at 14.33.17.jpeg** - Multiple skip options
6. **WhatsApp Image 2025-11-11 at 14.33.25.jpeg** - Clean skip with branding

---

## Key Changes History

### Session 1 - Initial Build
- Created award-winning design with glassmorphism
- Implemented gradient mesh backgrounds
- Added skip hire services (£100, £80, £50)
- Black header with white text
- Added tameside-skips.svg logo
- Added gallery with animations
- Added FAQ section (8 questions)
- Fixed £ icon (was $)

### Session 2 - Major Service Update
- ✅ **REMOVED** Rubbish Removal service (was £80)
- ✅ **REMOVED** Waste Consultation service (was £50)
- ✅ **UPDATED** to Skip Hire only with new pricing:
  - 2 Yard Mini: £140
  - 4 Yard Midi: £180
  - 8 Yard Ton Bags: £280
- ✅ Added "up to 1 week hire included" messaging
- ✅ Added Saddleworth to areas covered (Oldham already existed)
- ✅ **MOVED** Areas section below Contact Form, above Footer
- ✅ Updated hero pricing card to show £140 starting price
- ✅ Updated contact form dropdown to show skip sizes instead of services
- ✅ Updated footer services links to match new pricing
- ✅ Replaced all 6 gallery images with real photos from images/ folder
- ✅ Renamed index-premium.html to index.html (now main site)

---

## Technical Stack

- **Pure HTML/CSS/JavaScript** (no frameworks)
- **Google Fonts**: Inter (body), Space Grotesk (headings)
- **SVG Icons**: Material Design style
- **CSS Features**: Grid, Flexbox, backdrop-filter, background-clip
- **JavaScript**: IntersectionObserver for scroll reveals, FAQ accordion
- **Server**: Python 3 SimpleHTTPServer on port 8000

---

## Contact Form Configuration

**Dropdown Options:**
```html
<option value="2-yard-mini">2 Yard Skip - Mini (£140)</option>
<option value="4-yard-midi">4 Yard Skip - Midi (£180)</option>
<option value="8-yard-tonbags">8 Yard Skip - Ton Bags (£280)</option>
```

**Form Fields:**
- Full Name (required)
- Phone Number (required)
- Postcode (required)
- Service Required / Skip Size (required)
- Additional Information (optional)

**CTA:** "Request Callback" + "Or call us directly: 07828131272"

---

## FAQ Topics

1. What skip sizes are available?
2. How long can I hire a skip for?
3. Do I need a permit for a skip?
4. What items cannot go in a skip?
5. Can I get same-day delivery?
6. How is waste disposed of?
7. How do I book a skip?
8. Which areas do you cover?

---

## Future Reference Notes

### Important User Preferences
- User is "a big critic of claude's web design ability" - maintain high standards
- No emojis - use professional SVG icons only
- Clean, modern, award-winning aesthetics
- Real photos preferred over illustrations
- Accessibility is important (proper contrast ratios)

### Do NOT Mention
- "Premium" version (this IS the only version now)
- Old pricing (£100, £80, £50)
- Rubbish removal or waste consultation services

### Always Remember
- Phone number: 07828131272 (appears in header, hero, contact, footer)
- Areas section goes BELOW contact form, ABOVE footer
- All prices are for "up to 1 week hire, extra time call for quote"
- Brand colors match ASA Plumbing (yellow #FFC527, blues)

---

## Running the Site Locally

```bash
# Start server
python3 -m http.server 8000

# View site
open http://localhost:8000/index.html

# Stop server
kill $(lsof -t -i:8000)
```

---

## Deployment Checklist

- [ ] Test all forms
- [ ] Verify all images load
- [ ] Check mobile responsiveness
- [ ] Test on Safari, Chrome, Firefox, Edge
- [ ] Verify phone number clickable on mobile
- [ ] Test FAQ accordion functionality
- [ ] Verify scroll animations work
- [ ] Check all links in footer
- [ ] Test contact form submission

---

*Last Updated: 2025-11-11*
*Current Status: Production-ready single-page website with 6 real gallery images*
