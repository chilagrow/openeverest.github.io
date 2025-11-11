# Everest Open Source Website

## Overview
This is the official website for the Everest Open Source project, hosted on GitHub Pages at everest.github.io. The website serves as the main landing page and information hub for the project.

## Project Structure
- `index.html` - Main website page with sections for About, Features, and Community
- `style.css` - Styling with responsive design and modern gradient hero section
- `LICENSE` - Apache License 2.0
- `README.md` - Project description

## Technology Stack
- **Frontend**: Static HTML/CSS
- **Server**: Python HTTP server (development)
- **Deployment**: Replit Autoscale deployment

## Development
The website runs on port 5000 using Python's built-in HTTP server. The workflow is configured to automatically start the web server when the project loads.

### Running Locally
The `web-server` workflow automatically serves the website at port 5000:
```bash
python -m http.server 5000 --bind 0.0.0.0
```

## Deployment
The project is configured for Replit's Autoscale deployment, which is ideal for static websites. The deployment uses the same Python HTTP server to serve the static files.

## Project Status
- **Last Updated**: November 11, 2025
- **Status**: Active and ready for deployment
- **GitHub**: https://github.com/openeverest/everest.github.io

## Recent Changes
- **2025-11-11**: Initial website setup with HTML/CSS landing page
  - Created responsive website with hero section, navigation, and content sections
  - Configured Python web server workflow on port 5000
  - Set up deployment configuration for Replit Autoscale
  - Added .gitignore for common development files
