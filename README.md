# Kyle Ortzow - Portfolio

A clean, professional portfolio website showcasing my computer science projects, skills, and experience. Built with vanilla HTML/CSS for maximum performance and simplicity.

## Features

- **Responsive Design** - Mobile-first approach with breakpoints for tablet and desktop
- **Fast Loading** - No frameworks, minimal dependencies, optimized assets
- **Clean Architecture** - Organized file structure with separation of concerns
- **Modern CSS** - CSS Grid, Flexbox, CSS Variables for maintainability
- **SEO Friendly** - Semantic HTML, proper meta tags, accessibility best practices

## Project Structure

```
kyleortzow-portfolio/
├── index.html                      # Main portfolio page
├── projects/                       # Individual project pages
│   ├── canvas-notion-sync.html    # Canvas–Notion Sync project
│   ├── mtg-search-agent.html      # MTG Search Agent project
│   └── mtgtag.html                # MTGTag project
├── src/
│   ├── css/                       # Stylesheets
│   │   ├── variables.css          # CSS custom properties (colors, spacing)
│   │   ├── global.css             # Global styles and reset
│   │   ├── components.css         # Component-specific styles
│   │   └── responsive.css         # Media queries and responsive design
│   └── assets/
│       └── resume/                # Resume PDF and other documents
│           └── kyle_ortzow_resume.pdf
├── package.json                   # Project metadata and scripts
├── vercel.json                    # Vercel deployment configuration
└── README.md                      # This file
```

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid, Flexbox, Variables
- **No JavaScript** - Pure HTML/CSS for simplicity and performance
- **Vercel** - Deployment and hosting

## Design System

### Color Palette

The site uses a nature-inspired color scheme defined in `src/css/variables.css`:

- **Slate Grey** (`#7C8B92`) - Secondary text, borders
- **Dim Grey** (`#6D766E`) - Subtle accents
- **Charcoal Brown** (`#303A2C`) - Primary text
- **Granite** (`#455944`) - Hover states, emphasis
- **Dusty Olive** (`#6D764F`) - Primary brand color, CTAs
- **Cream** (`#f5f4f1`) - Card backgrounds
- **Light Background** (`#f9f8f6`) - Page background

### Typography

- **Font Family** - System fonts (`-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `Roboto`)
- **Font Sizes** - Fluid typography from 0.75rem to 3.5rem
- **Line Height** - 1.2 for headings, 1.6 for body text

## Development

### Local Development

Run a local server to preview the site:

```bash
# Using Python 3
npm run dev

# Or manually
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

### File Organization

- **CSS Modularization** - Styles are split into logical files for better maintainability
- **Component-Based** - Each UI component has dedicated styles
- **No Duplication** - Shared styles are centralized, no repeated code

## Deployment

### Deploy to Vercel

#### Option 1: Vercel Dashboard (Recommended)

1. Go to https://vercel.com and sign in
2. Click "New Project"
3. Import from GitHub: `kyleortzow-portfolio`
4. Configuration:
   - Framework Preset: **Other**
   - Build Command: (leave empty)
   - Output Directory: (leave empty)
5. Click **Deploy**

#### Option 2: Vercel CLI

```bash
npm install -g vercel
vercel login
vercel
```

### Deployment Configuration

The `vercel.json` file configures:
- Long-term caching for CSS and assets (1 year)
- Proper headers for static files
- Optimal performance settings

## Performance

- **Page Size** - Minimal HTML/CSS, no JavaScript
- **Load Time** - Sub-2-second page loads
- **Caching** - Aggressive caching for static assets
- **CDN** - Vercel's global CDN for fast delivery

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT License - See LICENSE file for details

## Contact

**Kyle Ortzow**
- Email: kortzow@gmail.com
- GitHub: [@KyleOrtzow1](https://github.com/KyleOrtzow1)
- LinkedIn: [kyle-ortzow](https://www.linkedin.com/in/kyle-ortzow/)
- Phone: +1 (510) 362-4688
- Location: San Francisco, CA

## Acknowledgments

Built with thoughtful design and clean code.
