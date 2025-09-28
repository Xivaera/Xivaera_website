# Xivaera Technologies Website

## Overview

This is a static company website for Xivaera Technologies, a web and mobile development company. The website serves as a marketing and portfolio platform showcasing the company's services, projects, and expertise. It's built as a multi-page static site with modern web technologies focusing on responsive design, smooth animations, and professional presentation.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The website follows a traditional multi-page static site architecture with shared components and styling:

- **Static HTML Structure**: Five main pages (index, about, services, portfolio, contact) with consistent navigation and layout patterns
- **Component-Based Design**: Shared navigation, header, and footer components across all pages
- **Responsive Design**: Mobile-first approach using Tailwind CSS framework
- **Animation System**: AOS (Animate On Scroll) library for smooth page transitions and element animations

### Styling and UI Framework
- **Tailwind CSS**: Utility-first CSS framework loaded via CDN for rapid styling and consistent design system
- **Custom CSS**: Additional styles in `assets/css/style.css` for specific animations and brand customizations
- **Design System**: Consistent color palette with primary green theme (#6bb768) and Inter font family
- **Interactive Elements**: Hover effects, smooth transitions, and animated navigation links

### JavaScript Architecture
- **Vanilla JavaScript**: Core functionality handled with vanilla JS for navigation, mobile menu, and scroll behaviors
- **jQuery**: Used for enhanced DOM manipulation and event handling
- **Modular Organization**: Main JavaScript file (`assets/js/main.js`) handles page initialization, mobile menu toggle, and smooth scrolling

### Performance Optimizations
- **CDN Dependencies**: External libraries loaded from CDNs for faster loading and reduced server load
- **Animation Optimization**: CSS transforms and transitions for smooth performance
- **Mobile Optimization**: Responsive design patterns and mobile-specific navigation

## External Dependencies

### CSS Frameworks and Libraries
- **Tailwind CSS**: Primary styling framework loaded from CDN
- **AOS (Animate On Scroll)**: Animation library for scroll-triggered animations
- **Font Awesome**: Icon library for consistent iconography

### JavaScript Libraries
- **jQuery**: DOM manipulation and event handling
- **AOS JavaScript**: Animation initialization and control

### Fonts and Typography
- **Google Fonts**: Inter font family for consistent typography across the site

### Development Tools
- **Tailwind CSS CDN**: Custom configuration for brand colors and extended theme
- **Custom CSS Variables**: CSS custom properties for consistent color management

The architecture prioritizes simplicity, performance, and maintainability while providing a professional user experience with modern web standards and responsive design principles.