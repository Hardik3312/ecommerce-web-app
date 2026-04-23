#  LuxeShop — E-Commerce Web App

A full-stack, production-ready e-commerce platform built with React + Vite (frontend) and Node.js + Express + MongoDB (backend). Features JWT auth, Stripe payments, Cloudinary image uploads, role-based access control, and a stunning modern UI.

---

## Tech Stack

| Layer      | Technology                                      |
|------------|-------------------------------------------------|
| Frontend   | React 18, Vite, Tailwind CSS, React Router v6   |
| Backend    | Node.js, Express 5, MongoDB + Mongoose          |
| Auth       | JWT (Access + Refresh tokens), bcrypt           |
| Payments   | Stripe                                          |
| Images     | Cloudinary                                      |
| State      | React Context API + useReducer                  |
| Styling    | Tailwind CSS v3, Custom CSS Variables           |

---

##  Project Structure

```
ecommerce-web-app/
├── frontend/        # React + Vite app
├── backend/         # Node.js + Express API
├── database/        # Schema and seed files
├── docs/            # API docs, ER diagrams
└── tests/           # Frontend & backend tests
```

---

##  Quick Start

### 1. Clone & Install

```bash
git clone https://github.com/yourname/ecommerce-web-app.git
cd ecommerce-web-app

# Install backend deps
cd backend && npm install

# Install frontend deps
cd ../frontend && npm install
```

### 2. Configure Environment

```bash
# Backend
cp backend/.env.example backend/.env
# Fill in: MONGO_URI, JWT_SECRET, STRIPE_SECRET_KEY, CLOUDINARY_* vars

# Frontend
cp frontend/.env.example frontend/.env
# Fill in: VITE_API_URL, VITE_STRIPE_PUBLIC_KEY
```

### 3. Seed Database

```bash
cd backend
npm run seed
```

### 4. Run Development Servers

```bash
# Terminal 1 — Backend (port 5000)
cd backend && npm run dev

# Terminal 2 — Frontend (port 5173)
cd frontend && npm run dev
```

---

##  Default Admin Credentials (after seeding)

```
Email:    admin@luxeshop.com
Password: Admin@1234
```

---

##  Features

- ✅ User registration & login (JWT)
- ✅ Product listing, search, filter, sort
- ✅ Product detail with image gallery
- ✅ Shopping cart with persistence
- ✅ Stripe checkout integration
- ✅ Order history & tracking
- ✅ User profile & dashboard
- ✅ Admin: manage products, orders, users
- ✅ Image upload via Cloudinary
- ✅ Responsive mobile-first UI
- ✅ Dark-mode luxe aesthetic

---

##  License

MIT
