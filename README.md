# HomeHubServer

Core backend server for smart home automation and monitoring system. Handles device control, data collection, and client communications.

## Requirements

- Node.js 20+
- MongoDB 7.0+
- Redis 7.0+

## Setup

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Start development server
npm run dev

# Start production server
npm run start
```

## Features

- REST API for device control
- Real-time device state updates
- User authentication
- Device state persistence
- Integration with Homebridge
- Environmental monitoring
- Activity tracking
- Media streaming control

## Project Structure

```
src/
├── api/          # API routes
├── config/       # Configuration files
├── controllers/  # Request handlers
├── models/       # Database models
├── services/     # Business logic
├── types/        # TypeScript types
└── utils/        # Helper functions
```

## API Documentation

API documentation available at `/api/docs` when running in development mode.

## Development

Development setup recommended on macOS or Linux. Built using TypeScript for type safety and better development experience.

## Deployment

Designed to run on Linux (Ubuntu recommended) in a VM environment with Node.js process manager (PM2).
