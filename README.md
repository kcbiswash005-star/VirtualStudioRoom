# VirtualStudioRoom

VirtualStudioRoom is a mobile app prototype developed for academic purposes.  
It helps users discover, book, and pay for creative studio services in one place.

## 📱 Project Overview

**Problem:**  
Customers often need multiple tools or manual communication to find studio services, compare prices, and complete bookings.

**Solution:**  
VirtualStudioRoom provides a simple, user-friendly flow to:
- Browse services
- Create bookings
- Simulate online payment
- Generate invoice/bill
- Submit customer feedback

## 🎯 Target Users
- Students
- Content creators
- Freelancers
- Small business owners

## 💡 Core Value Proposition
A single mobile app that reduces user effort, saves time, and simplifies studio booking transactions.

---

## ✅ Features

### Core
- Service listing with pricing and descriptions
- Booking form (name, date, time, duration)
- Payment simulation (Card / PayPal)
- Invoice generation and export
- Booking history

### Business Completeness
- ABN/ACN (temporary) display
- Contact Us page
- Maps link for location
- Social media links
- Marketing/promotional content
- Disclaimer statement

### Additional
- Customer feedback form
- Clean, intuitive UI with bottom navigation

---

## 🛠 Tech Stack
- **Language:** Kotlin
- **UI:** Jetpack Compose (Material 3)
- **Architecture:** MVVM
- **Navigation:** Navigation Compose
- **Database:** Room (local persistence)

---

## 📂 Suggested Project Structure

```text
com.virtualstudioroom
├── data/                # Entities, DAO, DB, Repository
├── vm/                  # ViewModels
├── ui/                  # Screens, navigation, app shell
├── util/                # Invoice exporter and helpers
└── MainActivity.kt
