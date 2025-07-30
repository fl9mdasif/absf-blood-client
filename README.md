## Project BloodHub: A Full-Stack Blood Donation Platform
Welcome to BloodHub, a modern web platform designed to save lives by connecting voluntary blood donors with patients in need across Bangladesh. Our mission is to create a fast, reliable, and community-driven network to address the critical demand for blood.

### 🚀 Live Links
Frontend (React App): https://master.d18ycpe02we2yn.amplifyapp.com

##Backend (Express API):  ([Deployed on Vercel](https://absf-bloodhub-server.vercel.app/)

### ✨ Key Features
BloodHub is equipped with a range of features to provide a seamless experience for both donors and administrators.

### For Users & Donors:
Secure Authentication: Safe user registration and login using JSON Web Tokens (JWT).

### Advanced Donor Search: A powerful search engine to find donors with filters for:

Blood Group, Division, District, and Thana/Upazila, Detailed Donor Profiles: Publicly viewable profiles with essential, non-sensitive information. 
### Blood Request System: An intuitive system for logged-in users to request blood from available donors.

### Personal Dashboard: A dedicated space for users to: View and manage their profile details. Update their donation availability status.Track the status of their sent blood requests.Manage incoming blood requests from others.

## For Admins:
- Role-Based Access: A protected, unified dashboard that provides additional administrative tools.

- Platform Overview: A stats-driven overview of total users, donors, and requests.

- User Management: Full control over the user base, including the ability to:

- View all registered users.

- Update user roles (e.g., promote a user to an admin).

- Activate or deactivate user accounts.

## 🛠️ Technology Stack
BloodHub is built with a modern, decoupled architecture for optimal performance and scalability.

### Frontend (Client-Side)
- Framework: React (Vite)

- Styling: Tailwind CSS

### API Communication: Axios

- Routing: React Router DOM

- Deployment: AWS Amplify

## Backend (Server-Side)
- Framework: Node.js & Express.js

- Database: MongoDB with Mongoose

- Authentication: JWT (jsonwebtoken) & bcryptjs

### Deployment: Vercel (as Serverless Functions)

## Getting Started
To get a local copy up and running, follow these simple steps.

## Installation & Setup
- Clone the Frontend Repository:

```npm
git clone https://github.com/fl9mdasif/absf-blood-client
```

```npm
cd absf-blood-client
npm install
```

- Clone the Backend Repository:
  
```npm
git clone https://github.com/fl9mdasif/absf-blood-server
cd absf-blood-server
npm install
```

### Set Up Environment Variables:

- In the bloodhub-server directory, create a .env file and add the following:

```npm
DATABASE_URL=your_mongodb_connection_string
JWT_ACCESS_SECRET=your_super_secret_jwt_key
PORT=5000
```

In the bloodhub-client directory, update the baseURL in src/api/axios.js to point to your local server:

### src/api/axios.js
-baseURL: 'http://localhost:5000/api',

Run the Application:

Start the backend server:

## In the bloodhub-server directory
```npm
npm run dev
```
Start the frontend client:

## In the bloodhub-client directory
```npm
npm run dev
```

Your application should now be running locally, with the frontend at http://localhost:5173 and the backend at http://localhost:5000.
