# E-Commerce Deck

A modern e-commerce website built with Node.js, Express, and MongoDB.

## Features

- User authentication (login/register)
- Product listing and details
- Shopping cart functionality
- Checkout process
- Responsive design with Bootstrap 5

## Technologies Used

- Node.js
- Express.js
- MongoDB
- EJS (Embedded JavaScript templating)
- Bootstrap 5
- express-session for session management

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables in `.env` file
4. Start the development server: `npm run dev`
5. Visit `http://localhost:3000` in your browser

## Project Structure

```
ecommerce-website/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── views/
│   ├── public/
│   ├── middleware/
│   ├── config/
│   ├── utils/
│   └── server.js
├── package.json
└── README.md
```

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
PORT=3000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
```

## License

This project is licensed under the MIT License.