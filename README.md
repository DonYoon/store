# E-Commerce Store Project

This project is a simple e-commerce application built using Angular for the front-end and leveraging the fakestoreapi.com as the backend API. The application allows users to view products, add them to their shopping cart, adjust quantities, and proceed to checkout. The application uses Stripe for handling payments.

## Key Features:

1. **Product Listing:** The application fetches a list of products from fakestoreapi.com and displays them on the home page.
2. **Add to Cart:** Users can add products to their shopping cart.
3. **Shopping Cart:** Users can view their cart, adjust the quantity of each product in the cart, or remove items from the cart.
4. **Checkout:** The application redirects users to the Stripe checkout page to complete the purchase.

## Key Components:

1. **Services:** The application has two main services:
   - `CartService`: This service handles all cart-related operations like adding items to the cart, removing items from the cart, adjusting quantities, and calculating the total price of items in the cart.
   - `StoreService`: This service handles all interactions with the backend API. It fetches products and categories from the API.

2. **Components:** The application has several components:
   - `AppComponent`: The root component. It contains the header and a router-outlet where different pages are displayed.
   - `HeaderComponent`: This component displays the navigation bar at the top of the page. It also displays the current state of the shopping cart and allows users to clear the cart.
   - `HomeComponent`: This component displays a list of products on the home page.
   - `CartComponent`: This component displays the shopping cart and allows users to adjust quantities or remove items.

3. **Routing:** The application uses the Angular Router to navigate between the home page and the cart page.

## Technologies:

- Angular
- Angular Material for UI components
- RxJS for managing state
- fakestoreapi.com as backend API
- Stripe for payment handling
