# ASA Skips Website

Professional one-page website for ASA Skips - Skip Hire in Tameside.

## Features

- **Modern Design**: Clean, professional design with brand colors matching ASA Plumbing
- **Fully Responsive**: Works perfectly on mobile, tablet, and desktop
- **Conversion-Focused**: Multiple CTAs for phone calls and callback requests
- **Fast Loading**: No external dependencies except Google Fonts
- **Professional Icons**: SVG icons throughout (no emojis)

## Sections

1. **Header**: Sticky navigation with logo and phone number
2. **Hero**: Eye-catching section with skip image and key benefits
3. **Services**: Three service cards with pricing (Skip Hire £100, Rubbish Removal £80, Waste Consultation £50)
4. **Areas Covered**: Grid of 18 areas in Tameside and surroundings
5. **Testimonials**: Customer reviews with 5-star ratings
6. **About**: Company information and features
7. **Contact Form**: Callback request form
8. **Footer**: Complete contact information and links

## Replacing Placeholder Elements

### Logo
The logo is currently a simple yellow square with "ASA" text. To replace it with your actual logo:
1. Find the logo section in the HTML (around line 767)
2. Replace the div with an `<img>` tag pointing to your logo file:
   ```html
   <img src="your-logo.png" alt="ASA Skips" style="width: 100%; height: 100%; object-fit: cover; border-radius: 8px;">
   ```
- Recommended size: 200x200px or larger
- Format: PNG with transparent background preferred

### Skip Image
The skip image in the hero section is currently an embedded SVG illustration. To replace with a real photo:
1. Find the hero-image section (around line 836)
2. Replace the entire `<svg>` tag with an `<img>` tag:
   ```html
   <img src="skip-photo.png" alt="Professional Skip Hire" style="max-width: 450px;">
   ```
- Recommended size: 800x600px or larger
- Format: PNG with transparent background works best for professional look

## Customization

### Colors
The website uses ASA Plumbing's brand colors:
- Primary Yellow: `#FFC527`
- Dark Background: `#222222`
- Deep Blue: `#1e306e`
- Bright Blue: `#267ECE`

To change colors, search for these hex codes in the CSS and replace them.

### Phone Number
The phone number `07828131272` appears multiple times. To change it:
1. Search for `07828131272` in the HTML file
2. Replace all instances with your new number

### Content
All content can be edited directly in the HTML file:
- Hero text: Line ~703
- Services: Line ~767
- Areas: Line ~866
- Testimonials: Line ~895
- About: Line ~928
- Contact form: Line ~972

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- No external JavaScript libraries
- Optimized CSS
- Fast loading times
- SEO-friendly markup

## Contact

For any questions or modifications, contact the web development team.
