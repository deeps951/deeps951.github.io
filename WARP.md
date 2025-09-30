# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is Andrew's personal website/portfolio repository, hosted on GitHub Pages at `deeps951.github.io`. The project showcases Andrew's work as a web developer, musician, and former flying instructor based on Australia's Gold Coast.

## Repository Structure

The repository contains multiple website versions and prototypes:

- **Main Site** (`index.html`) - Primary Bootstrap 5-based personal website
- **HTML Version** (`htmlversion/`) - Simplified vanilla HTML/CSS version
- **Living Colour** (`livingcolour/`) - Client project for interior design business
- **Bulma Test** (`rt/`) - Experimental version using Bulma CSS framework
- **Assets** - Images, stylesheets, and scripts organized in respective directories

## Key Technologies

- **Frontend Framework**: Bootstrap 5.3.3 (CDN)
- **Styling**: Custom CSS with Bootstrap overrides, natural color palettes
- **Fonts**: Saira Extra Condensed for headings, Muli for body text
- **Deployment**: GitHub Pages (static hosting)
- **Version Control**: Git with main branch deployment

## Common Development Commands

### Local Development
```bash
# Serve the site locally (various options)
python -m http.server 8000
# or
php -S localhost:8000
# or use Live Server extension in VS Code
```

### Git Workflow
```bash
# Standard workflow for updates
git add .
git commit -m "descriptive message"
git push origin main  # Automatically deploys to GitHub Pages
```

### File Management
```bash
# Create new project folders
mkdir new-project && cd new-project

# Optimize images (recommended before adding)
# Use online tools or imageoptim for compression

# Check repository status
git status
git log --oneline -10
```

## Architecture and Design Patterns

### Main Website Structure
The primary `index.html` follows a single-page application pattern with:
- Hero section with full-viewport background image
- About, Experience, and Skills sections in Bootstrap container
- Responsive grid system for content layout
- Inline JavaScript for dynamic year updates

### Styling Architecture
- Bootstrap 5 as base framework with custom CSS overrides
- CSS custom properties (variables) for consistent theming
- Color scheme inspired by natural palettes and human body tones
- Responsive design with mobile-first approach

### Content Strategy
- Personal branding emphasizes creativity, technical skills, and unique background
- Professional experience spans flying instruction, music production, and web development
- Photography and visual elements are carefully curated to reflect personality

### Project Organization
Each subdirectory represents a different project or version:
- Standalone HTML files for quick prototyping
- Shared asset directories when possible
- Client projects maintain separate branding and styles

## Development Guidelines

### Adding New Projects
1. Create project directory in root
2. Include standalone `index.html` with project-specific styling
3. Maintain consistent folder structure (`css/`, `js/`, `images/` when needed)
4. Update main portfolio if project should be featured

### Image Management
- Store images in `images/` directory with descriptive filenames
- Optimize for web (< 500KB for hero images, < 100KB for profile images)
- Use WebP format when possible for better compression
- Maintain aspect ratios suitable for responsive design

### Code Style
- Use semantic HTML5 elements
- Prefer external CSS files for substantial styling
- Keep JavaScript minimal and functional
- Comment complex CSS rules and custom properties
- Maintain consistent indentation (2 spaces)

### Deployment Process
- All changes to `main` branch automatically deploy to GitHub Pages
- Test locally before pushing to avoid broken deployments
- Monitor deployment status in repository Actions tab

## Notable Features

### Bootstrap Customizations
- Custom primary color: `#bd5d38` (warm orange-brown)
- Modified button styles and form elements
- Custom hero section with overlay effects
- Typography hierarchy using Google Fonts integration

### Multi-Version Architecture
The repository maintains multiple complete website versions rather than using a build system. This allows for:
- Rapid prototyping without affecting main site
- Client project development within same repository
- Framework experimentation (Bootstrap vs Bulma vs vanilla CSS)
- Easy rollback to previous versions if needed

### Asset Organization
- Images are centralized but projects can have local assets
- CSS follows component-based organization even without a build system
- JavaScript is minimal and primarily inline for simplicity

## Testing and Quality Assurance

### Browser Compatibility
Test across major browsers, especially:
- Chrome/Edge (primary)
- Safari (Mac users)
- Mobile browsers (responsive design critical)

### Performance Considerations
- Monitor CDN availability for Bootstrap/fonts
- Optimize images before committing
- Keep external dependencies minimal
- Test loading speed on slower connections

### Content Validation
- Verify contact information accuracy
- Update portfolio pieces regularly
- Maintain consistency in personal branding
- Check for typos in all content sections

## Client Project Integration

The `livingcolour/` directory demonstrates client work integration:
- Separate branding and color schemes
- Professional service business layout
- Contact information and portfolio showcase
- Audio element integration for ambiance

When adding similar client projects:
- Create isolated directory structure
- Maintain client-specific assets and styling
- Document project scope in commit messages
- Consider privacy implications of client work display