# 🔐 Secrets Project

A web application that allows users to register, log in, and anonymously submit secrets. Features secure authentication using **sessions** and **Google OAuth 2.0**.


## 🧰 Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS Templating
- **Authentication**: Google OAuth 2.0, Express Session, Passport.js
- **Database**: PostgreSQL
- **Other Tools**: dotenv, bcrypt

---

## 🔑 Features

- 📝 Anonymous Secret Sharing
- 🔐 Session-Based Login
- 🔗 Google OAuth 2.0 Integration
- 👤 User Registration & Login with PostgreSQL storage
- 🗝️ Secrets accessible only after authentication

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/parthjadav26/Secrets-Project.git
   cd Secrets-Project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure PostgreSQL**
   - Create a database (e.g., `secrets_db`)
   - Set your `.env` file:
     ```env
     DATABASE_URL=postgres://user:password@localhost:5432/secrets_db
     CLIENT_ID=your_google_client_id
     CLIENT_SECRET=your_google_client_secret
     SESSION_SECRET=your_session_secret
     ```

4. **Run database migrations (if using Sequelize)**
   ```bash
   npx sequelize-cli db:migrate
   ```

5. **Start the server**
   ```bash
   node app.js
   ```

6. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## 📸 Screenshots

### 🏠 Home Page
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/92fdb371-71af-4108-ac71-99abb6099401" />


### 📝 Register Page
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/750e7c63-d30f-40b9-b9bb-ab0dcece59e4" />

### 🔓 Login Page
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3e8a7c2b-b5f6-4087-9f47-3120e7b3fafc" />

### 🔓 Secrets Page
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1dba0c64-72e4-4261-9d5c-a6df8b368c23" />



---

## 📄 License

This project is licensed under the MIT License.

---

> Developed by **Parth Jadav** 🚀
