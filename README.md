# 🏨 Student Hostel Management Portal

A full-stack web application designed to streamline hostel management for students. This project includes a dynamic frontend built with Angular, a robust backend using Node.js and Express, and MongoDB for database operations.

## 🚀 Features

* 🔐 **User Authentication**: Secure signup and login for students.
* 🏠 **Room Listings**: Browse available boys’ and girls’ hostel rooms with images and pricing.
* 📝 **Complaint Management**: Submit and track previous complaints directly from the portal.
* 💬 **Contact History**: View past contact messages and replies.

## 🛠️ Tech Stack

* **Frontend**: Angular
* **Backend**: Node.js + Express.js
* **Database**: MongoDB
* **Authentication**: JWT-based
* **Others**: Nodemon, MongoDB Compass, .env configuration

## 📂 Project Structure

```
HostelManagementSystem/
├── server/                 # Backend APIs (controllers, models, routers, etc.)
├── src/                   # Angular frontend (components, modules, etc.)
├── .env                   # Environment configuration file
├── package.json           # Node dependencies
├── README.md              # Project documentation
└── ...other config files
```

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/hostel-management-portal.git
   ```

2. **Navigate and Install Dependencies**

   ```bash
   cd hostelManagement
   npm install
   ```

3. **Create ****`.env`**** File**

   * Copy the content from `.env.sample` into a new file named `.env`.

4. **Start MongoDB**

   * Open MongoDB Compass and ensure the `hostel` database is accessible.

5. **Run Project**

   * Open **two terminals** inside the project directory.

   **Terminal 1 (Frontend)**

   ```powershell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   $env:NODE_OPTIONS="--openssl-legacy-provider"
   npm run start
   ```

   **Terminal 2 (Backend)**

   ```powershell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   npm run server
   ```

6. **Access Application**

   ```
   http://localhost:4200/
   ```

## 📌 Notes

> ✅ Do **not** upload the `node_modules/` folder to GitHub. Add it in your `.gitignore` file.

## 👤 Author

> Developed by Mahesh Babu Nettem
> [LinkedIn](www.linkedin.com/in/mahesh-babu-nettem-654065356) | [GitHub]([https://github.com/your-username](https://github.com/hackermahesh03))
