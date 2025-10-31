# Jaydeb Sarader Portfolio

## Overview
This is a personal portfolio website for Jaydeb Sarader, a Data Analyst & Engineer with expertise in Business Intelligence, data visualization, and analytics. The portfolio showcases projects, skills, education, and professional experience.

**Project Type:** Static HTML/CSS/JavaScript Portfolio Website  
**Current State:** Fully functional and deployed on Replit  
**Last Updated:** October 31, 2025

## Purpose
- Showcase data analytics and data science projects
- Display professional skills and experience in BI tools (Power BI, Tableau)
- Provide contact information and professional links
- Demonstrate proficiency in Python, SQL, Excel, and machine learning

## Recent Changes
- **October 31, 2025:** Initial import and setup on Replit
  - Created Python HTTP server (server.py) for serving static files
  - Configured workflow to run on port 5000 with webview output
  - Set up deployment configuration for autoscale deployment
  - Added cache control headers to prevent browser caching issues

## Project Architecture

### Structure
```
/
├── index.html              # Main portfolio page (single-page application)
├── server.py               # Python HTTP server (port 5000)
├── css/                    # Stylesheets
│   ├── style.css          # Main custom styles
│   ├── bootstrap.min.css  # Bootstrap framework
│   ├── animate.css        # Animation library
│   └── ...                # Other CSS libraries
├── js/                     # JavaScript files
│   ├── main.js            # Custom JavaScript
│   ├── jquery.min.js      # jQuery library
│   └── ...                # Other JS libraries
├── images/                 # Portfolio images and project screenshots
├── fonts/                  # Icon fonts and typography
│   ├── flaticon/
│   ├── icomoon/
│   ├── ionicons/
│   └── open-iconic/
└── scss/                   # SCSS source files (not compiled)
```

### Technologies Used
- **Frontend:** HTML5, CSS3, JavaScript
- **Libraries:** jQuery, Bootstrap, Owl Carousel, AOS (Animate On Scroll)
- **Icons:** Flaticon, Icomoon, Ionicons, Open Iconic
- **Server:** Python 3.11 HTTP server
- **Deployment:** Replit Autoscale

### Key Features
- Responsive design with Bootstrap
- Animated typing effect on hero section
- Interactive project showcase with hover effects
- Smooth scrolling navigation
- Skills visualization with progress bars
- Contact section with social links

## Running the Project

### Development
The project runs automatically via the configured workflow:
- **Command:** `python server.py`
- **Port:** 5000
- **Host:** 0.0.0.0 (allows external access)
- **Output:** Webview (displays in Replit preview pane)

### Manual Start
If you need to restart the server manually:
```bash
python server.py
```

### Cache Management
The server includes cache control headers to prevent browser caching issues during development. If you don't see changes reflected:
1. Restart the workflow
2. Use browser developer tools to perform a "hard refresh" (Ctrl+Shift+R or Cmd+Shift+R)

## Deployment
The project is configured for Replit Autoscale deployment:
- **Type:** Autoscale (stateless web application)
- **Run command:** `python server.py`
- **Port:** 5000 (automatically exposed by Replit)

To publish the site, click the "Deploy" button in Replit.

## Known Issues
- Minor JavaScript error in browser console related to `typingAnimationElement` identifier being declared multiple times due to carousel cloning scripts. This doesn't affect functionality but could be optimized in the future.

## Future Enhancements
- Add blog section for technical articles
- Integrate contact form with email backend
- Add dark mode toggle
- Optimize images for faster loading
- Add Google Analytics for tracking

## Contact Information
- **Name:** Jaydeb Sarader
- **Location:** Kolkata, India
- **GitHub:** https://github.com/jaydeb2023
- **LinkedIn:** www.linkedin.com/in/jaydeb-sarader-39210b193

## Portfolio Sections
1. **Home:** Hero section with animated typing effect
2. **About:** Personal introduction, skills, and achievements
3. **Resume:** Education, volunteer work, and achievements
4. **Projects:** Showcase of data analytics and ML projects
5. **Contact:** Social links and contact information
