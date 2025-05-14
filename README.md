# eCommerce-Landing-Page-Website

## Overview

This project is a fully responsive eCommerce landing page designed to showcase products, deals, and services for an online shopping platform. It includes various sections such as a header with search functionality, a hero section, product showcases, a supplier request form, and a footer with newsletter subscription. The page is built using HTML, CSS, and JavaScript, ensuring a seamless experience across mobile, tablet, and desktop devices.

The landing page was last updated on May 14, 2025, and is designed with a modern, user-friendly interface using the Roboto font and a consistent color scheme (`#007bff` for primary elements, `#8B96A5` for secondary elements).

---

## Live Demo
[Live Demo Here](https://muzamal478.github.io/eCommerce-Landing-Page-Website/)

---

## Features

- **Responsive Design**: Fully responsive across mobile (up to 768px), tablet (769px–1024px), and desktop (1024px and above) devices.
- **Header**:
  - Logo, search bar with category dropdown, and user action icons (Profile, Message, Orders, Cart).
  - Navigation menu with categories and a language/shipping selector.
- **Hero Section**:
  - Categories list, banner with call-to-action, and user-focused side boxes (Join Now, Discount, Quote).
- **Deals and Offers**:
  - Countdown timer for limited-time offers.
  - Product cards showcasing deals with discounts.
- **Product Showcases**:
  - "Home and Outdoor" and "Consumer Electronics" sections with featured categories and product grids.
- **Supplier Request Form**:
  - Form to send inquiries to suppliers with fields for item, details, quantity, and unit.
- **Recommended Items**:
  - Grid of recommended products with prices and descriptions.
- **Extra Services**:
  - Cards highlighting additional services with images and icons.
- **Suppliers by Region**:
  - List of suppliers by country with flags and domain links.
- **Newsletter Subscription**:
  - Form to subscribe to newsletters with email input.
- **Footer**:
  - Company information, links, social media icons, and app store buttons.
- **Dynamic Functionality**:
  - JavaScript-powered countdown timer and dynamic rendering of product sections.

---

## File Structure

```
eCommerce-Landing-Page/
├── assets/
│   ├── logo-colored.svg        # Brand logo for header and footer
│   ├── logo-symbol.svg        # Favicon
│   ├── Profile.svg            # Header icon
│   ├── Message.svg            # Header icon
│   ├── Orders.svg             # Header icon
│   ├── Cart.svg               # Header icon
│   ├── menu.svg               # Navigation menu icon
│   ├── icon.svg               # Flag icon for language/shipping selector
│   ├── Banner-board.svg       # Hero banner image
│   ├── Avatar.svg             # User avatar in hero side box
│   ├── image 102.svg          # Supplier request section background
│   ├── image 92.svg           # Home and outdoor category background
│   ├── image 98.svg           # Consumer electronics category background
│   ├── cloth/                 # Images for recommended items
│   ├── interior/              # Images for home and outdoor products
│   ├── tech/                  # Images for consumer electronics products
│   ├── flags/                 # Country flags for suppliers by region
│   ├── Mask group-1.svg       # Extra services images
│   ├── Mask group-2.svg
│   ├── Mask group-3.svg
│   ├── Mask group.svg
│   ├── send.svg               # Service icons
│   ├── search.svg
│   ├── security.svg
│   ├── inventory_2.svg
│   ├── facebook3.svg          # Social media icons
│   ├── twitter3.svg
│   ├── instagram3.svg
│   ├── linkedin3.svg
│   ├── youtube3.svg
│   ├── Group.svg              # App Store button
│   ├── market-button.svg      # Google Play button
│   ├── Vector.svg             # Newsletter email icon
│   ├── image 35.svg           # Deals product images
│   ├── image 34.svg
│   ├── image 28.svg
│   ├── image 29.svg
│   ├── image 23.svg
├── index.html                 # Main HTML file
├── styles.css                 # Stylesheet for the landing page
├── script.js                  # JavaScript for dynamic functionality
└── README.md                  # Project documentation
```

---

## Prerequisites

To run this project, you need:

- A modern web browser (e.g., Chrome, Firefox, Safari).
- A local server (e.g., Live Server extension in VS Code) to serve the files, as some features (like relative paths for assets) may not work when opening `index.html` directly in a browser.

---

## Setup Instructions

1. **Clone or Download the Project**:
   - Clone the repository or download the project files to your local machine.
   ```
   git clone https://github.com/muzamal478/eCommerce-Landing-Page-Website.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd eCommerce-Landing-Page-Website
   ```

3. **Open the Project**:
   - Open the project folder in a code editor like VS Code.
   - Ensure all files (`index.html`, `styles.css`, `script.js`, and the `assets` folder) are in the same directory.

4. **Run a Local Server**:
   - Use a local server to serve the files. For example, if you’re using VS Code:
     - Install the Live Server extension.
     - Right-click `index.html` and select "Open with Live Server".
   - Alternatively, you can use any local server setup (e.g., `http-server` via Node.js).

5. **Access the Page**:
   - Open your browser and navigate to the local server URL (e.g., `http://localhost:5500`).
   - The landing page should load with all assets, styles, and functionality intact.

---

## Usage

- **Header**:
  - Use the search bar to search for products (logs the query to the console for now).
  - Click on icons (Profile, Message, Orders, Cart) for user actions (links are placeholders).
  - Navigate through categories using the menu.
- **Hero Section**:
  - Browse categories on the left.
  - Click "Learn more" on the banner to explore trending items.
  - Join or log in using the user box on the right.
- **Deals and Offers**:
  - View limited-time deals with a countdown timer.
  - Product cards show discounts and images.
- **Product Showcases**:
  - Explore "Home and Outdoor" and "Consumer Electronics" sections.
  - Click "Source now" to explore more products in each category.
- **Supplier Request**:
  - Fill out the form to send inquiries to suppliers (form submission logs to the console).
- **Recommended Items**:
  - Browse recommended products with prices and descriptions.
- **Extra Services**:
  - Learn about additional services offered by the platform.
- **Suppliers by Region**:
  - View suppliers by country with their respective domains.
- **Newsletter**:
  - Enter your email to subscribe to the newsletter (logs to the console).
- **Footer**:
  - Access company information, links, social media, and app store buttons.

---

## Responsiveness

The landing page is fully responsive across devices:

### Mobile (Up to 768px)
- **Header**: Logo, search bar, and icons stack vertically. Navigation menu items stack for better accessibility.
- **Hero Section**: Categories, banner, and side boxes stack vertically. Banner image height reduces to 200px.
- **Deals and Offers**: Deals info and product cards stack vertically.
- **Product Showcases**: Featured category and product grid stack vertically. Product cards take full width.
- **Supplier Request**: Text and form stack vertically. Form inputs stack for usability.
- **Recommended Items**: Product cards stack into a single column.
- **Extra Services**: Service cards stack into a single column.
- **Suppliers by Region**: Country columns stack vertically.
- **Newsletter**: Form inputs and button stack vertically.
- **Footer**: Footer columns stack vertically, with centered text and social icons.

### Tablet (769px–1024px)
- **Hero Section**: Categories and side boxes take full width, banner remains centered.
- **Product Showcases**: Product cards display in a 2-column grid.
- **Recommended Items**: Product cards display in a 3-column grid.
- **Extra Services**: Service cards display in a 2-column grid.

### Desktop (1024px and Above)
- All sections display in their full layout with multi-column grids and side-by-side elements.

---

## Dependencies

- **Google Fonts**: The project uses the Roboto font, loaded via a CDN in `index.html`.
  ```html
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  ```
- No other external libraries or frameworks are required.

---

## Customization

### Colors
The project uses CSS custom properties (variables) for easy customization. Edit the `:root` section in `styles.css` to change colors:

```css
:root {
  --primary-color: #007bff;      /* Primary buttons and accents */
  --secondary-color: #8B96A5;    /* Secondary text and elements */
  --background-color: #f8f9fa;   /* Background color */
  --text-color: #212529;         /* Primary text color */
  --white: #fff;                 /* White */
  --gray: #dee2e6;               /* Borders and dividers */
  --red: #eb001b;                /* Discount tags */
  --light-bg: #eff2f4;           /* Light background for sections */
}
```

### Fonts
To change the font, update the Google Fonts link in `index.html` and update the `font-family` in `styles.css`:

```css
body {
  font-family: 'Roboto', sans-serif;
}
```

### Assets
Replace images in the `assets` folder to update visuals. Ensure the file names and paths remain the same, or update references in `index.html` and `script.js`.

---

## JavaScript Functionality

The `script.js` file handles dynamic rendering and interactivity:

- **Product Rendering**:
  - `renderDeals()`: Renders product cards in the "Deals and Offers" section.
  - `renderHomeOutdoor()`: Renders product cards in the "Home and Outdoor" section.
  - `renderElectronics()`: Renders product cards in the "Consumer Electronics" section.
  - `renderRecommended()`: Renders product cards in the "Recommended Items" section.
- **Countdown Timer**:
  - `startCountdown()`: Updates the countdown timer in the "Deals and Offers" section every second.
- **Search**:
  - `searchProducts()`: Logs the search query to the console (placeholder for future implementation).
- **Initialization**:
  - All functions are called on page load via the `DOMContentLoaded` event listener.

To add more products, update the arrays in `script.js` (`deals`, `homeOutdoor`, `electronics`, `recommended`).

---

## Testing

### Responsiveness Testing
- Use browser dev tools to test at:
  - 320px (small mobile)
  - 768px (tablet)
  - 1024px (small desktop)
  - 1350px (large desktop)
- Verify that all sections stack correctly, text is readable, and buttons/forms are usable.

### Functionality Testing
- **Countdown Timer**: Ensure the timer updates every second and displays "Offer Expired" when the time is up.
- **Product Rendering**: Confirm all product sections render correctly with images, names, and prices.
- **Search Bar**: Check that the search bar logs the query to the console when the button is clicked.
- **Forms**: Test the supplier request and newsletter forms to ensure inputs are functional (logs to console).

### Cross-Browser Testing
- Test on Chrome, Firefox, and Safari to ensure compatibility with styles and functionality.

---

## Known Issues

- **Search Functionality**: The search bar currently logs the query to the console. A full search implementation would require a backend or additional JavaScript logic.
- **Form Submission**: The supplier request and newsletter forms log to the console. To handle submissions, integrate a backend or form handler (e.g., Formspree, Netlify Forms).
- **Placeholder Links**: Links in the navigation, footer, and buttons are placeholders (`#`). Update them with actual URLs as needed.

---

## Future Improvements

- Add a backend to handle search queries and form submissions.
- Implement lazy loading for images to improve performance.
- Add hover effects and animations for better user engagement.
- Include a dark mode toggle for accessibility.
- Add unit tests for JavaScript functions using a framework like Jest.

---

## Contributing

To contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```
   git push origin feature-name
   ```
5. Create a pull request with a detailed description of your changes.

---

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as needed.

---

## Contact

For questions or support, contact:

- **Name**: Muzamal Asghar
- **Email**: muzamalasghar47@gmail.com
- **Date**: May 14, 2025
