# Freelancing Platform – MERN Stack

A full-stack freelance job portal that connects clients with skilled freelancers for seamless collaboration. This platform enables project posting, bidding, communication, and project submission — all with real-time updates and role-based workflows.

---

## 🚀 Features

### 👨‍💼 For Clients
- Post and manage freelance projects
- Browse freelancer profiles
- Receive and manage proposals
- Chat securely with freelancers
- Review and approve work submissions

### 👨‍🎨 For Freelancers
- Create and update professional profiles
- Explore available freelance projects
- Submit competitive bids
- Communicate with clients in real-time
- Submit completed work and track payments

### 🛡️ For Admin
- Monitor users and project activity
- Enforce platform policies
- Facilitate dispute resolution

---

## 🧱 Tech Stack

| Layer       | Tech Used                               |
|-------------|------------------------------------------|
| Frontend    | React.js, Bootstrap, Material UI, Axios |
| Backend     | Node.js, Express.js, Socket.IO          |
| Database    | MongoDB (with Mongoose)                 |
| Auth        | Bcrypt (Password Hashing)               |

---

## 📂 Folder Structure

```
freelancer-platform/
├── client/             # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── public/
├── server/             # Express backend
│   ├── index.js
│   ├── Schema.js
│   └── SocketHandler.js
```

---

## ⚙️ Installation

### Prerequisites

- Node.js and npm: [Install](https://nodejs.org/)
- MongoDB (local or Atlas): [Install](https://www.mongodb.com/)
- Git (optional): [Install](https://git-scm.com/)
- Visual Studio Code (recommended): [Install](https://code.visualstudio.com/)

---

### Backend Setup

```bash
cd server
npm install
```

Ensure MongoDB is running locally (`mongodb://localhost:27017/Freelancing`)  
or update the connection string in `index.js`.

---

### Frontend Setup

```bash
cd client
npm install
```

---

### Run the App

Open **two terminals**:

**1. Backend (Port 6001):**
```bash
cd server
npm start
```

**2. Frontend (Port 3000):**
```bash
cd client
npm start
```

Navigate to:  
**`http://localhost:3000`**

---

## 🔑 Key API Routes

| Route                          | Method | Description                        |
|--------------------------------|--------|------------------------------------|
| `/register`                   | POST   | User registration                  |
| `/login`                      | POST   | User login                         |
| `/fetch-projects`            | GET    | Retrieve all available projects    |
| `/new-project`               | POST   | Client posts a new project         |
| `/make-bid`                  | POST   | Freelancer applies for a project   |
| `/approve-application/:id`   | GET    | Client approves an application     |
| `/submit-project`            | POST   | Freelancer submits final work      |
| `/approve-submission/:id`    | GET    | Client accepts submitted work      |

---

## 📽 Demo & Resources

- 🎬 [Demo Video](https://drive.google.com/file/d/1erdcudF8D00QyHEf0aMKioTAqWa2AjDb/view?usp=sharing)

---


## 🛡️ License

Licensed under the [MIT License](LICENSE).

---

**Build your freelance future with code.** 💼💻
