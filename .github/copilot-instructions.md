# AI Coding Agent Instructions

## Project Overview
**EuDecid** is an informatica "Atestat" (high school IT project) with a three-file structure:
- `Main.html`: Primary web application entry point
- `Design.css`: Styling for the web interface
- `README.md`: Project documentation

This is a web-based application project following a simple HTML + CSS pattern.

## Architecture & File Structure

### Current State
- **`Main.html`**: HTML structure for the application
- **`Design.css`**: Stylesheet for visual design and layout
- **No JavaScript files yet**: All functionality should be implemented in HTML/CSS initially

### Key Pattern
Follow a **separation of concerns** approach:
- HTML for semantic structure and markup
- CSS for presentation and styling
- Future JavaScript (if needed) for interactive behavior

## Development Conventions

### HTML Structure (`Main.html`)
- Use semantic HTML5 tags (`<header>`, `<main>`, `<nav>`, `<section>`, etc.)
- Each major component should be in a separate `<section>` or container
- Use descriptive `id` and `class` attributes for CSS targeting
- Example structure:
```html
<header id="main-header"><!-- Navigation --></header>
<main>
  <section class="feature-section"><!-- Content --></section>
</main>
<footer><!-- Footer content --></footer>
```

### CSS Conventions (`Design.css`)
- Use class-based selectors for styling (avoid inline styles)
- Organize CSS by component/section
- Use a color scheme defined at the top for consistency
- Responsive design: Include media queries for mobile-first approach

### Adding New Features
1. Add semantic HTML markup to `Main.html`
2. Define corresponding CSS classes/styling in `Design.css`
3. Ensure both files stay in sync during changes

## Build & Deployment
- No build system currently required (static site)
- Open `Main.html` directly in a browser to test
- Future: If JavaScript is added, consider a bundler or build process

## Testing
- Manual browser testing by opening `Main.html`
- Check CSS in browser DevTools to verify styling
- Test on multiple screen sizes for responsive design

## Common Tasks

### Updating Layout
1. Modify HTML structure in `Main.html` (add/change semantic tags)
2. Update corresponding styles in `Design.css`

### Styling Changes
- Always modify `Design.css`, never use inline styles
- Group related rules and add comments for major sections

### Adding Content
- Keep content semantic and well-structured in HTML
- Ensure accessibility (alt text, ARIA labels if needed)

---

**Last Updated:** December 2025
