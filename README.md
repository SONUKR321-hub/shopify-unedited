# UOMO Shopify Theme

A Shopify theme converted from the UOMO React.js e-commerce website. This theme brings the modern design and functionality of the original React application to the Shopify platform.

## 🎯 Features

- **Modern Design**: Clean, contemporary interface inspired by the original React design
- **Responsive Layout**: Fully responsive design that works on all devices
- **Shopify Native**: Built with Shopify's Liquid templating system and best practices
- **Fast Performance**: Optimized for speed and SEO
- **Customizable**: Easy-to-use theme settings for customization
- **Cross-browser Compatible**: Works across all modern browsers

## 📁 Theme Structure

```
uomo-shopify-theme/
├── assets/                 # CSS, JS, and other static files
│   ├── base.css           # Base styles and utilities
│   └── header.css         # Header-specific styles
├── config/                # Theme configuration
│   └── settings_schema.json # Theme customization options
├── layout/                # Main layout templates
│   └── theme.liquid       # Main theme layout
├── locales/               # Translation files
├── sections/              # Reusable sections
│   ├── header.liquid      # Site header with navigation
│   └── hero-banner.liquid # Homepage hero banner
├── snippets/              # Reusable code snippets
│   ├── icon-*.liquid      # SVG icons
│   └── meta-tags.liquid   # SEO meta tags
└── templates/             # Page templates
    ├── index.liquid       # Homepage template
    ├── product.liquid     # Product page template
    ├── collection.liquid  # Collection page template
    └── cart.liquid        # Shopping cart template
```

## 🚀 Installation

### Method 1: Shopify Admin Upload

1. **Zip the theme folder**: Compress the `uomo-shopify-theme` folder into a ZIP file
2. **Upload to Shopify**:
   - Go to your Shopify Admin
   - Navigate to `Online Store > Themes`
   - Click `Upload theme`
   - Select your ZIP file
   - Click `Upload`

### Method 2: Shopify CLI (Recommended for Development)

1. **Install Shopify CLI**:
   ```bash
   npm install -g @shopify/cli @shopify/theme
   ```

2. **Navigate to theme directory**:
   ```bash
   cd uomo-shopify-theme
   ```

3. **Connect to your store**:
   ```bash
   shopify theme dev --store your-store.myshopify.com
   ```

4. **Push to your store**:
   ```bash
   shopify theme push
   ```

## ⚙️ Configuration

### Theme Settings

Access theme settings through: `Shopify Admin > Online Store > Themes > Customize`

Available settings include:
- **Colors**: Primary and secondary color schemes
- **Typography**: Font selections for headings and body text
- **Layout**: Page width and spacing options
- **Product Cards**: Card styling and layout options
- **Social Media**: Links to your social media profiles

### Navigation Setup

1. **Main Menu**:
   - Go to `Navigation` in your Shopify admin
   - Edit the `Main menu`
   - Add links for: Home, Shop, Blog, About, Contact

2. **Footer Menu**:
   - Create additional menus for footer links
   - Configure in theme settings

### Required Pages

Create these pages in your Shopify admin for full functionality:
- **About**: `/pages/about`
- **Contact**: `/pages/contact`
- **Terms & Conditions**: `/pages/terms`
- **Privacy Policy**: `/pages/privacy`

## 🎨 Customization

### Colors
The theme includes a comprehensive color system:
- Primary text color
- Background colors (primary/secondary)
- Accent colors for buttons and highlights
- Button text colors

### Typography
- Choose from Shopify's font library
- Separate settings for headings and body text
- Automatic font loading and optimization

### Layout Options
- Adjustable page width (1000px - 1600px)
- Section spacing controls
- Grid spacing options

### Product Cards
- Text alignment options
- Border radius and thickness
- Shadow effects
- Border opacity controls

## 🛠️ Development

### File Structure

- **Liquid Templates**: All templates use Shopify's Liquid templating language
- **CSS**: Modular CSS with utility classes and component styles
- **JavaScript**: Vanilla JavaScript for enhanced functionality
- **Icons**: SVG icons as Liquid snippets for easy maintenance

### Key Components

1. **Header Navigation**:
   - Desktop and mobile navigation
   - Cart icon with item count
   - Search functionality
   - Account links

2. **Product Display**:
   - Product cards with hover effects
   - Image galleries with zoom
   - Variant selection
   - Add to cart functionality

3. **Cart System**:
   - Ajax cart updates
   - Quantity controls
   - Discount display
   - Checkout integration

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- iOS Safari (latest)
- Chrome Mobile (latest)

## 📱 Mobile Optimization

The theme is fully responsive with:
- Touch-friendly navigation
- Mobile-optimized product galleries
- Responsive grid layouts
- Touch gestures for image carousels

## 🔧 Troubleshooting

### Common Issues

1. **Theme not loading properly**:
   - Check that all required files are uploaded
   - Verify Liquid syntax in templates
   - Check browser console for JavaScript errors

2. **Styling issues**:
   - Ensure CSS files are properly linked
   - Check theme settings for color/font configurations
   - Verify responsive breakpoints

3. **Cart functionality**:
   - Ensure proper form actions in templates
   - Check JavaScript for cart updates
   - Verify Shopify cart routes

### Performance Optimization

- Images are lazy-loaded where appropriate
- CSS is minified for production
- JavaScript uses modern ES6+ features with fallbacks
- Fonts are preloaded for better performance

## 📞 Support

For theme-specific issues:
1. Check the troubleshooting section above
2. Review Shopify's theme development documentation
3. Test in a different browser or device
4. Check browser developer tools for errors

## 📄 License

This theme is converted from the UOMO React.js project and maintains compatibility with Shopify's terms of service and theme requirements.

## 🔄 Updates

To update the theme:
1. Download the latest version
2. Back up your current theme
3. Upload the new version
4. Test thoroughly before publishing
5. Update any custom modifications

---

**Note**: This theme has been converted from a React.js application to work with Shopify's Liquid templating system. Some features may require additional Shopify apps or custom development for full functionality.
