# Anushka Restaurants Login Page

A responsive login page for Anushka Restaurants built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Dark theme with gradient backgrounds and smooth animations
- **Interactive Elements**: Hover effects, focus states, and form validation
- **Password Toggle**: Show/hide password functionality
- **Form Validation**: Basic client-side validation
- **Professional Styling**: Matches the provided design prototype

## Files Structure

```
anushka_restaurants_login/
├── index.html          # Main HTML file
├── style.css           # CSS styling
└── README.md           # This documentation
```

## Local Hosting Instructions

### Method 1: Simple HTTP Server (Recommended)

1. **Using Python (if installed):**
   ```bash
   cd anushka_restaurants_login
   python3 -m http.server 8000
   ```
   Then open: http://localhost:8000

2. **Using Node.js (if installed):**
   ```bash
   cd anushka_restaurants_login
   npx serve .
   ```
   Then open the provided URL (usually http://localhost:3000)

### Method 2: Direct File Opening

1. Navigate to the project folder
2. Double-click `index.html`
3. The page will open in your default browser

### Method 3: Live Server (VS Code Extension)

1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Customization

### Colors
The color scheme can be modified in `style.css`:
- Primary gradient: Lines 8-9
- Login form background: Line 108
- Button gradient: Line 185

### Images
- Chef image is loaded from Unsplash
- Logo uses inline SVG (can be replaced with custom logo)

### Responsive Breakpoints
- Desktop: 1024px and above
- Tablet: 768px - 1023px
- Mobile: 767px and below

## Form Functionality

Currently includes:
- Email validation
- Password field with show/hide toggle
- Form submission handler (shows alert with email)
- Basic client-side validation

To integrate with a backend:
1. Replace the JavaScript alert in the form submission handler
2. Add proper API endpoints for authentication
3. Implement proper error handling

## Performance Features

- Optimized images
- Smooth animations
- Efficient CSS
- Minimal JavaScript
- Fast loading times

## Security Notes

This is a frontend-only implementation. For production use:
- Implement proper backend authentication
- Add CSRF protection
- Use HTTPS
- Implement rate limiting
- Add proper input sanitization

