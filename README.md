# Equipment Reservation and Management System

## Overview

Welcome to the Equipment Reservation and Management System! This is a robust solution designed to simplify equipment management, allowing administrators to seamlessly add equipment, while users can easily reserve and rent it. The system enforces intelligent restrictions, ensuring a smooth experience for all users.

### Key Features

- **User Roles:** Two distinct roles - administrators with equipment management privileges, and regular users with reservation capabilities.
- **Technologies Used:** React, Node.js/Express, and MongoDB, all intricately connected to provide a seamless experience.
- **Responsive Design:** The system is designed to be responsive across different screen resolutions.
- **Authentication:** Access is restricted to authenticated users, ensuring data security.

## Requirements

### Common User Actions

All users, regardless of their role, can:

- View the list of available equipment.
- Access detailed information about specific equipment.

### Administrator Actions

Administrators have additional privileges:

- Create and update equipment entries.
- Change equipment status (e.g., from draft to not draft).
- Monitor all reservations.
- Approve, disapprove, or mark reservations as rented.

### Regular User Actions

Regular users can:

- View their reservation history.
- Create new reservations.
- Modify reservation details (e.g., change dates).
- Cancel reservations.

## Getting Started

To run the project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/geleg/equipment-reservation-system.git
   ```

2. **Install Dependencies:**
   - Navigate to the frontend folder:
     ```bash
     cd frontend
     npm install
     ```
   - Navigate to the server folder:
     ```bash
     cd server
     npm install
     ```

3. **Set Up MongoDB:**
   - Ensure you have MongoDB installed and running.
   - Configure the MongoDB URI in the server's .env file.

4. **Configure Authentication:**
   - Set up authentication settings.
   - Create a .env file in the server folder and add the following variables:
     - `PORT=your_port`
     - `URI=your_mongodb_uri`
     - `SECRET=your_jwt_secret`

5. **Run the Application:**
   - In the server folder, run:
     ```bash
     npm run dev
     ```
   - In the frontend folder, run:
     ```bash
     npm start
     ```

## Contributors

A big shoutout to our awesome contributors who made this project possible:

- [geleg](https://github.com/geleg)
- [justegu](https://github.com/justegu)
- [dashkens](https://github.com/dashkens)
- [GytisMal](https://github.com/GytisMal)
- [Dj50Grosh](https://github.com/Dj50Grosh)
- [OlgaNovickova](https://github.com/OlgaNovickova)

Feel free to explore, contribute, and make this project even better! 🚀
