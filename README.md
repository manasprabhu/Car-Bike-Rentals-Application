# Car-Bike-Rentals-Application

## Description
Car-Bike-Rentals-Application is a modern web application built with React and Google Firebase. It provides a seamless platform for users to rent cars and bikes with ease. The application supports responsive design, user authentication, and efficient state management, making it a robust solution for vehicle rental services.

## Features
- **Responsive Design**: Built with React Bootstrap and SASS to ensure the application works on all device sizes.
- **Client and Server-Side Routing**: Managed using React Router Dom v6.
- **Global State Management**: Powered by React Redux and persisted using React Persist.
- **User Authentication and Data Management**: Utilizes Google Firebase for authentication, Firestore for database, and Firebase Storage for file management.
- **Interactive UI**: Enhanced with Sweetalert2 for custom alerts and pop-ups.

## Modules Used
- **React Bootstrap & SASS**: For responsive development.
- **React Router Dom v6**: For routing.
- **React Redux**: For global state management.
- **React Persist**: For persisting Redux state.
- **Google Firebase**: For user authentication, Firestore database, and file storage.
- **Sweetalert2**: For custom popups.

## Screenshots
### Car Reservation
![Car Reservation](reservation)

### User/Admin Login/Sign-up
![User/Admin Login/Sign-up](login)

### My Rentals
![My Rentals](rentals)

### Cars Management (Admin)
![Cars Management (Admin)](cars-management)

### Rentals Management (Admin)
![Rentals Management (Admin)](rentals-management)

### Vehicle Model Management (Admin)
![Vehicle Model Management (Admin)](model-management)

## Project Videos
### Rent a Car Application Overview
- [Watch here](Rent-a-Car.mp4)

### User & Vehicle & Location Management
- [Watch here](User-Vehicle-Location-Management.mp4)

### Rentals Management (Admin)
- [Watch here](Admin-Rental-Management.mp4)

### Contact Form Management
- [Watch here](Contact-Form-Management.mp4)

### Firebase Structure
- [Watch here](Firebase-Structure.mp4)

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/car-bike-rentals-application.git
   cd car-bike-rentals-application
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Setup Firebase:**
   - Create a Firebase project and add a web app.
   - Copy your Firebase config object and paste it into a `.env` file in the root of your project:
     ```
     REACT_APP_FIREBASE_API_KEY=your-api-key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
     REACT_APP_FIREBASE_PROJECT_ID=your-project-id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     REACT_APP_FIREBASE_APP_ID=your-app-id
     ```

4. **Start the development server:**
   ```bash
   npm start
   ```

5. **Open your browser and navigate to:**
   ```
   http://localhost:3000
   ```

## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any improvements or bug fixes.
