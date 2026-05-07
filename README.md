# Portfolio Bootstrap 3

A versatile professional portfolio showcasing expertise in web development, videography, and digital marketing.

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" />
  <img src="https://img.shields.io/badge/Bootstrap-3.3.7-563D7C.svg" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E.svg" />
  <a href="LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
</p>

## Description

Portfolio Bootstrap 3 is a high-performance, single-page personal branding platform designed for creatives and developers. Built on the reliable Bootstrap 3 framework, it provides a seamless user experience across all devices. The project integrates modern interactive elements such as particle backgrounds and dynamic typing effects to create a compelling first impression. It serves as a comprehensive digital resume, highlighting professional skills, service offerings, career milestones, and a curated gallery of work.

## Features

- **Responsive Architecture** - Fully optimized for mobile, tablet, and desktop viewing using the Bootstrap grid system
- **Interactive Visuals** - Engaging user interface featuring Particles.js background and Typed.js animations
- **Dynamic Content Sliders** - Integrated Owl Carousel for showcasing blog posts and client testimonials
- **Professional Skill Tracking** - Visual progress bars to demonstrate proficiency in various technical and creative domains
- **Chronological Timeline** - Structured education and experience sections to outline professional growth
- **Filtered Portfolio Gallery** - Organized project showcase with category filtering and Magnific Popup integration
- **Fast Performance** - Lightweight static structure ensures rapid loading times and smooth navigation

## Tech Stack

- **Frontend Framework**: Bootstrap 3
- **Scripting**: JavaScript (ES6), jQuery
- **Animations**: Particles.js, Typed.js
- **UI Components**: Owl Carousel 2, Magnific Popup
- **Icons**: Linea Icons, Font Awesome 5
- **Typography**: Google Fonts (Kaushan Script, Open Sans)
- **Styling**: Vanilla CSS3

## Installation Guide

### Prerequisites

- A modern web browser
- A local web server (optional, but recommended for some features)
- Git installed on your system

### Steps

1. Clone the repository to your local machine

```bash
git clone https://github.com/reynaldiarya/Portfolio-Bootstrap-3.git
```

2. Navigate to the project directory

```bash
cd Portfolio-Bootstrap-3
```

3. Open the project in your browser
You can simply open `index.html` directly or use a local server like Live Server in VS Code.

```bash
# Example using Python's built-in server
python -m http.server 8000
```

4. Access the site at `http://localhost:8000`.

## Configuration

The portfolio is designed to be easily customizable via configuration files and standard HTML attributes.

### Particle Background
The background behavior is controlled via `particles.json`. You can modify particle density, color, and interaction speed in this file.

### Metadata
Update the following tags in `index.html` for SEO optimization:

| Tag | Location | Purpose |
|----------|-------------|---------|
| `description` | `<head>` | Search engine snippet |
| `keywords` | `<head>` | SEO indexing terms |
| `title` | `<head>` | Browser tab title |

### Typing Animation
Modify the strings in the script block at the bottom of `index.html` to change the animated titles.

```javascript
var typed5 = new Typed("#typed5", {
  strings: ["Web Developer", "Photographer", "Designer"],
  // ... configuration
});
```

## Usage

### Personalizing Content

1. **Profile Information**: Update the headings and paragraphs in the `#home` and `#about` sections of `index.html`.
2. **Skills**: Adjust the `width` percentage in the `.progress-bar` elements to reflect your expertise levels.
3. **Portfolio Items**: Add or remove items in the `#mix-container` div. Ensure the `data-filter` class matches the filter categories.
4. **Media Assets**: Replace images in the `images/` directory with your own. Maintain the recommended aspect ratios for the best visual results.

### Deploying to Production

This project is ready for static hosting. You can deploy it directly to:
- GitHub Pages
- Netlify
- Vercel
- Standard shared hosting via FTP

## Project Structure

```text
/
├── css/              # Minified and custom stylesheets
├── images/           # Image assets including avatars and portfolio thumbnails
├── js/               # Vendor libraries and custom scripts
├── linea/            # Linea icon font files and styles
├── index.html        # Main entry point and structural markup
├── particles.json    # Configuration for background animations
├── LICENSE           # MIT License details
└── README.md         # Project documentation
```

## Scripts / Commands

While this is a static project, the following utilities are used within the environment:

| Tool | Purpose |
|---------|-------------|
| `typed.min.js` | Handles the typewriter effect on the hero section |
| `particles.js` | Manages the interactive background particles |
| `scripts.min.js`| Contains theme-specific logic and initialization |
| `validator.min.js`| Handles contact form validation logic |

## Contributing

Contributions are welcome to improve the template. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Improve specific component'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for detailed terms and conditions.

## Author

Reynaldi Arya