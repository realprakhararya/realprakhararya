# Prakhar Arya - Portfolio Website

A modern, responsive portfolio website built with Jekyll for GitHub Pages deployment.

## Features
- Fast loading with external CSS/JS files
- SEO optimized with Jekyll SEO plugin

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
4. Visit `http://localhost:4000` in browser

## Key Changes Made

- Extracted inline CSS to `assets/css/style.scss` with Jekyll front matter
- Moved JavaScript to `assets/js/main.js` 
- Added Jekyll configuration in `_config.yml`
- Created proper layout structure in `_layouts/default.html`
- Added Jekyll front matter to `index.html`

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
