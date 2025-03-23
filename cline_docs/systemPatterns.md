# System Patterns: Zeret Architecture Website

## Architecture Overview
The Zeret Architecture website follows a static site architecture, built with HTML, CSS, and JavaScript. This approach was chosen for its simplicity, performance, and ease of hosting.

## File Organization
```
/Zeret/
├── cline_docs/              # Memory Bank documentation
├── Guides/                  # Project guides and planning documents
│   ├── zeret-branding-guide.md
│   └── zeret-website-plan.md
├── Page Mockups/            # Design mockups in SVG format
│   ├── zeret-about-page.svg
│   ├── zeret-contact-page.svg
│   ├── zeret-homepage.svg
│   ├── zeret-portfolio-page.svg
│   ├── zeret-project-detail.svg
│   └── zeret-services-page.svg
├── Resources/               # Reference materials and content
│   ├── About — Teréz Villeda-Medina.pdf
│   ├── Teréz Villeda-Medina - Projects.pdf
│   └── ZA Planning and Design .pdf
├── images/                  # Image assets (to be created)
└── *.html                   # HTML pages (homepage exists, others to be created)
```

## Technical Patterns

### HTML Structure
- Semantic HTML5 elements (`header`, `nav`, `section`, `footer`, etc.)
- Clean, accessible markup
- Structured for SEO optimization
- Responsive design patterns
- Standard page templates for consistency

### CSS Approach
- CSS is currently embedded in the HTML (in `<style>` tags)
- Will be extracted to external CSS files as the project grows
- BEM naming convention recommended for CSS classes
- Mobile-first responsive design with breakpoints at:
  - Mobile: 320px - 767px
  - Tablet: 768px - 1023px
  - Desktop: 1024px - 1439px
  - Large Desktop: 1440px+

### JavaScript Usage
- Minimal JavaScript for essential functionality
- Vanilla JavaScript without frameworks
- Currently handles:
  - Mobile navigation toggle
  - Image slider/carousel
  - Smooth scrolling

### Color System
Based on the branding guide:
- Primary Colors:
  - Deep Navy: #1A2639
  - Forest Green: #3F6C51
  - Light Stone: #D6D5C9
  - Off-White: #F2F2F2
- Secondary Colors:
  - Medium Green: #4A7F61
  - Charcoal: #2C3A47
  - Warm Cream: #E8E4D9

### Typography System
- Primary Font: Montserrat (300, 400, 600, 700)
- Secondary Font: Libre Baskerville
- Font sizes follow a consistent scale
- Responsive typography adjustments

## Version Control Strategy
- GitHub repository for source code management
- Main branch for production-ready code
- Feature branches for new development
- Commit messages following conventional format

## Deployment Strategy (Proposed)
- GitHub Pages for hosting (static site)
- Alternatively could use Netlify or Vercel
- Manual deployment initially
- Potential for CI/CD pipeline later

## Future Patterns to Consider
- CSS preprocessing with Sass
- Image optimization workflow
- Build process with Webpack or Parcel
- Content management solution
