# BlinkIt Clone - Full Stack E-commerce Application

A full-stack e-commerce application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that mimics core functionalities of BlinkIt.

## 🚀 Features

- User authentication and authorization
- Product browsing and searching
- Shopping cart management 
- Order processing with Stripe integration
- Address management
- Email notifications
- Responsive design with Tailwind CSS

## 🛠️ Tech Stack

### Frontend
- React.js with Vite
- Redux for state management
- Tailwind CSS for styling
- ESLint for code quality

### Backend
- Node.js with Express
- MongoDB with Mongoose
- JWT for authentication
- Stripe for payments
- Cloudinary for image storage
- Resend for email services

## 🏃‍♂️ Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/blinkit-clone.git
```

2. Install frontend dependencies:
```bash
cd client
npm install
```

3. Install backend dependencies:
```bash
cd server
npm install
```

4. Create .env files:

For client/.env:
```env
VITE_SERVER_URL=your_server_url
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

For server/.env:
```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
RESEND_API_KEY=your_resend_api_key
```

### Running the Application

1. Start the backend server:
```bash
cd server
npm run dev
```

2. Start the frontend development server:
```bash
cd client
npm run dev
```

## 📝 License

This project is licensed under the ISC License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👨‍💻 Author

Your Name
- GitHub: [@yourusername](https://github.com/yourusername)
