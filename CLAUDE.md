# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a personal portfolio website for Yaqin Hei, a Machine Learning Engineer. The site is a static HTML/CSS website hosted on GitHub Pages.

## Architecture
- **Static Website**: Single-page application built with vanilla HTML and CSS
- **Main Files**:
  - `index.html` - Main portfolio page with timeline, research, projects, and contact information
  - `styles.css` - CSS styling with responsive design for mobile devices
  - `photo.png` - Profile photo used in the about section
  - `Hei_ML engineer_All.pdf` - Resume/CV document

## Development Commands
This is a static website with no build process or dependencies. To work with the site:

- **Local Development**: Open `index.html` directly in a browser or use a simple HTTP server:
  ```bash
  python -m http.server 8000  # Python 3
  # or
  python -m SimpleHTTPServer 8000  # Python 2
  ```

- **Deployment**: The site is hosted on GitHub Pages, so changes pushed to the main branch will automatically deploy

## Code Structure
- **Responsive Design**: Mobile-first approach with breakpoints at 600px
- **Semantic HTML**: Proper use of sections, headers, and semantic elements
- **CSS Organization**: Organized with comments for different component sections (reset, header, timeline, etc.)
- **Bilingual Content**: Mix of English and Chinese text throughout the site

## Key Features
- Timeline section showcasing career progression
- Research and projects sections
- Contact information and social links
- Circular profile photo with CSS transforms
- Responsive design for mobile devices

## Content Areas
- **Timeline**: Professional experience in reverse chronological order
- **Research**: Current focus areas and publications
- **Projects**: Key AI/ML projects
- **Certifications**: Professional certifications
- **Contact**: Email and social media links