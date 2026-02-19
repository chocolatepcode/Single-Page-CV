# Single Page CV

A clean, professional single-page CV (Curriculum Vitae) built with semantic HTML5 and minimal CSS.

## Project Overview

This project creates a responsive, single-page CV that follows best practices for:
- Semantic HTML structure
- SEO optimization
- Open Graph (OG) tags for social media sharing
- Accessibility standards

## Features

✅ **Semantic HTML5** - Uses proper HTML5 semantic elements (`<main>`, `<header>`, `<section>`, `<article>`, `<address>`, `<time>`)
✅ **SEO Ready** - Includes meta description, keywords, author, and robots tags
✅ **Social Media Optimized** - Open Graph tags for better sharing on LinkedIn, Facebook, etc.
✅ **Responsive Design** - Clean layout that works on all device sizes
✅ **Print Friendly** - Designed to look great when printed or saved as PDF
✅ **Accessible** - ARIA labels and semantic structure for screen readers

## Project Structure

```
single-page-cv/
├── src/
│   ├── index.html    # Main CV page
│   └── favicon.svg   # Site favicon
├── cv.png           # Design reference
├── requirements.txt # Project requirements
├── .gitignore       # Git ignore rules
└── README.md        # This file
```

## Getting Started

### View the CV

1. Open `src/index.html` in your web browser
2. Or use a local server:
   ```bash
   cd src
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

### Customize Your CV

1. Open `src/index.html` in your text editor
2. Replace the placeholder content:
   - **Name**: Replace "Your Name" with your actual name
   - **Contact Info**: Update address, phone, email
   - **Skills**: List your technical skills
   - **Education**: Add your educational background
   - **Experience**: Detail your work history with achievements
   - **Social Links**: Add your LinkedIn and GitHub URLs

3. Update meta tags in the `<head>` section:
   - `meta name="description"` - Your personal description
   - `meta name="author"` - Your name
   - Open Graph tags for social sharing

4. Update the favicon (optional):
   - Replace `src/favicon.svg` with your own SVG icon
   - Or add additional favicon formats (PNG, ICO)

### Print/Save as PDF

The CV is designed to be print-friendly. To save as PDF:

1. Open the page in your browser
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Select "Save as PDF"
4. Choose appropriate paper size (A4 or Letter)
5. Enable "Background graphics" for colors

## Technical Details

### HTML Structure

The CV uses semantic HTML5 elements:
- `<main>` - Main content container
- `<header>` - Name and contact information
- `<section>` - Skills, Education, Experience sections
- `<article>` - Individual education and work entries
- `<address>` - Contact information (styled as normal text)
- `<time>` - Date ranges with datetime attributes
- `<h1>`, `<h2>`, `<h3>` - Proper heading hierarchy

### SEO & Meta Tags

```html
<!-- SEO Meta Tags -->
<meta name="description" content="...">
<meta name="keywords" content="...">
<meta name="author" content="...">

<!-- Open Graph Tags -->
<meta property="og:title" content="...">
<meta property="og:description" content="...">
<meta property="og:type" content="profile">
```

### Styling

CSS is embedded in the HTML for a single-file solution:
- Clean, modern typography
- Responsive layout (max-width: 800px)
- Color-coded sections (green headings, blue links)
- Print-friendly styling

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Deployment

This is a static HTML file that can be deployed anywhere:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the `src` folder
- **Vercel**: Connect your Git repository
- **Any web server**: Upload `src/index.html` and `src/favicon.svg`

## Credits

This project was created as part of a frontend development learning roadmap, focusing on semantic HTML and best practices for CV/resume websites.

## License

This project is open source and available for personal use.
