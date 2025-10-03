# Chetan's Café - Online Ordering System

A modern, responsive web application for Chetan's Café that allows customers to browse the menu and place orders online.

## 📋 Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Menu Categories](#menu-categories)
- [File Structure](#file-structure)
- [Browser Compatibility](#browser-compatibility)
- [Contributing](#contributing)

## ✨ Features

### Core Functionality
- **Interactive Menu Display**: Browse through 16 delicious items with high-quality images
- **Smart Ordering System**: Add items to your order with quantity tracking
- **Real-time Price Calculation**: See your total update instantly as you add items
- **Sticky Order Summary**: Order panel stays visible while scrolling through the menu
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Order Confirmation**: Modal-based checkout with order number generation

### User Experience
- Hover effects on menu cards
- Visual feedback when items are added to order
- Easy item removal with quantity adjustment
- Category badges for quick identification
- Smooth animations and transitions

## 🛠 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with Bootstrap integration
- **JavaScript/jQuery**: Interactive functionality
- **Bootstrap 5.3.0**: Responsive grid and components
- **Font Awesome 6.4.0**: Icon library
- **Google Fonts (Poppins)**: Typography

## 📦 Installation

1. **Download the file**
   - Save the HTML file to your local machine

2. **No build process required**
   - This is a static HTML file that runs directly in the browser
   - All dependencies are loaded via CDN

3. **Open in browser**
   ```
   Simply double-click the HTML file or open it with your preferred browser
   ```

## 🚀 Usage

### For Customers

1. **Browse Menu**
   - Scroll through the menu section to see all available items
   - Items are organized with images, descriptions, prices, and categories

2. **Add Items**
   - Click "Add to Order" button on any menu item
   - Item will be added to your order summary on the right
   - Add the same item multiple times to increase quantity

3. **Review Order**
   - Check your selected items in the order summary panel
   - See individual item quantities and totals
   - View the overall total price

4. **Modify Order**
   - Click the × button next to any item to decrease quantity or remove it
   - Order total updates automatically

5. **Checkout**
   - Click the "Checkout" button when ready
   - Review your order in the modal
   - Click "Confirm Order" to complete
   - Receive your order number

6. **Place New Order**
   - Click "Place New Order" to start fresh

## 🍽 Menu Categories

The menu includes items from the following categories:
- **South Indian**: Masala Dosa, Idli Sambar, Uthappam
- **North Indian**: Coffee, Chole Bhature, Palak Paneer, Ice Cream, Chole Kulche
- **Appetizer**: Paneer Tikka, Samosa
- **Rice**: Veg Biryani, Cold Drinks
- **Beverage**: Mango Lassi, Masala Chai
- **Dessert**: Gulab Jamun, Rasmalai, Kulfi

## 📁 File Structure

```
chetan-cafe.html
├── HTML Structure
│   ├── Navigation Bar
│   ├── Hero Section
│   ├── Menu Section
│   │   ├── Menu Items Grid
│   │   └── Order Summary Panel
│   ├── Footer
│   └── Modals (Checkout & Thank You)
├── CSS Styling
│   ├── Custom Styles
│   └── Bootstrap Integration
└── JavaScript
    ├── Menu Data Array
    ├── Order Management Functions
    └── Event Handlers
```

## 💻 Browser Compatibility

This website is compatible with:
- ✅ Google Chrome (recommended)
- ✅ Mozilla Firefox
- ✅ Safari
- ✅ Microsoft Edge
- ✅ Opera

**Minimum Requirements:**
- JavaScript enabled
- Modern browser with ES6 support
- Internet connection (for CDN resources)

## 🎨 Customization

### Adding New Menu Items
Edit the `menuItems` array in the JavaScript section:

```javascript
{
    id: 17,
    name: "Your Item Name",
    price: 199,
    category: "Category",
    description: "Item description",
    image: "image-url"
}
```

### Changing Colors
Modify the CSS variables in the `<style>` section:
- Primary color: Update `.btn-warning` references
- Card hover effects: Modify `.card:hover`
- Background: Change `background-color` values

### Updating Contact Information
Edit the footer section in the HTML to update:
- Address
- Phone number
- Email
- Social media links

## 🔒 Important Notes

**Session Storage Notice:**
The original code contains `sessionStorage` API calls which are **not supported** in the Claude.ai artifact environment. These have been kept in the code for demonstration purposes but will need to be implemented differently if you deploy this to a live environment.

For production use:
- Remove or modify the sessionStorage code
- Consider using cookies or a backend database for session management
- Implement proper user authentication if needed

## 📧 Contact

For questions or support regarding Chetan's Café:
- **Location**: Ballabgarh, Faridabad, Haryana
- **Email**: info@chetanscafe.com
- **Phone**: (75038...31)

## 📄 License

This is a demonstration project for Chetan's Café. All rights reserved.

---

**Built with ❤️ for Chetan's Café**

*"Chetan's Café is the best café in the world. Thanks for visiting my cafe!"*
