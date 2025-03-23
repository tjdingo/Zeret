# System Patterns

## Architecture Overview
The Zeret Architecture website follows a classic static website architecture with HTML, CSS, and minimal JavaScript. The site uses a component-based approach to CSS organization and maintains consistent styling patterns across pages.

## File Structure
```
Zeret/
├── assets/
│   ├── css/
│   │   ├── main.css          # Core styles and layout
│   │   ├── components.css    # Reusable UI components
│   │   └── responsive.css    # Media queries for responsive design
│   ├── js/
│   │   └── main.js           # Global JavaScript functionality
│   └── images/
│       ├── hero/             # Hero section background images
│       └── projects/         # Project portfolio images
├── cline_docs/               # Documentation files
├── *.html                    # Main page templates
```

## Design Patterns

### Navigation
- Fixed header with logo, navigation links, and mobile hamburger menu
- Active state indication for current page
- New horizontal divider below navigation

### Layout
- Container-based layout with max-width and centered content
- Section-based page structure with consistent vertical spacing
- CSS variables for color definitions and reuse

### UI Components
- Hero sections with overlay text on background images
- Cards for projects and services with hover effects
- Form elements with consistent styling
- Call-to-action sections with prominent buttons
- Footer with multi-column layout

### Typography
- Montserrat for primary typography (headings and body text)
- Libre Baskerville for special text elements
- Consistent heading hierarchy (h1-h4)
- Typographic scale with defined sizes

### Color System
```css
:root {
    --deep-navy: #1A2639;     /* Primary dark color */
    --forest-green: #3F6C51;  /* Primary accent color */
    --medium-green: #4A7F61;  /* Secondary accent color */
    --light-stone: #D6D5C9;   /* Light neutral color */
    --off-white: #F2F2F2;     /* Background color */
    --charcoal: #2C3A47;      /* Dark text color */
    --warm-cream: #E8E4D9;    /* Alternate light color */
}
```

## Reuse Patterns
- Section headings with consistent styling and decorative underline
- Button styles with primary and secondary variants
- Grid layouts for services, portfolio items, and other collections
- Consistent spacing using standard margin and padding values

## Responsive Design
- Mobile-first approach with breakpoints for larger screens
- Flexible grid layouts that adapt to screen sizes
- Navigation that collapses to hamburger menu on mobile
- Image sizing that scales appropriately for viewport
