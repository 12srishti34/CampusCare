# CampusCare – Student Mental Wellness & Support Platform

CampusCare is a full-stack web application designed to support students' mental well-being by providing a platform where they can connect with teachers and mentors, track their moods, maintain personal diaries, and participate in stress-relief activities.

##  Key Features

- **Student Dashboard:** A dedicated dashboard for students.
- **Teacher Dashboard:** A separate interface for teachers.
- **Appointment Booking:** Students can book one-to-one sessions with teachers or mentors.
- **Mood Tracker:** Track and monitor daily moods.
- **Dear Diary:** A personal space for students to write their thoughts and feelings.
- **Group Chat:** Enables communication and interaction.
- **Stress Relief Activities:** Interactive games and activities to help students relax.
- **Authentication:** User authentication and role-based access.

##  Tech Stack

### Frontend
- React.js
- Material UI
- Tailwind CSS
- React Router
- Axios
- Recharts

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT Authentication
- bcryptjs

##  Project Structure

```text
CampusCare/
├── backend/
│   ├── config/
│   ├── controller/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── client/
│   ├── public/
│   └── src/
│       ├── Components/
│       └── pages/
│
├── package.json
└── README.md
```

##  Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/12srishti34/CampusCare.git
```

### 2. Navigate to the project folder

```bash
cd CampusCare
```

### 3. Install backend dependencies

```bash
cd backend
npm install
```

### 4. Configure environment variables

Create a `.env` file inside the backend folder and configure the required environment variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Use the variable names required by the backend configuration.

### 5. Start the backend

```bash
npm start
```

### 6. Install frontend dependencies

Open another terminal:

```bash
cd client
npm install
```

### 7. Start the frontend

```bash
npm start
```

##  Project Objective

CampusCare aims to create a supportive digital environment where students can focus on their mental wellness, express themselves, connect with mentors, and access helpful activities.

##  Developed By

**Srishti Chadha**

GitHub: [12srishti34](https://github.com/12srishti34)
