# Matrix Events

> An Event Management app built for Chitkara University's **Matrix Club** — designed to streamline the process of creating, attending, and managing events for students and admins.

---

## 📋 Overview
**Matrix Events** is an Android app developed to help the Matrix Club organize and manage its events.  
Students can register, mark attendance, and stay updated with new events, while admins can create events, mark attendance, and download participant reports.

- ⚡️ **Access is restricted to Chitkara email addresses (@chitkara.edu.in)**
- ✅ You can access the app with following credentials (deepak7035.ca24@chitkara.edu.in , matrix_deepak)
- ✅ **Admin role granted only via database** for security

---

## 🚀 Features
- ✅ **Email & Password Authentication** for `@chitkara.edu.in` students
- 📧 **Email Verification** for new signups
- 👥 **User Registration & Profile Management** (Year of study, etc.)
- 🗓️ **Admin Capabilities**:
  - Create, Edit, and Delete Events
  - Mark Attendance (one-time only)
  - Export Event Participant Reports
- 💳 **Razorpay Integration** for paid events
- 🔔 **Push Notifications** (using FCM) for new events
- 💬 **Chat Feature** (Available for now — to be removed in future versions)
- 📷 **Event Gallery** (Remains available even if the associated event is deleted)
- ⚠️ **App Version Check** (Forces an app update screen if versions don’t match)

---

## 🛠️ Tech Stack
- **Framework**: Flutter
- **Database**: Firestore
- **Notifications**: FCM (Firebase Cloud Messaging)
- **Backend**: Express.js (Hosted on Render)
- **Routing**: `go_router`
- **State Management**: Basic state management (using `setState` and constructor data passing)

---

## 📱 Platform
- **Android only**

---

## 🐞 Additional Features
- 🌟 **Lottie Animations** for seamless user experience
- 📊 **Crashlytics** for error and crash reporting

---

## 📋 Roadmap
- ❌ Remove Chat Feature (Future Version)
- 🔥 Enhance Event Gallery Features
- ⏳ Potential public release on the Play Store (if selected)

---

## 🖊️ Created By
**Deepak Chawla**  
_Made with ❤️ for Chitkara University's Matrix Club._

---
