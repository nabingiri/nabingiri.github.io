# Website

This is the personal website design.


## File Structure

```
├── index.html          # Main website file
├── stylesheet.css      # Styling and layout
├── CNAME              # Domain configuration for GitHub Pages
├── README.md          # This file
├── data/
│   ├── Giri_Nabin_CV.pdf                    # Curriculum Vitae
│   └── [Giri, Nabin]Dissertation_Defense.pdf # PhD Defense Slides
└── images/
    └── nabin_pic.png   # Profile photo
```

## Local Development

To test the website locally:

1. **Simple File Opening**:
   ```bash
   open index.html
   # or
   firefox index.html
   # or
   google-chrome index.html
   ```

2. **Local Server** (recommended):
   ```bash
   # Using Python
   python3 -m http.server 8000
   # Then visit: http://localhost:8000
   
   # Or using Node.js
   npx serve .
   # Then visit the provided URL
   ```

## Deployment

This website is configured for GitHub Pages deployment:

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```

2. **GitHub Pages Setup**:
   - Go to repository Settings -> Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save settings

3. **Custom Domain**:
   - The CNAME file configures the site for `nabingiri.io`
   - Ensure DNS is properly configured to point to GitHub Pages
   - GitHub will automatically handle SSL certificates

## Based on:

- **HTML5**: Semantic markup for accessibility and SEO
- **CSS3**: Modern styling with Flexbox and Grid
- **Google Fonts**: JetBrains Mono and Source Code Pro
- **Font Awesome**: Icons for social media links
- **GitHub Pages**: Free hosting and deployment

## Contact

For questions about this website or collaboration opportunities, please contact:
- **Website**: [nabingiri.github.io](https://nabingiri.github.io)

---


