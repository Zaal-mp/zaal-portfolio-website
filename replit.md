# Portfolio Website

A modern, responsive portfolio website for showcasing your skills, projects, and experience.

## Overview

This is a clean, professional portfolio website built with HTML, CSS, and JavaScript. It features smooth scrolling, responsive design, and animated sections to create an engaging user experience.

## Project Structure

- `index.html` - Main HTML structure with sections for Home, About, Skills, Projects, and Contact
- `styles.css` - All styling with CSS custom properties, animations, and responsive design
- `script.js` - JavaScript for smooth scrolling, scroll animations, and interactive navbar
- `server.py` - Simple Python HTTP server to serve the static files

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Click navigation links for smooth scrolling to sections
- **Animated Elements**: Fade-in animations as you scroll through the page
- **Auto-hiding Navbar**: Navbar slides up when scrolling down, reappears when scrolling up
- **Modern UI**: Clean, professional design with gradient accents
- **Easy Customization**: Simple to update with your own information

## Customization Guide

To personalize this portfolio with your information:

1. **Update Personal Information** in `index.html`:
   - Replace "Your Name" with your actual name
   - Update the subtitle with your role/title
   - Modify the about section with your bio
   - Update contact information (email, GitHub, LinkedIn)

2. **Customize Skills** in `index.html`:
   - Edit the skill cards to match your expertise
   - Add or remove skill categories as needed

3. **Add Your Projects** in `index.html`:
   - Replace example projects with your actual work
   - Update project names, descriptions, and tags
   - Add links to live demos and source code
   - Consider adding project images instead of placeholders

4. **Adjust Colors** in `styles.css`:
   - Modify CSS custom properties in `:root` to change the color scheme
   - `--primary-color` and `--secondary-color` control the main theme

## Running Locally

The server runs on port 5000 and serves static files from the current directory. It includes cache-control headers to ensure you see updates immediately during development.

## Recent Changes

- **Nov 20, 2024**: Initial project setup
  - Created responsive portfolio website with HTML/CSS/JavaScript
  - Set up Python HTTP server for serving static files
  - Configured workflow to run on port 5000
  - Added smooth scrolling and scroll animations
  - Implemented responsive design for all screen sizes
