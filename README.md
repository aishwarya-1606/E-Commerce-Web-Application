# E-Commerce Web Application

A full-stack e-commerce web application developed for managing products, handling customer orders, and providing a seamless online shopping experience.

---

## Features

* Product catalog management
* Add to cart functionality
* Secure checkout system
* User authentication and authorization
* Role-based access control (Admin/User)
* Product and order management
* Responsive design for web and mobile
* REST API integration
* Dynamic product handling
* Order tracking system

---

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* React.js

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT Authentication
* bcrypt.js

### Deployment

* Vercel
* Render
* Netlify

---

## Project Structure

```bash id="t7xj5d"
ecommerce-web-app/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## Installation

### Clone Repository

```bash id="yv8h1x"
git clone <repository-link>
```

### Frontend Setup

```bash id="n0x8qq"
cd client
npm install
npm start
```

### Backend Setup

```bash id="g5t5d4"
cd server
npm install
node server.js
```

---

## Required Packages

```bash id="g4dx7q"
npm install express mongoose cors dotenv bcryptjs jsonwebtoken
npm install nodemon --save-dev
```

---

## Database Setup

Connect MongoDB using:

```javascript id="x3q15y"
mongoose.connect('YOUR_MONGODB_URL')
```

---

## API Endpoints

| Method | Endpoint           | Description    |
| ------ | ------------------ | -------------- |
| POST   | /api/auth/register | Register user  |
| POST   | /api/auth/login    | Login user     |
| GET    | /api/products      | Fetch products |
| POST   | /api/products      | Add product    |
| PUT    | /api/products/:id  | Update product |
| DELETE | /api/products/:id  | Delete product |
| POST   | /api/orders        | Create order   |
| GET    | /api/orders        | Fetch orders   |

---

## User Roles

### Admin

* Add products
* Update products
* Delete products
* Manage orders

### User

* Browse products
* Add items to cart
* Place orders
* Track orders

---

## Deployment

### Frontend

* Vercel
* Netlify

### Backend

* Render
* Railway

### Database

* MongoDB Atlas

---

## Expected Outcome

* Learn full-stack application development
* Understand authentication and authorization
* Gain experience with REST APIs
* Learn database integration
* Build real-world e-commerce features
* Handle dynamic product and order management
* Deploy scalable web applications

---

## Future Enhancements

* Online payment integration
* Wishlist feature
* Product reviews and ratings
* Search and filtering
* Order notifications
* Dark mode
* Admin analytics dashboard

---

## Author

Aishwarya
AIML Student | Full Stack Developer
