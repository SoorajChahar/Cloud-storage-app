📦 Cloud Storage App

A simple, secure, and user-friendly cloud storage web application that allows users to upload, manage, and download their files from anywhere.


---

🚀 Features

✅ User authentication (sign up, login, logout)
✅ Upload and store files securely
✅ Download your files anytime
✅ Delete files
✅ Responsive and intuitive UI
✅ File size/type validation


---

🛠️ Tech Stack

Backend: Node.js, Express

Frontend: HTML, CSS, JavaScript

Database: MongoDB (or SQL — adjust as applicable)

Storage: Local server filesystem / AWS S3 

Authentication: Passport.js / JWT 



---

🧑‍💻 Getting Started

Prerequisites

Node.js & npm

MongoDB or other database



---

Clone the repo

git clone https://github.com/surajsinghchhonkar/cloud-storage-app.git
cd cloud-storage-app


---

Install dependencies

npm install


---

Environment variables

Create a .env file in the root directory with the following variables (example):

PORT=3000
DB_URI=mongodb://localhost:27017/cloud-storage
JWT_SECRET=your_secret_key

Adjust values as needed for your environment.


---

Run the app

npm start

Then visit http://localhost:3000 in your browser.

