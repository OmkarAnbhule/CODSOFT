# UrbanCart E-commerce Website

UrbanCart is an e-commerce platform designed to provide a seamless shopping experience for users looking to purchase a variety of products online. This README.md file provides an overview of the project, its features, technologies used, installation instructions, API endpoints (if applicable), directory structure, and other relevant information.

## Features

- **Product Catalog**: Browse a wide range of products categorized by type, brand, or other criteria.
- **User Authentication**: Register, log in, and manage user accounts.
- **Shopping Cart**: Add products to a cart for purchasing.
- **Checkout Process**: Secure checkout flow for completing purchases.
- **Order Management**: View order history and manage orders.
- **Search and Filters**: Search products and apply filters to find specific items.
- **Admin Dashboard**: Admin interface for managing products, orders, and users (if applicable).

## Technologies Used

- **Frontend**: React with Redux (State Management)
- **Backend**: Node.js with Express
- **Database**: MongoDB (MongoDB Atlas for cloud hosting)
- **Payment Gateway**: Stripe or other payment processing integration
- **Authentication**: JWT (JSON Web Tokens)
- **UI Framework**: Bootstrap or Tailwind CSS

## Installation

1. **Clone Repository**

   ```bash
   git clone https://github.com/OmkarAnbhule/CODSOFT.git
   
2. **Setup Frontend**
   ```bash
   cd client
   npm install

3. **Setup Backend**
   ```bash
   cd ../server
   npm install
   
4. **Configure Environment Variables**
   ```makefile
   PORT=5000
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
Replace your_mongodb_uri, your_jwt_secret, your_cloudinary_* with your actual MongoDB URI, JWT secret, Cloudinary credentials respectively.

5. **Run Application**
   *Start Frontend*
     ```bash
     cd client
     npm run dev
  
  *Start Backend*
    ```bash
    cd ../server
    node index.cjs
    
7. **Access Application**
  Open your web browser and go to http://localhost:5173 to view the application.

## License
  This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
**React with Vite** - for building the frontend.
**Node.js with Express** - for building the backend API.
**MongoDB** - for database storage (MongoDB Atlas for cloud hosting).
**Cloudinary** - for media management and image uploads.
## Author
 - Omkar Suresh Anbhule
 - GitHub: https://github.com/OmkarAnbhule
