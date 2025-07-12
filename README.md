# CrudEase

**CrudEase** is a simple Node.js and Express-based CRUD (Create, Read, Update, Delete) application using MongoDB and EJS as the templating engine. It allows users to create, view, edit, and delete user records.

---

## 📁 Features

- Create new user entries (name, email, image)
- View all users in a list
- Edit existing user details
- Delete users from the database
- Uses EJS for templating and rendering
- Connected to MongoDB using Mongoose

---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS
- HTML/CSS (static files in `public/`)

---

## 🚀 Getting Started

Follow the instructions below to set up and run the project locally.

### 📦 Prerequisites

- Node.js and npm installed
- MongoDB installed and running locally (or use MongoDB Atlas)

### ⬇️ Clone the Repository

```bash
git clone https://github.com/your-username/CrudEase.git
cd CrudEase

📥 Install Dependencies

npm install

⚙️ Set Up MongoDB

Ensure MongoDB is running locally at the default port. If you're using a different connection string or MongoDB Atlas, update the connection URL in your ./models/user.js or your index.js (whichever connects mongoose).

mongoose.connect("mongodb://127.0.0.1:27017/CrudEase");

▶️ Run the App

node index.js

Or if using nodemon:

npx nodemon index.js

Visit your app at:
📍 http://localhost:3000


---

📁 Project Structure

CrudEase/
├── models/
│   └── user.js
├── public/
│   └── [static files like CSS/images]
├── views/
│   ├── index.ejs
│   ├── read.ejs
│   └── edit.ejs
├── index.js
├── package.json
└── README.md


---

🤝 Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


---

📜 License

This project is open-source and free to use.

Let me know if you also want a sample `user.js` schema or EJS templates.

