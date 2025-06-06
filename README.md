# Stonks Backend Server

This is the backend server for the Stonks application.

## Setup

1. Install dependencies:

```bash
npm install
```

2. Create a `.env` file in the root directory with the following variables:

```
PORT=3000
API_KEY=your_stock_api_key
FRONTEND_URL=http://localhost:5173
NODE_ENV=development
```

3. Start the server:

```bash
npm start
```

## Available Endpoints

- `GET /health`: Health check endpoint
- `GET /api/key`: Get the API key for stock data (protected)

## Development

The server is configured to work with the Stonks frontend application. It includes:

- CORS configuration for the frontend
- JSON request parsing
- Error handling middleware
- Environment variable management
