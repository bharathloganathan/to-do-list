# 📝 Todo App — Hackathon Project Submission
A full-stack web application to manage personal or professional tasks. Users can add, edit, delete, and view their tasks with associated deadlines and status updates.

---

## 🌐 Hosted Links

- Frontend: [https://bharathloganathan.github.io/to-do-list-frontend/](https://bharathloganathan.github.io/to-do-list-frontend/)
- Backend: [https://to-do-list-backend-production-dd7e.up.railway.app/](https://to-do-list-backend-production-dd7e.up.railway.app/)
- Project Demo Video: [Watch here](https://drive.google.com/file/d/1cl4DVcfjBA_FZn4RBW_-ZEGB7SFUdHQ5/view?usp=drive_link)

---

## ⚙ Tech Stack

| Layer       | Technology Used                     |
|-------------|-------------------------------------|
| Frontend    | React.js, CSS                       |
| Backend     | Node.js, Express.js                 |
| Database    | MySQL                               |
| Hosting     | GitHub Pages (Frontend), Railway (Backend) |

---


## 📦 Folder Structure


root
│
├── client/                         
│   ├── public/                    
│   └── src/                       
│       ├── components/            
│       │   ├── TaskForm.js       
│       │   └── TaskList.js        
│       ├── App.css                
│       ├── App.js                 
│       ├── index.css              
│       └── index.js               
│
│   ├── config/                    
│   ├── controllers/              
│   │   └── task.controller.js
│   ├── middlewares/              
│   │   └── error.js
│   ├── models/                   
│   │   ├── index.js
│   │   └── task.model.js
│   ├── routes/                   
│   │   └── task.routes.js
│   └── app.js                    
│
├── README.md                     
└── .env                        



---

## 🚀 Setup Instructions

### 1. Clone the repository

bash
git clone https://github.com/bharathloganathan/to-do-list.git
cd to-do-list


### 2. Setup Frontend

bash
cd client
npm install
npm run build


### 3. Setup Backend

bash
cd server
npm install
npm start




---

## 📌 Assumptions

- User maintains a personal todo list stored securely in MySQL.
- Tasks are simple text entries with timestamps and completion status.
- No push notifications or reminders are included in this MVP.

---

## 📽 Demo Video

🎥 [Click here to watch the demo](https://drive.google.com/file/d/1cl4DVcfjBA_FZn4RBW_-ZEGB7SFUdHQ5/view?usp=drive_link)

---

## 🤖 AI Tool Usage

- ChatGPT was used to:
  - Refactor backend APIs
  - Draft the README structure
  - Suggest modular file structuring
- All prompt logs are retained and can be shown in the final interview.

---

## ✅ Final Submission Highlights

- ✅ Fully deployed and functional
- ✅ Responsive user interface
- ✅ Clean, scalable codebase
- ✅ Architecture and demo video included

---

### This project is a part of a hackathon run by [https://www.katomaran.com](https://www.katomaran.com)