
# 🔐 Graphical Password Authentication System

A secure and user-friendly authentication system that replaces traditional text-based passwords with image-based login. This project allows users to set and verify passwords using images or specific click points, enhancing both usability and security.

---

## 📖 About

The **Graphical Password Authentication System** is built to offer a more intuitive and secure alternative to traditional password systems. Instead of remembering complex alphanumeric passwords, users authenticate by selecting a sequence of images or clicking specific points on a single image.

This approach makes it harder for attackers to guess or brute-force credentials and is especially useful for systems targeting non-technical users, children, or visually-oriented environments like schools, kiosks, or internal tools.

---

## 🚀 Features

- 🖼️ Image-based registration and login  
- 📌 Click-based or sequence-based password setup  
- ✅ Validation of user input on image interaction  
- 🔐 Improved resistance against brute-force and dictionary attacks  
- 💡 More memorable and user-friendly than traditional passwords  

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express (optional, if storing credentials server-side)  
- **Database**: MongoDB or LocalStorage (depending on implementation)  

---


---

## 📸 Screenshots

> _Add image-based screenshots showing registration and login interaction._

---

## 🧪 How It Works

1. **Registration**: User selects multiple points on an image (or image sequence).  
2. **Storage**: Coordinates or selected images are securely stored (hashed if server-side).  
3. **Login**: User clicks the same points or selects the same images in the correct order.  
4. **Validation**: System compares login pattern with stored one and grants access.  

---

## 📌 Use Cases

- Educational platforms  
- Internal tools for kids or visually-driven apps  
- Kiosk systems  
- Enhanced login security demos  

---

## ✅ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/graphical-password.git
cd graphical-password
```
 ### 2. Setup Backend

 ```bash
cd server
npm install
node app.js
```

