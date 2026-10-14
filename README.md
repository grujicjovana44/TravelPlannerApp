# Travel Planner — Mobile Computing

A hybrid mobile application for planning and organizing trips, developed as part of the Mobile Computing course at the Faculty of Organizational Sciences (FON).

## 🌍 About the Project

Travel Planner helps users organize their trips by selecting countries and cities and managing essential travel details, including accommodation, transportation, travel dates, and expenses.

The central entity of the application is a **Trip**, which connects geographical locations with the user's travel arrangements and logistical information.

The application is built with **Ionic** and **Angular**, while **Firebase Realtime Database** is used for data storage. Authentication and database communication are implemented through Firebase REST APIs and HTTP requests.

## ✨ Features

### 🔐 Authentication
- User registration and login
- Firebase Authentication through the Firebase REST API
- Personal trip management for registered users

### 🧳 Trip Management

The application supports full CRUD (Create, Read, Update, Delete) operations for trips.

- **Create:** Select a country from a predefined list, enter a city, specify departure and return dates, and define transportation and accommodation types and costs.
- **Read:** View planned trips and browse trips grouped by country.
- **Statistics:** View trip statistics.
- **Update:** Edit existing trip details, including destinations, dates, transportation, accommodation, and costs.
- **Delete:** Remove trips from the database.

### 👥 Collaborative Trip Planning
- Add another registered user to a trip.
- Allow invited participants to view shared trip details.
- Enable participants associated with a trip to leave comments.
- Support collaborative trip planning and information sharing.

### 💰 Travel Expense Tracking
- Record transportation costs.
- Record accommodation costs.
- Keep travel details and expenses organized within each trip.

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| Ionic | Hybrid mobile application framework |
| Angular | Frontend framework and application architecture |
| TypeScript | Application development and type safety |
| Firebase Realtime Database | Data storage and synchronization |
| Firebase Authentication REST API | User authentication |
| REST API / HTTP | Communication with Firebase services |
| Git and GitHub | Version control and source code management |

## 🏗 Application Architecture

The application uses Ionic and Angular to provide the mobile user interface and application logic. Firebase provides the backend services for authentication and data storage.

Communication with Firebase is performed through HTTP requests using REST APIs.

The main application entity is **Trip**, which contains travel information such as:
- Destination country and city
- Start and end dates
- Transportation type and cost
- Accommodation type and cost
- Associated users and trip comments

## 🚀 Getting Started

### Prerequisites
- Node.js and npm
- Ionic CLI
- A Firebase project with the required services configured
- Git

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
```

Replace the placeholders with the actual repository URL and directory name.

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Firebase

Create or configure a Firebase project and enable the services required by the application.

Configure the Firebase connection settings according to the project's existing configuration files. Use your own Firebase project credentials and avoid committing private secrets or sensitive configuration values.

### 4. Run the Application

Start the development server using the command supported by the project's configuration:

```bash
ionic serve
```

The application will be available at the local address displayed in the terminal.

For mobile device testing or building, refer to the Ionic CLI documentation and the platform configuration included in the project.

## 🎓 Academic Context

This project was developed as part of the **Mobile Computing** course at the **Faculty of Organizational Sciences, University of Belgrade**.

It demonstrates the development of a hybrid mobile application using Ionic and Angular, integration with Firebase REST APIs, user authentication, data management, and collaborative functionality.

## 👩‍💻 Authors

- **Jovana Grujić** — 2022/0376
- **Ana Dobrijević** — 2022/0032
