# RapidCare Backend

Backend server for RapidCare ambulance service application.

## Features

- Real-time ambulance booking with Socket.io
- MongoDB database integration
- RESTful API endpoints
- Driver and patient management
- Live location tracking

## Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.io
- CORS enabled

## Environment Variables

Create a `.env` file with:

```
PORT=5001
MONGODB_URI=your_mongodb_connection_string
NODE_ENV=development
```

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Production

```bash
npm start
```

## API Endpoints

- `/api/patients` - Patient management
- `/api/ambulances` - Ambulance management
- `/api/drivers` - Driver management
- `/api/bookings` - Booking management

## Deployment

Deployed on Vercel with Railway MongoDB.
