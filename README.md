# Vehicle-Tracking-System

Welcome to the **Vehicle-Tracking-System** repository! This project provides a comprehensive solution for real-time tracking and management of vehicles. It includes features such as live location tracking, route optimization, and alerts for various events.

## Features

- **Live Location Tracking**: Monitor the real-time location of vehicles.
- **Route Optimization**: Calculate the most efficient routes for vehicles.
- **Alerts and Notifications**: Receive alerts for events such as speeding, geofence breaches, and maintenance schedules.
- **Historical Data**: Access and analyze past location and route data.
- **User Management**: Role-based access control for administrators, drivers, and users.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies

- **Frontend**: React.js, Leaflet, Material-UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: WebSocket
- **Mapping and Geolocation**: OpenStreetMap, Leaflet

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/vehicle-tracking-system.git
   cd vehicle-tracking-system
   ```

2. **Install backend dependencies**:
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**:
   ```bash
   cd ../frontend
   npm install
   ```

4. **Configure the environment**:
   - Ensure MongoDB is installed and running.
   - Create a `.env` file in the `backend` directory with the appropriate settings.

5. **Start the backend**:
   ```bash
   cd backend
   npm start
   ```

6. **Start the frontend**:
   ```bash
   cd ../frontend
   npm start
   ```

## Usage

1. Navigate to `http://localhost:3000` in your browser.
2. Register or log in as a user.
3. Add vehicles and start tracking their locations.

## License

This project is licensed under the MIT License – see the [LICENSE.md](LICENSE.md) file for details.
