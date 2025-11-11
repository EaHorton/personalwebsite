# Personal Website

A Hugo-based personal website showcasing research, projects, and professional experience.

## Site Structure

This Hugo site includes four main pages:

- **Home** (`/`) - Welcome page and introduction
- **Research** (`/research/`) - Research interests, publications, and projects  
- **CV** (`/cv/`) - Curriculum vitae with education, experience, and achievements
- **Projects** (`/projects/`) - Portfolio of personal and professional projects

## Getting Started

### Prerequisites

Make sure you have Hugo installed on your system. You can download it from [gohugo.io](https://gohugo.io/installation/).

### Running the Site Locally

1. Navigate to the project directory:
   ```bash
   cd /Users/eahorton/personal_website/personalwebsite
   ```

2. Start the Hugo development server:
   ```bash
   hugo server -D
   ```

3. Open your browser and visit `http://localhost:1313`

### Building for Production

To build the static site for deployment:

```bash
hugo
```

This will generate the site in the `public/` directory.

## Customization

### Content

- Edit the markdown files in the `content/` directory to update your personal information
- Update `content/_index.md` for the home page
- Update `content/research.md` for your research information
- Update `content/cv.md` for your curriculum vitae
- Update `content/projects.md` for your projects

### Site Configuration

- Edit `hugo.toml` to update site title, description, menu items, and other settings
- Update the `baseURL` to match your deployment URL

### Styling

- The CSS is located in `themes/personal/static/css/style.css`
- Modify colors, fonts, and layout as needed
- The theme is fully responsive and mobile-friendly

### Navigation

The navigation menu is automatically generated from the menu configuration in `hugo.toml`. To add or modify menu items, edit the `[[menu.main]]` sections.

## Deployment

This site can be deployed to:

- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

For GitHub Pages deployment, make sure to update the `baseURL` in `hugo.toml` to match your GitHub Pages URL.

## Theme Features

- Clean, professional design
- Fully responsive layout
- Mobile-friendly navigation
- SEO-optimized
- Fast loading
- Accessible markup

## File Structure

```
personalwebsite/
├── content/
│   ├── _index.md       # Home page
│   ├── research.md     # Research page
│   ├── cv.md           # CV page
│   └── projects.md     # Projects page
├── themes/personal/
│   ├── layouts/        # HTML templates
│   └── static/         # CSS and assets
├── hugo.toml           # Site configuration
└── README.md           # This file
```

## License

This project is open source and available under the MIT License.