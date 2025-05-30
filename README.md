# GarudadevDataServices Website

This website has been successfully split into separate files and enhanced with dark/light theme functionality.

## Files Structure

- `index.html` - Main HTML file (cleaned up, references external CSS and JS)
- `styles.css` - All CSS styles with light/dark theme support
- `script.js` - JavaScript functionality including theme toggle and animations
- `garuda-icon.svg` - Placeholder Garuda icon (replace with your actual JPG/PNG)

## Features Implemented

### ✅ 1. File Separation
- Extracted all CSS from HTML into `styles.css`
- Extracted all JavaScript from HTML into `script.js`
- Clean HTML structure with external references

### ✅ 2. Dark/Light Theme Toggle
- **Default**: Light theme (as requested)
- **Toggle Button**: Moon/Sun icon in navigation
- **Persistence**: Theme preference saved in localStorage
- **Smooth Transitions**: All elements transition smoothly between themes

### ✅ 3. Website Name Update
- Changed from "GarudaDev Data Services" to "GarudadevDataServices"
- Updated in navigation, hero section, title, and footer
- **Plain text styling**: Removed gradient effects for plain black/white text

### ✅ 4. Garuda Icon Integration
- Added as favicon in browser tab
- Integrated in navigation logo
- Used in developer avatar section
- **Note**: Replace `garuda-icon.svg` with your actual JPG image

### ✅ 5. Performance Improvements
- **Fixed lazy loading**: Reduced threshold from 0.1 to 0.05 and improved rootMargin
- **Faster animations**: Cards and stats now appear much quicker when scrolling
- **Optimized intersection observer**: Better performance for fade-in effects

### ✅ 6. Enhanced Stats Section
- **New stat card**: Added "165+ GitHub Stars"
- **Better layout**: Increased max-width to accommodate 4 cards
- **Improved mobile**: Better responsive design for multiple cards

### ✅ 7. Color Scheme Update
- **Changed from purple to red**: All accent colors now use red theme
- **Red gradients**: Updated primary and secondary colors
- **Consistent theming**: Red colors in both light and dark modes
- **Updated tech tags**: Technology badges now use red color scheme

## Theme Colors

### Light Theme
- Background: White (#ffffff)
- Text: Dark (#333333)
- Cards: Semi-transparent white
- Accent: Red gradient (#dc2626 to #b91c1c)

### Dark Theme
- Background: Dark blue (#0f0f23)
- Text: White (#ffffff)
- Cards: Semi-transparent white overlay
- Accent: Red gradient (#dc2626 to #ef4444)

## How to Replace the Icon

1. Save your Garuda JPG image as `garuda-icon.png` or `garuda-icon.jpg`
2. Update the file references in:
   - `index.html` (3 locations: favicon, logo, avatar)
   - Optionally update `styles.css` if needed

## Usage

1. Open `index.html` in a web browser
2. Click the moon/sun icon in the top-right to toggle themes
3. The website will remember your theme preference

## Browser Compatibility

- Modern browsers with CSS custom properties support
- JavaScript enabled for theme toggle functionality
- Responsive design for mobile and desktop
