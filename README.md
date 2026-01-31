# Resume Website

A professionally designed single-page resume website with modern design and responsive layout.

## 📁 Project Structure

```
Resume/
├── resume-singlepage/         # Single-page version
│   ├── index.html             # All content on one page
│   └── css/
│       └── style.css          # Stylesheet
│
└── README.md                  # This file
```

## 🎨 Features

✅ **Modern, Professional Design**
- Clean typography and color scheme
- Smooth animations and transitions
- Professional gradient hero section
- Card-based layouts

✅ **Responsive Design**
- Works perfectly on desktop, tablet, and mobile
- Flexible grid layouts
- Touch-friendly navigation

✅ **Comprehensive Sections**
- Hero section with CTA buttons
- About me section
- Key highlights/metrics
- Professional experience
- Skills & expertise (Leadership, Technical, Core)
- Education & certifications
- Contact form and social links

✅ **Interactive Features**
- Sticky navigation bar with active indicators
- Smooth scrolling (single-page only)
- Hover effects on cards
- Form validation

## 🚀 Getting Started

### Best For:
- Quick overview of your profile
- Shareable resume URL
- Fast loading
- Modern single-page portfolio

### Navigation:
- Smooth scroll navigation
- All content on one page
- Auto-highlighting of current section in navbar

### How to Use:
1. Open `resume-singlepage/index.html` in your browser
2. Update the content with your information
3. All sections are clearly marked with IDs for easy editing
4. Customize colors in `css/style.css`

## 🎨 Customization

### Update Your Information:
1. **Name & Title**: Change in hero section
2. **About**: Update the "About Me" section content
3. **Experience**: Add/remove experience items
4. **Skills**: Update skill categories and cards
5. **Education**: Add your degrees and certifications
6. **Contact**: Update email, phone, location, and social links

### Customize Colors:
Edit the CSS variables at the top of `css/style.css`:
```css
:root {
    --primary-color: #2c3e50;      /* Main dark color */
    --secondary-color: #3498db;    /* Accent blue */
    --accent-color: #e74c3c;       /* Red accent */
    --light-bg: #ecf0f1;           /* Light background */
    /* ... more colors ... */
}
```

### Common Changes:
- Change font: Modify `font-family` in body styles
- Update button style: Edit `.btn-primary` and `.btn-secondary` classes
- Adjust spacing: Modify padding values in sections
- Change typography size: Update `font-size` values in headings

## 📱 Mobile Optimization

Fully responsive design with:
- Mobile-first design approach
- Tablet and desktop breakpoints
- Flexible navigation menu
- Optimized touch targets
- Readable font sizes on all devices

## 🔗 Linking Your Resume PDF

The website supports a PDF download button. To link your resume:

1. Place your PDF file (`Resume_AnirudhaDhopate.pdf`) in the root directory
2. Update the href in the button:
   ```html
   <a href="Resume_AnirudhaDhopate.pdf" target="_blank">Download Resume</a>
   ```
3. Or update the path if your PDF is in a different location

## 🌐 Deployment

### GitHub Pages (Recommended):
1. Create a GitHub repository
2. Push your files to the repo
3. Enable GitHub Pages in settings
4. Your site will be live at: `https://yourusername.github.io/Resume`

### Other Options:
- Netlify: Drag & drop your folder
- Vercel: Connect your GitHub repo
- Any web hosting: Upload files via FTP

## 📋 Customization Checklist

- [ ] Update your name and current position
- [ ] Update "About Me" section
- [ ] Add your work experience
- [ ] List your skills
- [ ] Add education and certifications
- [ ] Update contact information
- [ ] Add social media links
- [ ] Update email address
- [ ] Link your resume PDF
- [ ] Customize colors if desired
- [ ] Test on mobile devices
- [ ] Deploy to your hosting

## 🔧 Browser Compatibility

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile browsers

## 📝 Tips

1. **Keep content concise** - Use bullet points for readability
2. **Use action verbs** - Start experience descriptions with strong verbs
3. **Add metrics** - Include numbers and achievements
4. **Update regularly** - Keep your resume fresh with recent accomplishments
5. **Test the form** - Set up email service for contact form (consider Formspree or similar)

## 🤝 Contact Form Setup

The contact form is currently a template. To make it functional, you can:

1. **Formspree** (Recommended - Easy):
   - Update form action: `action="https://formspree.io/f/YOUR_ID"`
   
2. **Email service** (Alternative):
   - Use services like Basin, Getform, or Netlify Forms
   - Follow their setup instructions

## 📄 License

Feel free to use this template for your personal resume website!

---

**Need help?** Check the code comments and customize as needed. Both versions use clean, semantic HTML for easy modification.
