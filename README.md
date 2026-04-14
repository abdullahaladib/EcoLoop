# 🌱 EcoLoop

> **Empowering Communities Through Sustainable Actions and Meaningful Donations**

A modern web-based platform designed to facilitate food donation, recycling, and waste reduction. EcoLoop connects conscious individuals and organizations to create a more sustainable community, ensuring efficient resource distribution while promoting environmental responsibility.

[![BRAC University](https://img.shields.io/badge/BRAC%20University-CSE470-green)](https://www.bracu.ac.bd)
[![MERN Stack](https://img.shields.io/badge/Tech-MERN%20Stack-blue)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()

---

## 🎯 About the Project

EcoLoop is a **BRAC University CSE470 Group Project** that aims to reduce waste and promote sustainable living by creating a seamless platform for:

- **Food Donation** - Share surplus food with those in need
- **Item Recycling** - Exchange clothes, books, and other items
- **Community Engagement** - Connect with eco-conscious individuals
- **Awareness** - Learn sustainable practices and eco-friendly tips

User registration is mandatory to ensure accountability, proper tracking, and a trusted community environment.

---

## ✨ Key Features

### 🔐 User Authentication

- **Sign Up** - Register with name, email, phone number, and secure password
- **Login** - Quick access with email and password
- Secure session management

### 🎁 Donation System

- **Item Donations** - Post items for donation with:
  - Title, location, type, date, image, and description
  - Filter donations by type
  - View all available donations

- **Food Donations** - Share food items with:
  - Title, location, food type, date, and description
  - Filter by location
  - Real-time availability

### 👥 Community Feed

- **Share & Organize** - Post updates and organize events
- **Engagement Features**:
  - Upvote posts to boost visibility
  - Comment for community interaction
  - User-tied posts for accountability
- **Sorted by Recency** - Always see the latest updates

### 👤 User Profile

- **Personal Dashboard** - View and manage your information:
  - Name, email, phone number
  - Recent donations and feed posts
  - Impact score tracking
- **Edit Profile** - Update personal details anytime
- **Activity History** - Track your contributions

### 📚 Awareness & Sustainability

- **Eco-Tips** - Actionable sustainability guidelines:
  - Reduce, Reuse, Recycle strategies
  - Water conservation tips
  - Energy conservation methods
- **Frequently Asked Questions** - Quick answers to common questions

---

## 🛠️ Tech Stack

| Layer           | Technologies                             |
| --------------- | ---------------------------------------- |
| **Frontend**    | Next.js, React, TypeScript, Tailwind CSS |
| **Backend**     | Node.js, Express.js                      |
| **Database**    | MongoDB                                  |
| **Build Tools** | npm, postcss                             |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/abdullahaladib/EcoLoop.git
   cd EcoLoop
   ```

2. **Install Frontend Dependencies**

   ```bash
   cd ecoloop_frontend
   npm install
   ```

3. **Install Backend Dependencies**

   ```bash
   cd ../ecoloop_backend
   npm install
   ```

4. **Start the Backend Server**

   ```bash
   cd ecoloop_backend
   npm run dev
   ```

5. **Start the Frontend Development Server**

   ```bash
   cd ecoloop_frontend
   npm run dev
   ```

6. **Access the Application**
   ```
   Open your browser and navigate to: http://localhost:3000
   ```

---

## 📁 Project Structure

```
EcoLoop/
├── ecoloop_frontend/          # Next.js React frontend
│   ├── app/
│   │   ├── (modules)/         # Feature modules
│   │   │   ├── admin/
│   │   │   ├── donation/
│   │   │   ├── food/
│   │   │   ├── feed/
│   │   │   ├── profile/
│   │   │   └── ...
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── package.json
│   └── tsconfig.json
│
└── ecoloop_backend/           # Node.js Express backend
    ├── src/
    │   ├── app/
    │   │   ├── admin/         # Admin management
    │   │   ├── auth/          # Authentication & authorization
    │   │   ├── donation/      # Donation features
    │   │   ├── food/          # Food donation
    │   │   ├── feed/          # Community feed
    │   │   ├── user/          # User management
    │   │   └── ...
    │   └── server.js
    └── package.json
```

---

## 🎨 UI Screenshots

The platform features a clean, intuitive interface with:

- **Authentication Pages** - Modern signup and login forms
- **Home Dashboard** - Welcome page with quick action buttons
- **Donation & Food Listing** - Browse and filter available items
- **Community Feed** - Engage with the community
- **User Profile** - Manage your account and track impacts
- **Sustainability Guidelines** - Learn eco-friendly practices

---

## 📖 Features in Detail

### 🌿 Reduce, Reuse, Recycle

- Buy reusable water bottles and bags
- Separate waste properly for recycling
- Repair instead of discarding old items

### 💧 Save Water

- Turn off taps while brushing
- Fix leaks promptly
- Collect rainwater for plants

### ⚡ Conserve Energy

- Switch to LED bulbs
- Unplug electronics when not in use
- Use natural light when possible

---

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add YourFeature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request

---

## 👨‍💻 Team

**BRAC University CSE470 Group Project**

Development and design by the team members at BRAC University.

---

## 💬 Support

For questions, suggestions, or issues:

- Open an issue on GitHub
- Contact the development team
- Check our FAQ section on the platform

---

## 🌍 Mission

**Making Sustainability Accessible to Everyone**

EcoLoop believes that small actions create big changes. By connecting our community and making donations easy, we're building a more sustainable future—one action at a time.

---

<div align="center">

**Ready to make a difference?** 🌱 Join EcoLoop today!

[Visit the Project](https://github.com/abdullahaladib/EcoLoop) • [Report Issues](https://github.com/abdullahaladib/EcoLoop/issues) • [View Demo](http://localhost:3000)

</div>
