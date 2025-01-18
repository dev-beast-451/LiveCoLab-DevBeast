# LiveCoLab

LiveCoLab is a collaborative real-time application designed to enhance team productivity and streamline workflows. Developed by **Team Dev Beast**, this project combines modern technologies for an efficient, responsive, and scalable platform.

## Team Information
- **Team ID:** Ag61
- **Team Name:** Dev Beast
- **Team Leader:** Yash Agarwal

---

## Project Overview
LiveCoLab aims to provide a seamless collaborative environment leveraging real-time communication and dynamic updates. Built with cutting-edge tools and frameworks, it ensures a modern, high-performance user experience.

---

## Requirements

### Frontend
- **Framework:** ReactJS
- **Real-time Communication:** WebSocket (via Socket.IO)

### Backend
- **Framework:** Spring Boot
- **Language:** Kotlin
- **Build Tool:** Maven

### Database
- **Database:** MongoDB

---

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Node.js and npm (for frontend setup)
- Java (JDK 11 or higher)
- Maven
- MongoDB
- Socket.IO library

### Steps

#### 1. Clone the Repository
```bash
 git clone https://github.com/<your-username>/livecolab.git
 cd livecolab
```

#### 2. Frontend Setup
```bash
cd frontend
npm install
npm start
```

#### 3. Backend Setup
- Navigate to the backend directory:
```bash
cd backend
```
- Build and run the Spring Boot application:
```bash
mvn spring-boot:run
```

#### 4. Database Setup
- Ensure MongoDB is running locally or remotely.
- Update the connection URL in the backend `application.properties` file.

#### 5. WebSocket Configuration
- Ensure Socket.IO server is running and properly configured.

---

## Features
- **Real-time collaboration:** Synchronized updates using WebSocket and Socket.IO.
- **User-friendly interface:** Intuitive design with ReactJS.
- **Scalable backend:** Built with Spring Boot and Kotlin.
- **Efficient data storage:** NoSQL database (MongoDB).

---

## Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes with clear and descriptive messages.
4. Push your changes and create a Pull Request.


---

## Contact
For queries, reach out to **Yash Agarwal** or any team member at **24mt0512@iitism.ac.in**.

