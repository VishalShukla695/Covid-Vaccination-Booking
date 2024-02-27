# COVID Vaccination Booking System

Welcome to the COVID Vaccination Booking System! This system allows both administrators and users to efficiently manage and book vaccination slots, ensuring a smooth and organized process for everyone involved.

## Features

### Admin Panel
- **Admin Login:** Secure login functionality for administrators.
- **Dashboard:** Interactive dashboard with search functionality for easy navigation.
- **Manage Vaccination Centers:** Add or remove vaccination centers as needed.
- **Dosage Details:** View detailed information about vaccine dosages.

### User Interface
- **User Login and Signup:** User-friendly login and signup process for users.
- **Vaccination Center Search:** Effortlessly search for vaccination centers based on various criteria.
- **Slot Application:** Apply for vaccination slots with ease, simplifying the booking process.

## Technologies Used

This system is built using modern web development technologies to ensure reliability, scalability, and user-friendliness:

- **HTML:** For structuring the web pages.
- **CSS:** For styling and enhancing the visual appeal.
- **EJS:** Embedded JavaScript templating for dynamic content generation.
- **Node.js:** Server-side JavaScript runtime for building scalable applications.
- **Express.js:** Web application framework for Node.js, providing robust features for web development.
- **MongoDB:** A NoSQL database for storing application data.
- **Mongoose:** An elegant MongoDB object modeling tool for Node.js.

## Installation

Follow these simple steps to get the COVID Vaccination Booking System up and running on your local machine:

1. **Clone the Repository:**
   ```
   git clone https://github.com/VishalShukla695/Covid-Vaccination-Booking
   ```

2. **Install Dependencies:**
   ```
   cd Covid-Vaccine-Booking
   npm install
   ```

3. **Set Up MongoDB:**
   - Install MongoDB if not already installed.
   - Create a `.env` file in the root directory and add your MongoDB connection string:
     ```
     MONGODB_URI=your_mongodb_connection_string
     ```

4. **Start the Application:**
   ```
   npm start
   ```

5. **Access the Application:**
   Open your web browser and navigate to `http://localhost:3000` to access the system.

## Usage

### Admin Panel:
- Access the admin login page at `/admin/login`.
- After logging in, manage vaccination centers, view dosage details, and perform administrative tasks.

### User Interface:
- Access the user login page at `/user/login` to log in or sign up.
- Once logged in, search for vaccination centers and apply for available slots.

## Contribution

Contributions to the COVID Vaccination Booking System are highly appreciated! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Thank you for using the COVID Vaccination Booking System. Stay safe and healthy!
