# Auction Platform

A full-stack web-based auction system where users can register, bid on items, and manage auctions.  
It provides a seamless real-time bidding experience along with an admin dashboard for managing the platform.

---

## 🚀 Features

- 🔑 **User Authentication** (JWT-based login/signup)
- 📦 **Create & Manage Auctions** (add, edit, delete auction items)
- ⚡ **Real-time Bidding System**
- 🛠️ **Admin Dashboard** for monitoring users and auctions
- 📱 **Responsive UI** for all devices
- ☁️ **Cloudinary Integration** for image uploads and management

---

## 🛠️ Tech Stack

**Frontend**

- React.js
- HTML, CSS, JavaScript

**Backend**

- Node.js
- Express.js

**Database**

- MongoDB (Mongoose ORM)

**Others**

- Cloudinary (image hosting & optimization)
- JWT (authentication & authorization)
- Bcrypt (password encryption)

---

## ☁️ Cloudinary Integration

Auction items often need images. Instead of storing images locally, this platform integrates **Cloudinary**:

- Uploads auction images securely to the cloud
- Provides optimized URLs for faster delivery
- Supports automatic resizing and transformations

Each time a user adds an auction item, the image is uploaded to Cloudinary and stored with its reference in MongoDB.

---

## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/lokesh-1815/auction-platform.git
   ```
