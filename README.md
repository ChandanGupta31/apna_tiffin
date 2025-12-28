# 🍱 Apna Tiffin - Hyper-Local Tiffin Subscription Platform

**Apna Tiffin** is a flutter-based mobile application designed to digitize the unorganized Tiffin Service sector. It connects students and professionals with local home-cooked meal providers (Messes) through a flexible subscription model.

Unlike traditional food delivery apps that focus on on-demand ordering, Apna Tiffin optimizes for stability, predictability, and retention using a **Zero-Commission P2P Model**.

---

## 🚀 Key Features

### 👤 For Customers (Students/Professionals)
* **Flexible Subscriptions:** Choose from Trial (3 Days), Weekly, or Monthly plans.
* **Smart Pause & Skip:** Pause subscriptions or skip specific meals. Skipped meals are converted into **Store Credits** (Wallet Balance) automatically.
* **Cyclic Menus:** View daily changing menus (Mon-Sun, Lunch/Dinner).
* **Zero-Commission Payments:** Direct UPI payment to vendors. Users upload a screenshot/UTR for verification to 

### 👨‍🍳 For Mess Owners (Vendors)
* **Digital Ledger:** Replaces physical notebooks with a digital subscriber list.
* **Daily Dispatch System:** Automated 6:00 AM generation of "Today's Delivery List".
* **Payment Gateway:** Manual verification system to approve/reject user payments based on screenshots.
* **Menu Planner:** Set cyclic menus once; the system handles the rotation.

---

## 🛠️ Tech Stack & Architecture

The project follows a **Feature-First Architecture** to ensure scalability and maintainability.

* **Frontend:** Flutter (Dart)
* **State Management:** Riverpod 2.0 (Code Generation + Annotations)
* **Backend:** Firebase (Serverless)
    * **Authentication:** Phone OTP & Google Sign-In.
    * **Database:** Cloud Firestore (NoSQL).
    * **Storage:** Firebase Storage (Banner Images, Payment Proofs).
    * **Logic:** Cloud Functions (TypeScript/Python) for the Daily Scheduler.
* **Navigation:** GoRouter.
* **Maps:** Geolocator & GeoQueries for delivery radius checks.

---

## 👨‍💻 About the Developer

**Chandan Gupta**
*Lead Developer & Founder*

A **B.Tech (ECE) Graduate** with a unique blend of technical expertise, combining **6 months of experience in Satellite Communications** with **6 months of specialized Flutter Development**.

Building **Apna Tiffin** solo to solve the daily food struggle for students and professionals using modern, scalable tech.

* 📧 **Email:** chandankumarguptabgt@gmail.com
* 🔗 **LinkedIn:** https://www.linkedin.com/in/erchandangupta/
* 🐙 **GitHub:** https://github.com/ChandanGupta31

---

**© 2025 Apna Tiffin. All Rights Reserved.**