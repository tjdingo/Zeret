# Technical Context

## Technologies Used

### Frontend
- **HTML5**: Structure and semantic markup
- **CSS3**: Styling and layout
  - Custom properties (CSS variables) for theming
  - Flexbox and Grid for layouts
  - Media queries for responsive design
- **JavaScript**: Minimal client-side interactions
  - Form validation and submission handling
  - Portfolio filtering functionality
  - Mobile menu toggle

### Assets
- **SVG Graphics**: Used for icons, logos, and some decorative elements
- **Web Fonts**: Google Fonts (Montserrat, Libre Baskerville)
- **Vector Images**: Project illustrations and hero backgrounds

## Build & Deployment
The website uses a straightforward static site approach without a build process:
- No preprocessors like Sass or Less
- No bundlers or transpilers
- Direct file editing and deployment
- GitHub Pages deployment via repository: https://github.com/tjdingo/Zeret

## Browser Support
- Modern evergreen browsers (Chrome, Firefox, Safari, Edge)
- Basic support for older browsers with graceful degradation
- Responsive design supporting mobile, tablet, and desktop viewports

## Performance Considerations
- Optimized SVG images for projects and hero sections
- Minimal JavaScript to reduce page weight
- No external dependencies beyond Google Fonts
- Efficient CSS with reusable components

## Technical Debt & Constraints
- Manual HTML updates required across pages for global changes
- Limited form functionality without backend processing
- No content management system for easy updates
- Basic JavaScript without framework benefits

## Development Environment
- Local development with direct file editing
- Browser testing for cross-platform compatibility
- Git version control with GitHub repository: https://github.com/tjdingo/Zeret
- Manual deployment process

## Future Technical Considerations
- Potential server-side form handling
- Possible integration with a static site generator for easier maintenance
- Image optimization for further performance improvements
- Enhanced project portfolio with filtering and search capabilities
