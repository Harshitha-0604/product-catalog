# Product Catalog 🛒

A modern **MERN stack** application with a responsive UI, a scalable backend API, and a clean product catalog to manage and display products.

---

## 🚀 Features

✅ Build a robust RESTful API with Express  
✅ Connect to MongoDB with Mongoose  
✅ Responsive UI using React.js and Chakra UI  
✅ Error handling and validation  
✅ Ready for deployment  
✅ Easily extendable (e.g., shopping cart, payments, admin panel)

---

## ⚛️ Tech Stack

- **Frontend:** React.js, Chakra UI  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Other Tools:** Git, GitHub

---

## ⚙️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Harshitha-0604/product-catalog.git
cd product-catalog

### Install dependencies
Backend
bash
    
cd backend
npm install
Frontend
bash
    
cd ../frontend
npm install

### Setup environment variables
In the backend folder, create a .env file with:

plaintext
    
MONGO_URI=your_mongo_connection_string
PORT=5000

### Build the frontend
bash
    
cd frontend
npm run build

### Start the app
Backend:
bash
    
cd ../backend
npm start
Frontend:
(if you are running React separately for development)

    
cd ../frontend
npm start
Visit the app at http://localhost:3000.

```

📂 Project Structure

product-catalog/
  backend/
    server.js
    models/
    routes/
  frontend/
    src/
    public/
  .gitignore
  README.md
  package.json

🐞 Error Handling
Centralized error middleware

Validations for product data

404 handling for unknown routes

🌐 Deployment
This app can be deployed on:

Render / Railway / DigitalOcean for backend

Vercel / Netlify for frontend


---
