# Mulytics

A professional website for bioinformatics and biostatistics consulting services.

## Overview

Mulytics is a consulting company specializing in bioinformatics, biostatistics, and custom application development for biological research. This website showcases our services, research publications, and developed applications.

## Features

- **Responsive Design**: Mobile-first approach with responsive layouts for all screen sizes
- **Modern UI**: Clean, professional design with dark theme and purple accent colors
- **Interactive Elements**: Smooth animations, hover effects, and interactive charts
- **Contact Forms**: Integrated contact and newsletter subscription forms using Formspree
- **Publication Showcase**: Display of research publications and academic work
- **Application Portfolio**: Showcase of developed web applications and tools

## Services

### Bioinformatics Analysis
- Transcriptomics and Proteomics
- Quality Control (QC)
- Alignment and Mapping
- Quantification
- Differential Expression Analysis
- Pathway Analysis
- Network Analysis
- Time-series Analysis
- Interactive Data Visualization

### Biostatistics
- Descriptive and Analytical Statistics
- Machine Learning
- Convolutional Neural Networks
- Propensity-Score Matching
- Marginal Effects
- Survival Analysis
- Power Analysis

### App Development
- Automated Analysis Apps
- Machine Learning Analysis Apps
- Interactive Dashboards
- Custom Web Applications

## Research Publications

- **Biological Network Analysis**: Advanced methods for analyzing biological networks
- **Propensity-Score Matching**: Statistical methods for causal inference
- **Marginal Effects Analysis**: Advanced statistical techniques
- **Neural Network Applications**: AI models for medical applications

## Developed Applications

- **Postoperative Facial Nerve Prediction**: ML application for predicting facial nerve function
- **Giant Pituitary Adenoma Resection**: Interactive surgical planning tool
- **CHOA TBI Analysis**: Comprehensive pediatric TBI analysis tool

## Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and form handling
- **Formspree**: Form submission handling
- **Google Fonts**: Inter font family for typography

## File Structure

```
mulytics.net/
├── index.html              # Main website file
├── styles.css              # All CSS styles and responsive design
├── _redirects              # Netlify redirects configuration
├── favicon.svg             # Website favicon
├── favicon-transparent.svg # Transparent version of favicon
├── logo.svg                # Company logo
├── logo-transparent.svg    # Transparent version of logo
├── logo.png                # PNG version of logo
├── logo-transparent.png    # Transparent PNG version of logo
└── linkedin-banner.png     # LinkedIn banner image
```

## Setup and Deployment

### Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. For development with live reload, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

### Deployment
This website is designed to be deployed on static hosting platforms like:
- **Netlify** (recommended)
- **Vercel**
- **GitHub Pages**
- **AWS S3 + CloudFront**

#### Netlify Deployment
1. Connect your repository to Netlify
2. Set build command: (leave empty for static site)
3. Set publish directory: `/` (root directory)
4. Deploy

The `_redirects` file is included for Netlify redirect configuration.

## Customization

### Colors
The website uses a consistent color scheme defined in CSS:
- Primary: `#8b5cf6` (Purple)
- Background: `#1a1a1a` (Dark)
- Secondary Background: `#2a2a2a` (Darker)
- Text: `#ffffff` (White)
- Muted Text: `#cccccc` (Light Gray)

### Typography
- Font Family: Inter (Google Fonts)
- Weights: 300, 400, 500, 600, 700

### Contact Forms
Forms are configured to use Formspree with the endpoint `https://formspree.io/f/myzdvwpo`. To use your own Formspree account:
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Replace the form action URLs in `index.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images and SVGs
- Minimal external dependencies
- Efficient CSS with minimal redundancy
- Fast loading times with static hosting

## License

© 2025 Mulytics. All rights reserved.

## Contact

- **Website**: [mulytics.net](https://mulytics.net)
- **LinkedIn**: [Mulytics](https://www.linkedin.com/company/mulytics/)
- **Email**: Contact through the website form

## Contributing

This is a company website. For business inquiries or collaboration opportunities, please use the contact form on the website.
