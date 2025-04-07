# Shopping Website

A responsive shopping website built with HTML, CSS, and JavaScript, featuring user authentication, product listings, cart functionality, and payment processing.

## Overview

This project is a fully functional e-commerce website named "AMAZOON," designed to provide a seamless shopping experience. It includes user login/signup, a product catalog, cart management, and a payment system. The website is styled with a modern gradient background, wave animations, and a mobile-first design approach, ensuring accessibility across devices.

## Features

- **User Authentication**:
  - Login and signup functionality using local storage to manage user accounts.
  - Password-protected access to shopping features.
- **Product Listings**:
  - Displays a catalog of products with names, prices, and "Add to Cart" buttons.
  - Currently includes three sample products (Item 1: $10, Item 2: $20, Item 3: $15).
- **Cart Functionality**:
  - Add items to the cart with dynamic updates to the total cost.
  - Remove items from the cart with real-time UI updates.
  - Displays "No items in the cart" when empty.
- **Payment Processing**:
  - Supports Credit Card and PayPal payment methods.
  - Dynamically shows payment fields based on the selected method (e.g., card number, expiry date, CVV for Credit Card; email for PayPal).
  - Confirms payment with a success message and clears the cart.
- **Responsive Design**:
  - Mobile-first design with a clean UI, ensuring usability on all screen sizes.
  - Gradient background with animated waves for a modern aesthetic.
- **Navigation**:
  - Easy navigation between Home, Cart, About Us, and Login/Logout sections.
  - Single-page application (SPA) style with section toggling for a smooth user experience.

## Live Demo

[View the live website here](https://ralphruto.github.io/ShoppingWebsite)


## Project Structure

- `index.html`: Main page with login, signup, home, cart, about, and payment sections.
- `about.html`: Standalone About Us page (alternative to the About section in `index.html`).
- `checkout.html`: Standalone Cart page (alternative to the Cart section in `index.html`).
- `script.js`: JavaScript file handling user authentication, cart functionality, and payment processing.
- `styles.css`: CSS file for styling the website, including gradient background, wave animations, and responsive layout.

## Technologies Used

- **HTML**: For structuring the website content and sections.
- **CSS**: For styling, including mobile-first design, gradient background, and wave animations.
- **JavaScript**: For dynamic functionality like user authentication, cart management, and payment processing.
- **Local Storage**: For persisting user data and login state.

## Credits

This project was developed in collaboration with:
- [Kenneth Liu](https://emmahnguyen.github.io/Kennypage/)
- [Emma Nguyen](https://emmahnguyen.github.io/EmmaWebpage/)
- [Hoa Nguyen](https://hoanguyen36.github.io/myIDwebpage/)

## Contributing

Feel free to fork this repository and submit pull requests to contribute to the project. For major changes, please open an issue to discuss your ideas.

