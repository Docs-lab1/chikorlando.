# 🍔 Tasty Bites - Fast Food Delivery App

A professional food delivery app inspired by Airtel, built with Supabase database.

## 🚀 Features

### Customer App
- 🍽️ Browse menu by categories
- 🛒 Add items to cart
- 📍 Location picker with map
- 💳 Multiple payment methods
- 📦 Real-time order tracking
- 🚴 Track delivery status

### Admin Panel
- ➕ Add/Edit menu items
- 📦 View all orders
- 🔄 Update order status
- 📊 Manage inventory

### Delivery Boy View
- 🚴 View ready orders
- 📍 See customer locations on map
- ✅ Update delivery status
- 🔄 Real-time updates

## 🛠️ Tech Stack

- HTML5 / CSS3 / JavaScript
- Supabase (PostgreSQL)
- Leaflet.js (Maps)
- Netlify (Hosting)

## 📁 Pages

| Page | URL | Purpose |
|------|-----|---------|
| Customer App | `/index.html` | Order food |
| Admin Panel | `/admin.html` | Manage menu & orders |
| Delivery View | `/delivery.html` | Manage deliveries |

## 🔧 Setup

1. Create Supabase project
2. Run SQL to create tables
3. Update Supabase credentials in all files
4. Deploy to Netlify

## 📊 Database Schema

### menu_items
- id, name, category, price, quantity, description, image_emoji, color, available, created_at

### orders
- id, customer_name, phone, items, total, address, latitude, longitude, delivery_notes, payment_method, status, created_at

## 🎨 Design

- Airtel-style red theme
- Glassmorphism effects
- Mobile-first responsive
- Smooth animations
- Professional icons

## 📦 Deployment

Deploy to Netlify by dragging the folder or connecting GitHub.

---

**Created for Mongu Trades Secondary School - ICT Department**