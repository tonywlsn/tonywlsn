# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal website for Antony Wilson, a software development consultant. The site is built with vanilla HTML, CSS, and JavaScript and is hosted on GitHub Pages at https://tonywlsn.github.io/tonywlsn.

## Architecture

- **Static site**: Pure HTML/CSS/JavaScript with no build process
- **Single page application**: All content is in index.html with smooth scrolling navigation
- **Responsive design**: Mobile-first approach with CSS Grid and Flexbox
- **GitHub Pages deployment**: Direct deployment from the main branch

## Key Files

- `index.html` - Main HTML structure with all sections (hero, about, services, skills, contact)
- `styles.css` - Complete CSS styling with responsive breakpoints
- `script.js` - JavaScript for mobile navigation, smooth scrolling, and scroll animations
- `README.md` - Basic project information and live site link

## Development

Since this is a static site, you can:
- Open `index.html` directly in a browser for local development
- Make changes to HTML, CSS, or JavaScript files directly
- Test responsiveness using browser dev tools

## Deployment

The site auto-deploys to GitHub Pages when changes are pushed to the main branch. No build process is required.

## Design System

- **Primary color**: #2563eb (blue)
- **Typography**: Inter font family from Google Fonts
- **Icons**: Font Awesome 6.0.0
- **Layout**: CSS Grid for services and skills sections, Flexbox for navigation and hero buttons
- **Animations**: CSS transitions with JavaScript Intersection Observer for scroll animations