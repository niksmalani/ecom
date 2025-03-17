# ecom

## 🚀 Overview
A **single-vendor e-commerce platform** built with:
- **Laravel & MySQL** (Backend & Database)
- **Razorpay** (Payment Gateway)
- **Shared Hosting** (Deployment)

## 📌 Features
- User Authentication
- Product Listing & Filtering
- Shopping Cart & Checkout
- Payment Integration

## 🛠️ Setup Guide
### 📂 Backend Setup (Laravel)
```bash
git clone https://github.com/your-repo-link.git
cd ecommerce-backend
composer install
cp .env.example .env
php artisan migrate --seed
php artisan serve
```

## 🔑 Environment Variables (.env)
```env
DB_DATABASE=ecommerce_db
DB_USERNAME=root
DB_PASSWORD=
RAZORPAY_KEY=your_razorpay_key
```

## 📡 API Endpoints
- **POST** `/api/login` - User Login
- **GET** `/api/products` - Fetch Products
- **POST** `/api/orders` - Create Order

## 🚀 Deployment
- Upload `public` folder to `public_html`
- Update `.env` with live credentials
- Run `php artisan migrate --seed`

## 🤝 Contributing
Pull Requests are welcome! 🚀
