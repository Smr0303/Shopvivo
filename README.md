# Responsive E-Commerce Platform

## Overview
This project is a responsive e-commerce platform developed to provide a comprehensive shopping experience. It features multi-tiered authorization for secure access, utilizes modern technologies for efficient development, and ensures seamless integration between frontend and backend components.

## Features
- **Responsive Design**: Optimized for various devices to ensure a consistent user experience.
- **Multi-Tiered Authorization**: Secure access control with roles such as Admin, Seller, and Customer.
- **State Management**: Implemented Redux for centralized state management across the application.
- **Image Management**: Integrated Cloudinary for efficient image upload, storage, and retrieval.
- **Database**: MongoDB used for data storage, ensuring scalability and performance.

## Technologies Used
- **Frontend**: React.js for building dynamic user interfaces.
- **Backend**: Node.js and Express.js for server-side logic and API development.
- **Database**: MongoDB for data storage and retrieval.
- **State Management**: Redux for managing global state in the frontend.
- **Image Storage**: Cloudinary for handling image uploads and storage.
- **Authentication**: JWT-based authentication for secure user sessions.

### Installation
1. **Clone the Repository**
   ```sh
   git clone [https://github.com/yourusername/ecommerce-platform.git](https://github.com/Smr0303/Shopvivo.git)
   cd ecommerce-platform
   npm install
   
2. Now for installing packages for frontend do

   ```sh
    cd frontend
    npm install
    cd ..
4. Set Up Environment Variables
   
   ```sh
       PORT
       DB_URI 
       STRIPE_API_KEY
       STRIPE_SECRET_KEY
       JWT_SECRET
       JWT_EXPIRE
       COOKIE_EXPIRE
       SMPT_SERVICE 
       SMPT_MAIL
       SMPT_PASSWORD
       SMPT_HOST
       SMPT_PORT
       CLOUDINARY_NAME
       CLOUDINARY_API_KEY
       CLOUDINARY_API_SECRET
   
6. Run the Application
   
   ```sh
       npm start
8. Access the Application
   
   ```sh
      Open your browser and navigate to http://localhost:PORT    
