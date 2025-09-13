# Prakhar Arya - Portfolio Website

A modern, responsive portfolio website built with Jekyll for GitHub Pages deployment.

## Features

- 🎨 Modern dark theme with gradient accents
- 📱 Fully responsive design
- ⚡ Optimized for GitHub Pages
- 🚀 Fast loading with external CSS/JS files
- 🔍 SEO optimized with Jekyll SEO plugin
- 📊 GitHub stats integration
- 🎯 Smooth scrolling navigation

## File Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Base layout template
├── assets/
│   ├── css/
│   │   └── style.scss   # Compiled styles
│   └── js/
│       └── main.js      # Interactive features
├── index.html           # Main portfolio page
├── Gemfile              # Ruby dependencies
└── .gitignore           # Git ignore rules
```

## Local Development

1. Install Ruby and Bundler
2. Run `bundle install` to install dependencies
3. Run `bundle exec jekyll serve` to start development server
4. Visit `http://localhost:4000` in your browser

## GitHub Pages Deployment

1. Push all files to your GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source as "Deploy from a branch" -> "main" branch
4. Your site will be available at `https://yourusername.github.io/repository-name`

## Troubleshooting Jekyll Build Issues

The original error "Is a directory @ apply2files - /github/workspace/_site/assets" was caused by:

1. **Inline CSS conflicts**: Moved all styles from `<style>` tags to `assets/css/style.scss`
2. **Missing front matter**: Added Jekyll front matter with `---` to SCSS file
3. **Improper asset handling**: Created proper `assets/` directory structure
4. **Layout conflicts**: Separated HTML structure into `_layouts/default.html`

## Key Changes Made

- ✅ Extracted inline CSS to `assets/css/style.scss` with Jekyll front matter
- ✅ Moved JavaScript to `assets/js/main.js` 
- ✅ Added Jekyll configuration in `_config.yml`
- ✅ Created proper layout structure in `_layouts/default.html`
- ✅ Added Jekyll front matter to `index.html`
- ✅ Configured GitHub Pages compatible plugins
- ✅ Added proper `.gitignore` for Jekyll

## Technologies Used

- Jekyll (Static Site Generator)
- SCSS (CSS Preprocessing)
- Font Awesome (Icons)
- GitHub Pages (Hosting)
- Responsive CSS Grid & Flexbox
- Intersection Observer API (Animations)

## Contact

- GitHub: [@PrakharArya-Rex](https://github.com/PrakharArya-Rex)
- LinkedIn: [prakhar-arya](https://www.linkedin.com/in/prakhar-arya-9aa777212/)
- LeetCode: [prakhararya](https://leetcode.com/u/prakhararya/)