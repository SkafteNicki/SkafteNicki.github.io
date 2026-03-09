# Nicki Skafte Detlefsen - Personal Website

A Jekyll-based static website styled like a GitHub profile.

## Technologies

- Jekyll (static site generator)
- HTML/CSS
- GitHub Pages compatible

## Local Development

### Prerequisites

- Ruby 2.7+ installed
- Bundler gem installed (`gem install bundler`)

### Setup

```bash
# Clone the repository
git clone https://github.com/SkafteNicki/skafteNicki.github.io.git
cd skafteNicki.github.io

# Install dependencies
bundle install

# Start the development server
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## Deployment

This site is deployed automatically to GitHub Pages via GitHub Actions whenever changes are pushed to the main branch.

### Manual GitHub Pages Deployment

1. Push to the `main` branch
2. Go to Settings > Pages
3. Select "Deploy from a branch" and choose your branch
4. The site will be available at `https://skafteNicki.github.io`

## Project Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page templates
├── _includes/          # Reusable components
├── assets/
│   ├── css/            # Stylesheets
│   ├── images/         # Images
│   └── files/          # PDF files
├── index.html          # Main page (Overview)
├── publications.html   # Publications
├── teaching.html       # Teaching
├── projects.html      # Projects
├── cv.html            # CV
├── services.html      # Services/Hire Me
├── Gemfile             # Ruby dependencies
└── README.md
```

## Customization

### Updating Profile Information

Edit `_config.yml` to update:
- Name
- Email
- Location
- Organization
- GitHub username

### Adding Publications

Edit `publications.html` to add new publications. Follow the existing format with PDF, BibTeX, and code links.

### Updating Teaching Info

Edit `teaching.html` to update course information and student supervision lists.

## License

MIT License
