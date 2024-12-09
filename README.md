# 🌐 Auth-Nexus 🔐  
**The Ultimate Authentication Solution**  

**Auth-Nexus** is a modern MERN stack authentication system designed with security, efficiency, and user experience in mind. From OTP-based verification to JWT-secured sessions, it has everything to ensure seamless authentication.  

🚀 **[Live Demo](https://auth-nexus.onrender.com)**  

---

## ✨ Key Highlights  

### 🔒 Authentication  
- 📧 **Signup with OTP Verification:** Ensuring secure onboarding.  
- 🔑 **JWT-based Login:** Access your account securely.  
- 🚪 **Logout:** Easy and secure session termination.  

### 📤 Email Features  
- ✅ **Account Verification Emails:** Verify with just a click.  
- 📬 **Welcome Email Template:** Personal touch after verification.  
- 🔄 **Password Reset Link:** Forgot your password? We've got you covered.  

### 🔐 Security Features  
- 🛡️ **Password Encryption:** Using `bcrypt` for top-notch security.  
- 🔑 **Token Management:** Powered by `crypto` and `jsonwebtoken`.  
- 🌍 **CORS-Enabled API:** Secure cross-origin data exchange.  

### 💻 Frontend Features  
- 📄 **Responsive Pages:** Signup, Login, OTP Verification, Email Verification, and Forgot Password.  
- 🛠️ **Protected Dashboard:** Accessible only to authenticated users.  
- ⚡ **Seamless Integration:** Smooth backend communication.  

---

## 🛠️ Tech Stack  

- **Frontend:** React, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Email Service:** Mailtrap  
- **Packages:** `bcrypt`, `cors`, `crypto`, `jsonwebtoken`  

---

## 🚀 Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/MohammedJawwad/Auth-Nexus.git
cd auth-nexus
```
### 2. Install Dependencies
Backend:
```bash
cd backend
npm install
```
Frontend:
```bash
cd ../frontend
npm install
```
### 3. Set Up Environment Variables
Create a .env file in the backend directory with the following:
```bash
MONGO_URI=<Your MongoDB connection string>  
JWT_SECRET=<Your JWT secret>  
MAILTRAP_USER=<Your Mailtrap user>  
MAILTRAP_PASS=<Your Mailtrap password>  
```
### 4. Run the Application
Start the Backend:
```bash
cd backend
npm start
```
Start the Frontend:
```bash
cd ../frontend
npm start
```
### 5. Open the app in your browser: http://localhost:3000
