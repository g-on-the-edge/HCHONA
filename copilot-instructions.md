# Copilot Instructions for HCHONA

## Project Overview
HCHONA is a guest information page for a La Crosse, Wisconsin rental property. The project provides guests with essential information including Wi-Fi credentials, smart lock instructions, checkout procedures, and host contact information through a modern, responsive web interface.

## Technology Stack
- **Frontend**: Pure HTML5 and CSS3 (no JavaScript frameworks)
- **Styling**: Inline CSS with modern CSS features (Grid, Flexbox, CSS Custom Properties)
- **Design**: Dark theme with glassmorphism effects and responsive design
- **Assets**: JPEG image (`house.JPEG`) and QR code placeholder

## Project Structure
```
/
├── index.html          # Main guest information page
├── house.JPEG          # Property image for hero section
├── README.md           # Project documentation
└── copilot-instructions.md  # This file
```

## Coding Standards

### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Keep accessibility in mind (alt text, ARIA labels where needed)
- Use descriptive class names that follow BEM-like conventions where applicable

### CSS
- Keep all styles in the `<style>` tag within the HTML file (no external stylesheets)
- Use modern CSS features (Grid, Flexbox, custom properties)
- Follow mobile-first responsive design principles
- Use descriptive class names (e.g., `.card`, `.hero`, `.badge`)
- Maintain consistent spacing and visual hierarchy
- Prefer relative units (rem, em, %) over fixed pixels where appropriate

### Design Principles
- **Color Scheme**: Dark theme with blues and purples (`#0f172a`, `#1f2937`, `#38bdf8`, `#6366f1`)
- **Typography**: System fonts for optimal performance
- **Responsive**: Mobile-first approach with breakpoint at 768px
- **Effects**: Subtle glassmorphism, gradients, and shadows for depth
- **Accessibility**: Maintain sufficient color contrast and readable font sizes

## Task Guidelines

### Preferred Tasks
- UI/UX improvements to the guest information page
- Responsive design enhancements
- Accessibility improvements
- Content updates (Wi-Fi, instructions, contact info)
- Visual polish and styling refinements
- Documentation updates

### Constraints
- **Keep it simple**: This is a single-page static site with no backend
- **No frameworks**: Avoid adding JavaScript libraries or CSS frameworks
- **Performance**: Keep the page lightweight and fast-loading
- **Self-contained**: All styles should remain in the HTML file unless there's a compelling reason to split them
- **Minimal dependencies**: No build tools, no package managers needed

### Content Considerations
- Guest-facing content should be clear, concise, and welcoming
- Instructions should be easy to follow for non-technical users
- Maintain the friendly, professional tone throughout
- Placeholder values (like phone numbers, QR codes) should be clearly marked

## Testing Guidelines
- Test responsive design at common breakpoints (mobile: 375px, tablet: 768px, desktop: 1024px+)
- Verify in multiple browsers (Chrome, Safari, Firefox)
- Check color contrast for accessibility (WCAG AA compliance)
- Validate HTML structure
- Test on actual mobile devices when possible

## Output Format
When making changes:
1. Explain what changes you're making and why
2. Consider the impact on mobile and desktop views
3. Maintain the existing visual design language
4. Preserve the welcoming, guest-friendly tone
5. Test your changes if possible

## Context for AI Assistants
This is a guest information website for a short-term rental property. The primary users are guests who need quick access to essential information during their stay. The page should be:
- **Immediately useful**: Key information (Wi-Fi, door code) should be easy to find
- **Visually appealing**: Professional design that reflects the quality of the property
- **Mobile-friendly**: Many guests will view this on their phones
- **Low-maintenance**: Easy for the host to update without technical knowledge
