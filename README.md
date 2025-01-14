# QuickBite - Backend 🍴

Welcome to the **QuickBite Backend** repository! This is the backend implementation of QuickBite, a platform that connects food enthusiasts with their favorite restaurants.

For the **frontend repository**, please visit: [QuickBite Frontend](https://github.com/PinakGupta/QuickBite-frontend)

---

## ✨ Features

- 🏢 **Restaurant Management**: Backend services for restaurant registration and menu management.
- 👥 **User Management**: APIs for user registration, login, and profile handling.
- 🔍 **Search and Filters**: Backend support for search functionality with location, cuisine, and other filters.
- 💳 **Stripe Payment Integration**: Secure end-to-end payment processing.
- 🔒 **Auth0 Authentication**: Robust authentication and authorization using Auth0.
- ☁️ **Cloudinary Integration**: Image storage and retrieval for menus and profiles.
- 📊 **Order Management**: APIs for placing, updating, and tracking food orders.

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB (local or cloud instance)
- Stripe and Auth0 accounts for integration

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/PinakGupta/QuickBite-backend.git
   ```

2. Navigate to the project directory:

   ```bash
   cd QuickBite-backend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add the following environment variables:

   ```env
   MONGO_URI=your_mongodb_connection_string
   STRIPE_SECRET_KEY=your_stripe_secret_key
   AUTH0_DOMAIN=your_auth0_domain
   AUTH0_CLIENT_ID=your_auth0_client_id
   AUTH0_CLIENT_SECRET=your_auth0_client_secret
   CLOUDINARY_URL=your_cloudinary_url
   ```

5. Start the development server:

   ```bash
   npm start
   ```

   The server will be running on [http://localhost:5000](http://localhost:5000).

---

## 🛠️ Technologies Used

- **Node.js** 🟢: Backend runtime environment
- **Express.js** 🚀: Web framework for building APIs
- **MongoDB** 🍃: NoSQL database for storing data
- **Stripe API** 💳: For secure payment processing
- **Auth0** 🔒: Authentication and authorization
- **Cloudinary** ☁️: Image storage and management

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Stripe API for secure payment processing.
- Auth0 for authentication services.
- Cloudinary for image storage.
- Open source libraries and frameworks that made this project possible.

---

Feel free to open issues or suggest improvements. Enjoy using QuickBite! 🍽️
