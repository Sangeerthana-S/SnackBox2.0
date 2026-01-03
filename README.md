# 🍕 SnackBox: Customizable Snack Ordering and Delivery App

[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com/)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin-blue.svg)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-brightgreen.svg)](https://developer.android.com/jetpack/compose)

A lightweight and user-friendly Android application designed to streamline the food ordering and delivery process. Built with modern Android development practices using Kotlin and Jetpack Compose.

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)

## 🎯 About the Project

SnackBox is an Android-based food delivery application developed as part of the TNSDC Naan Mudhalvan Experience Based Project Learning (EBPL) initiative. The application features two primary interfaces to facilitate seamless communication between customers and food service providers.

**Project Documentation:** [View Full Report](https://drive.google.com/file/d/16VuFX7LUbx28VYrmqfz9Igu28pdQLkFn/view?usp=sharing)

### Admin Interface
- Secure login with unique credentials
- Menu management capabilities
- Order tracking and monitoring
- Delivery status oversight

### User Interface
- Intuitive food menu browsing
- Item selection with quantity specification
- Easy delivery address input
- Streamlined checkout process

## ✨ Features

- **Secure Authentication**: Admin access protected by username and password
- **Menu Management**: Administrators can add, update, and remove food items
- **Order Tracking**: Real-time order status monitoring for admins
- **User-Friendly Design**: Clean and intuitive interface built with Jetpack Compose
- **Local Database**: SQLite database with Room for efficient data storage
- **Responsive UI**: Material Design components for a modern look and feel

## 🛠️ Tech Stack

### Platform
- **OS**: Android (API Level 21+)
- **Language**: Kotlin
- **UI Framework**: Jetpack Compose

### Libraries & Dependencies
- **UI Components**:
  - `androidx.compose.ui:ui`
  - `androidx.compose.material:material`
  - `androidx.navigation:navigation-compose`

- **Database**:
  - SQLite with Room Database
  - `androidx.room:room-runtime`
  - `androidx.room:room-ktx`

## 📱 Screenshots

<table>
  <tr>
    <td><b>Registration Page</b></td>
    <td><b>Login Page</b></td>
    <td><b>Home Page</b></td>
  </tr>
  <tr>
    <td><b>Cart Page</b></td>
    <td><b>Order Success</b></td>
    <td><b>Admin Dashboard</b></td>
  </tr>
</table>

*Note: Screenshots available in the project documentation*

## 🚀 Getting Started

### Prerequisites
- Android Studio (Arctic Fox or later)
- JDK 11 or higher
- Android SDK (API Level 21+)
- Gradle 7.0+

### Installation

1. Clone the repository
```bash
git clone https://github.com/Sangeerthana-S/SnackBox2.0.git
```

2. Open the project in Android Studio

3. Sync Gradle files
```
File > Sync Project with Gradle Files
```

4. Run the application
```
Run > Run 'app'
```

### Admin Credentials
*Contact the development team for admin login credentials*

## 📂 Project Structure
```
SnackBox/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/SnackBox/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── AdminActivity.kt
│   │   │   │   ├── TargetActivity.kt
│   │   │   │   ├── OrderDatabaseHelper.kt
│   │   │   │   └── ui/theme/
│   │   │   ├── res/
│   │   │   │   ├── drawable/
│   │   │   │   ├── layout/
│   │   │   │   └── values/
│   │   │   └── AndroidManifest.xml
│   └── build.gradle
└── README.md
```

## 🔮 Future Enhancements

- **Real-Time GPS Tracking**: Live order tracking with estimated delivery time using Google Maps API
- **Payment Integration**: Support for multiple payment gateways (PayPal, Stripe, Razorpay, UPI)
- **Push Notifications**: Order status updates via Firebase Cloud Messaging (FCM)
- **Rating & Reviews**: Customer feedback system for menu items
- **Order History**: Complete purchase history for users
- **Advanced Analytics**: Dashboard insights for administrators
- **Multi-language Support**: Localization for broader accessibility

## 👥 Contributors

This project was developed by students from INFO Institute of Engineering, Coimbatore:

- **Aswin Raj** - 711022104009
- **Alphin V T** - 711022104005
- **Jithu Saaron B** - 711022104021
- **Ganesan A** - 711022104017
- **Sangeerthana S** - 711022104043

**Project Guide**: Mrs. A. Saranya M.E., Assistant Professor  
**Department**: Computer Science and Engineering  
**Institution**: INFO Institute of Engineering, Coimbatore - 641107

## 🙏 Acknowledgments

Special thanks to:
- **Tamil Nadu Skill Development Corporation (TNSDC)**
- **Naan Mudhalvan Platform**
- **Android Studio EBPL Program**
- **Dr. N. Kottiswaran** - Principal, INFO Institute of Engineering
- **Dr. G. Selvavinayagam** - Head of Department, CSE
- **Mrs. A. Saranya** - Staff Coordinator and Project Guide

## 📄 License

This project is an academic submission for INFO Institute of Engineering, Coimbatore.

## 📞 Contact

For queries or collaboration:
- GitHub: [@Sangeerthana-S](https://github.com/Sangeerthana-S)
- Project Link: [SnackBox2.0](https://github.com/Sangeerthana-S/SnackBox2.0)

---

<div align="center">
Made with ❤️ by Team SnackBox | INFO Institute of Engineering, Coimbatore
</div>
