# Database Setup

This project uses MongoDB as the database for the MERN application.

## Option 1: Local MongoDB

1. Install MongoDB Community Edition.
2. Start the MongoDB service.
3. The application is configured to use:
   mongodb://127.0.0.1:27017/factoryMaintenanceDB

## Option 2: MongoDB Atlas

1. Create a free cluster on MongoDB Atlas.
2. Get the connection string.
3. Replace the MONGO_URI in the backend .env file.

Example:

MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/factoryMaintenanceDB?retryWrites=true&w=majority

## Database Schema Included

- Machines
- SpareParts
- MaintenanceSchedules
- Suppliers
- ServiceHistory

## Notes

If MongoDB is not running, the backend will fail to connect and the server will exit.
