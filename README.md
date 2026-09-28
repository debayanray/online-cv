# Debayan Ray - Online CV

My professional online CV/resume built with Jekyll.

**Live site:** [https://debayanray.github.io/online-cv/](https://debayanray.github.io/online-cv/)

## Features

- Responsive design with sidebar profile
- Skills organized by category with visual pills
- Experience timeline with detail pages for each role
- Open-source contributions section
- Target roles section
- Print-friendly layout

## Tech Stack

- Jekyll (static site generator)
- SCSS for styling
- GitHub Pages for hosting

## Local Development

1. Install Ruby and Bundler

2. Install dependencies:
```bash
bundle install
```

3. Serve locally:
```bash
bundle exec jekyll serve
```

4. Navigate to `http://localhost:4000/online-cv/`

## Structure

```
_data/data.yml      # Main profile data (skills, career profile, etc.)
_experiences/       # Individual experience detail pages
_includes/          # Reusable components
_layouts/           # Page layouts
_sass/              # SCSS stylesheets
```

## Export to PDF

Use browser print (Ctrl+P / Cmd+P) or third-party tools:
- https://webtopdf.com/
- https://tools.pdf24.org/en/webpage-to-pdf

## Credits

Theme based on [online-cv](https://github.com/sharu725/online-cv) by Sharath Kumar.
