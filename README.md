
# Bonhomie Event Management - Backend

This repository contains the backend code for the **Bonhomie Event Management** website, developed to streamline registrations and manage events related to sports, technical, and cultural activities held at our college. The backend is built using **Node.js** and **Express.js**, providing a robust and scalable API.

## About Bonhomie

**Bonhomie** is an annual event held at our college that brings together students and faculty to celebrate sports, technical, and cultural excellence. The event fosters camaraderie, teamwork, and creativity, offering a platform for students to showcase their talents and skills in various domains. 

Bonhomie features:
- **Sports Events**: Competitions like football, cricket, basketball, and other games promoting athleticism and teamwork.
- **Technical Events**: Coding challenges, hackathons, and robotics competitions that encourage innovation and technical expertise.
- **Cultural Events**: Activities like singing, dancing, art competitions, and drama performances that celebrate creativity and cultural heritage.

The **Bonhomie Event Management Website** simplifies the process of registering for events, ensuring smooth communication and coordination between organizers and participants.

## Features

- RESTful API for handling event registration and management.
- Secure and efficient handling of user data.
- Supports sports, technical, and cultural event categories.
- Integration with MongoDB for seamless data storage.
- Middleware for validation and error handling.

## Technologies Used

- **Node.js**: JavaScript runtime for building server-side applications.
- **Express.js**: Framework for creating RESTful APIs.
- **MongoDB**: NoSQL database for storing event and user data.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB.
- **JWT**: For secure authentication and session management.

## Related Repositories

- **Frontend Repository**: [Bonhomie Frontend](https://github.com/LabbaiIrfan/bonhomie-frontend

## Hosted Website

- **Live Website**: [Bonhomie Event Management](https://bonhomie.aiktc.ac.in/)

## Installation and Setup

Follow these steps to set up the backend locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-backend-repo-link
   cd bonhomie-backend
   ```

2. **Install Dependencies**:
   Run the following command to install all required dependencies:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add the following:
   ```
   PORT=5000
   MONGO_URI=your-mongodb-connection-string
   JWT_SECRET=your-jwt-secret
   ```

   - Replace `PORT` with the desired port for the backend server (default is 5000).
   - Replace `MONGO_URI` with your MongoDB connection URL (local or Atlas).
   - Replace `JWT_SECRET` with a secret key for JWT.

4. **Start the Server**:
   Run the following command to start the development server:
   ```bash
   npm start
   ```

5. **Access the API**:
   The backend server will be running at `http://localhost:5000`.

6. **Database Setup**:
   - Ensure MongoDB is running locally or use a cloud-based MongoDB service like [MongoDB Atlas](https://www.mongodb.com/atlas).
   - Use the `MONGO_URI` in the `.env` file to connect to your MongoDB database.

## Contribution

Contributions are welcome! If you'd like to improve the project or fix any issues, feel free to fork the repository and submit a pull request.

## Contact

For any queries or feedback, feel free to reach out:

- **Email**: Labbaiirfan955@gmail.com
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/irfan-labbai-5085a0288/)

---

Thank you for checking out this project!

