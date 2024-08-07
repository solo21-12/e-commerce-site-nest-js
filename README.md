# E-Commerce Site

A robust e-commerce platform built with NestJS and MongoDB.

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

   Create a `.env` file in the root directory with the following variables:

   ```env
   MONGODB_URL=mongodb://localhost:27017/ecommerce
   MONGODB_DATABASE_NAME=your_database_name
   MONGODB_PASSWORD=your_password
   JWT_SECRET=your_jwt_secret
   SESSION_KEY=your_session_key
   CLIENT_URL=http://localhost:3000
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   CLOUDINARY_NAME=your_cloudinary_name
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

## Contributing

1. Fork the repo.
2. Create a branch for your changes.
3. Submit a pull request.
