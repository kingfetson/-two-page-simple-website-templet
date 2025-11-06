# Business Issue Overview Website

A clean, fast-loading two-page website built with pure HTML5 and CSS. No frameworks, no images, no dependencies—just semantic markup and responsive design.

## File Structure

```
website/
├── index.html          # Homepage - Mission statement and who you are
├── overview.html       # Issue Overview - Detailed information
├── styles.css          # Single stylesheet for both pages
└── README.md           # This file
```

## How to Deploy to GoDaddy

1. **Access your GoDaddy hosting account**
   - Log in to GoDaddy
   - Navigate to your hosting control panel (cPanel)

2. **Upload files**
   - Open File Manager in cPanel
   - Navigate to the `public_html` folder (or `www` folder)
   - Upload all three files: `index.html`, `overview.html`, and `styles.css`
   - If you want the site in a subdirectory, create a folder first, then upload there

3. **Set permissions**
   - Ensure files have read permissions (644 is standard)
   - This is usually set automatically

4. **Test your site**
   - Visit your domain (e.g., `https://yourdomain.com`)
   - Both pages should load instantly

## How to Update Content

### Updating the Homepage (index.html)

1. Open `index.html` in any text editor (Notepad, TextEdit, VS Code, etc.)

2. **Company Name**: Find and replace "Company Name" with your actual company name (appears in multiple places)

3. **Tagline**: Replace `Brief tagline describing your core purpose` with your actual tagline

4. **Who We Are**: Replace the placeholder text in the first section with your organization description

5. **Why We Exist**: Update this section to explain your fundamental purpose

6. **What We Do**: Describe your approach and services

7. **Contact Information**: Update email and phone number in footer

### Updating the Issue Overview Page (overview.html)

1. Open `overview.html` in your text editor

2. Work through each section, replacing bracketed placeholder text:
   - **The Challenge**: Explain the problem you address
   - **Current State of Affairs**: Describe the current situation
   - **Key Facts**: Replace with your specific data points (add or remove fact paragraphs as needed)
   - **Our Approach**: Detail your methodology
   - **Why This Matters**: Explain the broader implications
   - **The Path Forward**: Outline next steps

3. Update contact information in the footer (same as homepage)

### Modifying Styles (styles.css)

The CSS file is well-commented. Common changes:

- **Colors**: Search for hex codes like `#3498db` (blue) or `#2c3e50` (dark blue-gray) and replace throughout
- **Fonts**: Modify the `font-family` in the `body` style
- **Spacing**: Adjust `padding` and `margin` values
- **Max width**: Change `max-width: 800px` in `.container` to make content wider/narrower

## Content Tips

- **Keep it concise**: This design works best with focused, scannable content
- **Use short paragraphs**: 2-4 sentences maximum for easy reading
- **Add sections**: Copy and paste the `<section class="section">` block to add more sections
- **Remove sections**: Delete any section you don't need
- **Maintain hierarchy**: Keep h1 for page titles, h2 for section headings

## Accessibility Features

- Semantic HTML5 markup
- Proper heading hierarchy (h1 → h2)
- Sufficient color contrast ratios
- Focus states for keyboard navigation
- Responsive meta viewport tag
- Alt-text ready (for if you add images later)

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (all versions from 2020+)
- Firefox (all versions from 2020+)
- Safari (all versions from 2020+)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **Load time**: Typically under 0.5 seconds
- **Page size**: ~15KB total (HTML + CSS combined)
- **Requests**: Only 3 HTTP requests total
- **Mobile-friendly**: Fully responsive, no separate mobile version needed

## Adding More Pages

To add a third page:

1. Copy `overview.html` and rename it (e.g., `about.html`)
2. Update the content inside
3. Add a link to the navigation in all three HTML files:
   ```html
   <a href="about.html" class="nav-link">About</a>
   ```

## Backup Recommendation

Before making major changes:
1. Download current versions of all files
2. Save them in a dated folder on your computer
3. Make changes to copies first
4. Test locally if possible
5. Upload when satisfied

## Support

For basic HTML/CSS help: [W3Schools](https://www.w3schools.com)  
For GoDaddy hosting help: [GoDaddy Support](https://www.godaddy.com/help)

---

**Last Updated**: November 2025  
**Version**: 1.0
