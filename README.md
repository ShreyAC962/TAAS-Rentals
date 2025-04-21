# TAAS-Rentals

TAAS RENTALS - MERN Car Booking System with Stripe Payment Integration
This is a fully functional Car Booking System built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with integration of the Stripe Payment Gateway. The application allows users to browse available cars, book them, and complete payments using Stripe. It also features user authentication, a protected routes system, and a simple user interface for managing bookings.

Key Features:
   User authentication (login and register)
   
   Car booking system with availability filters
   
   Stripe Payment Gateway integration
   
   Admin functionality to add, edit, and delete cars
   
   Responsive and modern design with car animations
   
   Continuous Integration and Continuous Delivery (CI/CD) pipelines
   
   Deployment on Google Cloud Platform (GCP) using containers.


### Steps to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/car-booking-system.git
   cd car-booking-system
   ```

2. **Set Up Backend:**
   - Navigate to the `backend` directory:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file and add your MongoDB URI, Stripe secret key, and JWT secret.
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Set Up Frontend:**
   - Navigate to the `frontend` directory:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file and add your backend URL and Stripe public key.
   - Start the frontend server:
     ```bash
     npm start
     ```

4. **Access the Application:**
   Open your browser and go to `http://localhost:3000` to use the app.

---

### Notes:
- Ensure MongoDB is running or use MongoDB Atlas.
- Replace Stripe keys in `.env` files.

---

