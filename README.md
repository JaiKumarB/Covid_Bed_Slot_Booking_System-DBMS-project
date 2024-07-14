# DBMS-Covid-Bed-Slot-Booking-Mini Project

## Description
The DBMS-Covid-Bed-Slot-Booking-Mini Project is designed to assist in managing and booking hospital bed slots during the Covid-19 pandemic. This system enables hospitals to efficiently manage bed availability and patients to book beds based on availability.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Database Schema](#database-schema)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The DBMS-Covid-Bed-Slot-Booking-Mini Project is designed to assist in managing and booking hospital bed slots during the Covid-19 pandemic. This system enables hospitals to efficiently manage bed availability and patients to book beds based on availability.

## Features
- User registration and login
- Hospital registration and login
- Booking of hospital bed slots by users
- Real-time bed availability updates by hospitals
- Admin panel for managing users and hospitals
- Secure and efficient database management

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Other Tools:** Git

## Installation
### Prerequisites
- Node.js
- MySQL

### Steps
1. **Clone the repository:**
    ```bash
    git clone https://github.com/JaiKumarB/Covid_Bed_Slot_Booking_System-DBMS-project/blob/main/README.md
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Covid_Bed_Slot_Booking_System-DBMS-project
    ```
3. **Install the required dependencies:**
    ```bash
    npm install
    ```
4. **Set up the database:**
    - Create a MySQL database named `covid_bed_booking`.
    - Import the database schema from the `database/schema.sql` file.
5. **Configure the database connection:**
    - Update the database configuration in `config/db.js` with your MySQL credentials.
6. **Run the application:**
    ```bash
    npm start
    ```

## Usage
1. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.
   
2. **Register and Login:**
   Users and hospitals can register and log in using their respective interfaces.
   
3. **Booking a Bed:**
   Users can search for hospitals and book available bed slots.
   
4. **Updating Bed Availability:**
   Hospitals can update the bed availability in real-time.

## Database Schema
The database schema includes the following tables:
- `users`: Stores user information.
- `hospitals`: Stores hospital information.
- `beds`: Stores bed availability details.
- `bookings`: Stores booking information.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or support, please contact:
- **Name:** [Jai Kumar B]
- **Email:** [jaikumarb031@gmail.com@example.com]
