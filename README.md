# Bella Hair - E-Commerce Website

A beautiful, modern e-commerce website inspired by premium hair care and accessories brands. This website features a clean, elegant design with smooth animations and full responsiveness.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, elegant design with smooth animations and transitions
- **Interactive Elements**: 
  - Mobile-friendly hamburger menu
  - Search overlay functionality
  - Shopping cart with live counter
  - Add to cart animations
  - Toast notifications
  - Smooth scrolling navigation
  - Parallax effects
  - Intersection observer animations

- **Key Sections**:
  - Announcement bar
  - Navigation with dropdown menus
  - Hero section with call-to-action
  - Featured products showcase
  - Promotional banners
  - Category browsing
  - About section
  - Newsletter signup
  - Comprehensive footer

## 🚀 Getting Started

### Option 1: Open Directly
Simply open the `index.html` file in your web browser:
1. Navigate to the project folder
2. Double-click `index.html`
3. The website will open in your default browser

### Option 2: Use a Local Server (Recommended)
For the best experience, use a local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Then open: http://localhost:8000
```

**Using Node.js (with http-server):**
```bash
npx http-server -p 8000

# Then open: http://localhost:8000
```

**Using VS Code:**
- Install the "Live Server" extension
- Right-click on `index.html`
- Select "Open with Live Server"

## 📁 File Structure

```
/
├── index.html      # Main HTML structure
├── styles.css      # All CSS styling and animations
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## 🎨 Design Features

### Color Palette
- **Primary**: Dark charcoal (#2d2d2d)
- **Secondary**: Warm brown (#8b7355)
- **Accent**: Golden tan (#d4a574)
- **Light Background**: Cream (#f9f6f2)
- **White**: Pure white (#ffffff)

### Typography
- **Headings**: Cormorant Garamond (elegant serif)
- **Body**: Montserrat (clean sans-serif)

### Key Interactions
- **Hover Effects**: Smooth transitions on all interactive elements
- **Scroll Animations**: Fade-in effects as elements come into view
- **Cart System**: Live cart counter with visual feedback
- **Mobile Menu**: Animated hamburger menu for mobile devices
- **Search**: Full-screen search overlay with smooth transitions

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2d2d2d;
    --secondary-color: #8b7355;
    --accent-color: #d4a574;
    /* ... */
}
```

### Adding Real Products
1. Replace the `.product-img-placeholder` divs with actual `<img>` tags
2. Update product names, prices, and descriptions
3. Connect to a backend API for dynamic product loading

### Adding Real Images
Replace the gradient placeholders with your images:
```html
<!-- Replace this: -->
<div class="product-img-placeholder">
    <span class="placeholder-text">Product Name</span>
</div>

<!-- With this: -->
<img src="path/to/image.jpg" alt="Product Name">
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 767px and below

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Future Enhancements

Consider adding:
- Backend integration for real product data
- User authentication system
- Complete shopping cart and checkout flow
- Product filtering and sorting
- Customer reviews and ratings
- Wishlist functionality
- Product search with live results
- Multi-language support
- Dark mode toggle

## 📄 License

This is a demonstration project. Feel free to use and modify as needed.

## 🤝 Credits

Design inspired by modern e-commerce websites with a focus on user experience and visual appeal.

---

**Note**: This is a front-end demo. For a production website, you'll need to integrate:
- Backend API for product management
- Payment gateway integration
- User authentication system
- Database for storing products and orders
- Content Management System (CMS)

