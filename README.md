# Chatly - Real-Time Chat Application 🚀

Chatly is a real-time chat application built using **React.js** for the frontend and **Golang** for the backend. It utilizes **WebSockets** for instant messaging and integrates with **PostgreSQL** for database management. The application supports user search, theme selection, profile customization, and mobile adaptation.

## ✨ Features
- 🔍 **[User Search](#features)** - Find users in the system and start chatting instantly.
- 💬 **[Real-Time Chat](#features)** - Instant messaging powered by **WebSockets**.
- 🎨 **[Theme Selection](#features)** - Customize the UI with dark/light themes.
- ⚙️ **[Settings & Profile Customization](#features)** - Update user information and preferences.
- 📱 **[Mobile Adaptation](#features)** - Fully responsive design for a seamless mobile experience.

## 🛠 Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Golang, WebSockets
- **Database:** PostgreSQL
- **Tools:** Node.js, Go

## 🔧 Installation
### [Frontend Setup](#frontend-setup)
Ensure you have **Node.js** installed, then run the following commands:

```bash
cd frontend
npm install
npm run dev
```

### [Backend Setup](#backend-setup)
Ensure you have **Go** installed, then run:

```bash
cd backend
go mod tidy
go run main.go
```

### [Database Setup](#database-setup)
Make sure **PostgreSQL** is installed and running. Create a database and update your **backend configuration** accordingly.

## 🚀 [Usage](#usage)
1. Start the **PostgreSQL** database.
2. Run the **backend** with:
   ```bash
   go run main.go
   ```
3. Run the **frontend** with:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser and start chatting!

---

🚀 Happy Coding! 🎉

