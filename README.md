# E-Commerce Site

**E-Commerce Site** is a comprehensive online shopping platform developed using NestJS and MongoDB. It features a robust backend architecture for managing products, orders, and user accounts, providing a scalable and secure solution. With capabilities for product listings, user authentication, and order processing, this platform is designed to deliver a seamless and efficient shopping experience.

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/solo21-12/e-commerce-site-nest-js.git
   cd e-commerce-site-nest-js
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Configure Environment**

   Create a `.env` file with:

   ```env
   MONGODB_PASSWORD=
   MONGODB_DATABASE_NAME
   JWT_SECRET
   MONGODB_URL
   SESSION_KEY
   CLIENT_URL
   CLOUDINARY_API_KEY
   CLOUDINARY_API_SECRET
   CLOUDINARY_NAME
   ```

4. **Run the Application**

   For development:

   ```bash
   npm run start:dev
   ```

   For production:

   ```bash
   npm run build
   npm run start:prod
   ```

5. **Run Tests**

   ```bash
   npm run test
   ```

## Documentation

For detailed API documentation, visit [Postman Documentation](https://documenter.getpostman.com/view/22911710/2sA3rzKt5e).

## Contributing

1. Fork the repo.
2. Create a branch for your changes.
3. Submit a pull request.
