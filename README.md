# 🚜 Farmer-Vendor App

[![Maintainer](https://img.shields.io/badge/maintainer-RohanLobo15-blue)](mailto:rohanlobo15@example.com) ![Stars](https://img.shields.io/badge/stars-0-lightgrey) ![Issues](https://img.shields.io/badge/issues-0-green) ![Pull Requests](https://img.shields.io/badge/pull%20requests-0-green) ![License](https://img.shields.io/badge/license-MIT-blue) ![Last Commit](https://img.shields.io/badge/last%20commit-today-brightgreen)

---

## 📝 Overview

A modern, secure, and user-friendly React Native mobile application that connects farmers and vendors. The app provides seamless authentication, product management, and communication features to empower agricultural commerce.

---

## 🚀 Features

- 🔐 **Separate Authentication Flows** for Farmers & Vendors
- 🔥 **Firebase Authentication** integration
- 🔄 **Password Reset** with email verification
- 📱 **Modern & Responsive UI**
- 🛡️ **Secure User Data Management**
- 🛒 **Cart & Order Management** (for Farmers)
- 📦 **Product Management** (for Vendors)
- 💬 **Real-time Chat** between Farmers & Vendors
- 🌐 **Multi-language Support** (English, Hindi, Kannada)
- ⭐ **Ratings & Reviews**
- 📍 **Distance Calculation** for local commerce

---

## 🛠️ Setup Instructions

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Update Firebase Configuration:**
   Navigate to `src/config/firebase.ts` and add your Firebase configuration details:
   ```typescript
   const firebaseConfig = {
     apiKey: "your-api-key",
     authDomain: "your-auth-domain",
     projectId: "mine-805ba",
     storageBucket: "your-storage-bucket",
     messagingSenderId: "your-messaging-sender-id",
     appId: "your-app-id"
   };
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

4. **Run on your device:**
   - Scan the QR code with Expo Go (Android)
   - Or press 'i' for iOS simulator
   - Or press 'a' for Android emulator

---

## 📁 Project Structure

```
farmer-vendor-app/
├── src/
│   ├── config/
│   │   └── firebase.ts
│   ├── screens/
│   │   ├── common/
│   │   │   └── ForgotPassword.tsx
│   │   ├── farmer/
│   │   │   ├── Login.tsx
│   │   │   ├── Signup.tsx
│   │   │   ├── Cart.tsx
│   │   │   ├── Orders.tsx
│   │   │   ├── Home.tsx
│   │   │   ├── Profile.tsx
│   │   │   ├── Chat.tsx
│   │   │   ├── ChatList.tsx
│   │   │   ├── ProductDetails.tsx
│   │   │   ├── OrderSuccess.tsx
│   │   │   └── ForgotPassword.tsx
│   │   ├── vendor/
│   │   │   ├── Login.tsx
│   │   │   ├── Signup.tsx
│   │   │   ├── Dashboard.tsx
│   │   │   ├── AddProduct.tsx
│   │   │   ├── EditProduct.tsx
│   │   │   ├── MyProducts.tsx
│   │   │   ├── Products.tsx
│   │   │   ├── Orders.tsx
│   │   │   ├── Home.tsx
│   │   │   ├── Profile.tsx
│   │   │   ├── Chat.tsx
│   │   │   ├── ChatList.tsx
│   │   │   └── ForgotPassword.tsx
│   │   ├── admin/
│   │   │   └── InitializeDatabase.tsx
│   │   └── InitialSelection.tsx
│   ├── components/
│   ├── config/
│   ├── contexts/
│   ├── navigation/
│   ├── translations/
│   ├── types/
│   └── utils/
├── App.tsx
├── package.json
├── package-lock.json
└── README.md
```

---

## 🧰 Technology Stack

- ⚛️ **React Native**
- 🚀 **Expo**
- 🔥 **Firebase Authentication**
- 🧭 **React Navigation**
- 📝 **React Native Paper**
- 🌐 **TypeScript**

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#) or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.
