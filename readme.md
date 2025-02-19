# Razorpay Clone

A clone of Razorpay's payment gateway system built using the MERN stack. This project replicates key features such as payment processing, transaction history, and API integration for seamless payment handling.

## Features
- User authentication (Sign up, Login)
- Secure payment processing
- Transaction history
- API integration for payments
- Admin dashboard for managing transactions
- Responsive UI

## Tech Stack
- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment Integration:** Razorpay API

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (v16+)
- MongoDB

### Steps to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/razorpay-clone.git
   cd razorpay-clone
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   RAZORPAY_KEY_ID=your_razorpay_key
   RAZORPAY_KEY_SECRET=your_razorpay_secret
   ```
4. Start the backend server:
   ```sh
   npm start
   ```
5. Navigate to the `client` directory and install dependencies:
   ```sh
   cd client
   npm install
   ```
6. Start the frontend:
   ```sh
   npm start
   ```

## API Endpoints
- `POST /api/payments/create` - Initiate a payment
- `GET /api/payments/status/:id` - Check payment status
- `GET /api/transactions` - Get transaction history

## Deployment
To deploy the application:
- Use **Render** or **Vercel** for frontend
- Use **Render** or **AWS EC2** for backend
- Use **MongoDB Atlas** for database

## Contributing
Feel free to fork this repository and submit pull requests.

## License
This project is licensed under the MIT License.

