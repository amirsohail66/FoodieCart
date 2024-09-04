
# FoodieCart: MEAN Stack eCommerce Food Delivery Website

FoodieCart is a fully authenticated eCommerce website for selling food online. Built using the MEAN stack, it provides a seamless experience for customers to browse, order, and pay for their favorite dishes.

Live Demo: [foodmine-eakr.onrender.com](https://foodmine-eakr.onrender.com/)

Repository: [https://github.com/amirsohail66/FoodieCart](https://github.com/amirsohail66/FoodieCart)

## Features

- **User Authentication**: Secure login system for customers.
- **Product Catalog**: Browse through a variety of food items.
- **Shopping Cart**: Add items to cart and manage quantities.
- **Checkout Process**: Smooth and intuitive checkout experience.
- **Payment Integration**: Secure payment processing with PayPal and card payments.
- **Order Confirmation**: Customers receive order ID and confirmation after successful payment.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: Angular
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Stack**: MEAN (MongoDB, Express.js, Angular, Node.js)
- **Payment Processing**: PayPal API
- **Hosting**: Render.com

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/amirsohail66/FoodieCart.git
   cd FoodieCart
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```
   DATABASE_URL=your_mongodb_connection_string
   PAYPAL_CLIENT_ID=your_paypal_client_id
   PAYPAL_SECRET=your_paypal_secret
   ```

4. Run the application:
   ```
   npm start
   ```

## Usage

1. Register for an account or log in if you already have one.
2. Browse the food items available in the catalog.
3. Add desired items to your cart.
4. Proceed to checkout when ready to place an order.
5. Choose your preferred payment method (PayPal or card).
6. Complete the payment process.
7. Receive order confirmation with your order ID.

## Deployment

This project is hosted on Render.com. To deploy your own instance:

1. Create a new Web Service on Render.
2. Connect your GitHub repository.
3. Set the environment variables in the Render dashboard.
4. Deploy the application.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

If you encounter any issues or have questions, please open an issue in this repository or contact our support team at [your-support-email@example.com].
