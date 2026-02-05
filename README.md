# Artist Portfolio Website

This is your complete artist portfolio website with an immersive artwork presentation feature.

## Files Included

- `index.html` - Main gallery and portfolio page
- `artwork-detail.html` - Immersive scrolling artwork detail page

## How to Deploy to Netlify

1. **Download this entire folder** to your computer
2. Go to https://app.netlify.com/drop
3. **Drag the entire "artist-website" folder** onto the Netlify Drop page
4. Your site will be live instantly with a URL like: `random-name-123.netlify.app`

## Customization Guide

### Main Gallery Page (index.html)

1. **Replace "YOUR NAME"** in the navigation (line 232)
2. **Update contact details** (lines 567-569)
3. **Replace artwork images**: Change the image URLs in the `src` attributes
4. **Add more artworks**: Copy and paste an `<a class="artwork-card">` section

### Detail Page (artwork-detail.html)

1. **Replace the main image**: Update the image URL on line 380
2. **Adjust zoom focus points**: Edit the `data-zoom`, `data-x`, and `data-y` attributes:
   - `data-zoom`: Zoom level (1 = normal, 2 = 2x zoom)
   - `data-x`: Horizontal focus (0-100, 50 = center)
   - `data-y`: Vertical focus (0-100, 50 = center)
3. **Edit text descriptions**: Update the content in each `<div class="text-overlay">` section
4. **Add/remove sections**: Copy entire `<section class="scroll-section detail-section">` blocks

### Creating More Detail Pages

To create detail pages for other artworks:
1. Copy `artwork-detail.html` and rename it (e.g., `artwork-2.html`)
2. Update the image and text content
3. In `index.html`, update the artwork card link to point to your new page

## Adding a Custom Domain

After deploying to Netlify:
1. Buy a domain from Namecheap, Google Domains, or similar
2. In Netlify dashboard, go to Domain Settings
3. Follow Netlify's instructions to connect your domain

## Need Help?

- Images not loading? Make sure the image URLs are valid
- Links not working? Check that file names match exactly (case-sensitive)
- Contact form not working? You'll need to add a backend service like Netlify Forms or Formspree

---

Created with Claude - Ready to showcase your art to the world!
