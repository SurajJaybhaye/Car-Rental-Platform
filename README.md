# 🚗 Car Rental Platform – Full-Stack Web Application  

### 🧾 Seamless Car Booking Experience for Users & Admins  

**Car Rental Platform** is a full-stack web application that enables users to explore, book, and manage car rentals with ease.  
It includes an intuitive admin dashboard for managing vehicles, bookings, and users — built with scalability, security, and performance in mind.  

🌐 **Live Demo:** [https://car-rental-platform-ruddy.vercel.app/](https://car-rental-platform-ruddy.vercel.app/)  

---

## 🧠 Features  

### 👤 User Dashboard  
- Browse available cars by type, price, or availability.  
- Book and manage car rentals securely.  
- View and cancel bookings directly from the dashboard.  

### 🧑‍💼 Admin Dashboard  
- Manage car listings (add, edit, or delete vehicles).  
- Track user activity and booking history.  
- Monitor platform analytics and performance.  

### 💳 Payment & Booking  
- Secure booking workflows.  
- Real-time status updates.  
- Optimized backend for concurrency and validation.  

### 📸 Image Management  
- Optimized image upload and storage for cars.  
- Cloud-based image hosting with efficient delivery.  

---

## 🧰 Tech Stack  

| Layer | Technology |
|--------|-------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ORM) |
| **Hosting** | Vercel (Frontend) & Render (Backend) |
| **Authentication** | JWT (JSON Web Tokens) |
| **Storage** | ImageKit |
| **State Management** | Context API / Redux Toolkit |

---

## ⚙️ Core Highlights  

- 🧩 **Full-Stack Architecture** — Separate frontend and backend, designed for scalability and easy deployment.  
- 🔐 **JWT Authentication** — Secure login, signup, and token-based session handling.  
- 📦 **ImageKit Integration** — Seamless car image upload and management.  
- 🧾 **Admin Controls** — Role-based access for managing cars, bookings, and users.  
- ⚡ **Optimized APIs** — RESTful endpoints with error handling, input validation, and fast response time.  
- 📱 **Responsive UI** — Built with Tailwind CSS for smooth cross-device experience.  

---

## 🛠️ Getting Started  

### 1️⃣ Clone the Repository  
```
git clone https://github.com/SurajJaybhaye/Car-Rental-Platform.git
cd Car-Rental-Platform
```

### 2️⃣ Server Setup

```
cd server
npm install
```

### Setup Environment Variables  Create a .env file in the server folder with:


```
MONGODB_URI=your_database_URL

JWT_SECRET=your_JWT_secret

IMAGEKIT_PUBLIC_KEY=your_imagekit_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_key
```

### Run the Server
```
npm run dev
```
### 3️⃣ Client Setup
```
cd ..
cd client
npm install
```
### Setup Environment Variables Create a .env file in the client folder with:

```
VITE_CURRENCY=$
VITE_BASE_URL=your_backend_url
```
### Run the Client

```
npm run dev
```


## 💡 Future Improvements
Integrate payment gateway (Stripe / Razorpay).

Add real-time notifications for booking updates.

Introduce user reviews and ratings.

Add analytics dashboard for admins.

Implement multi-language support and dark mode.

