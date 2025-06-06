# BillBuddy

**Smart Expense Management & Bill Splitting for Android**

BillBuddy is an Android application designed to simplify expense tracking, group bill splitting, and financial discussions. Built with Kotlin and Firebase, it offers a modern, intuitive interface for managing your finances collaboratively.

---

## Table of Contents

- [Core Features](#core-features)
- [Tech Stack](#tech-stack)
- [Project Highlights](#project-highlights)
---

## Core Features

*   **Secure User Authentication:** Easy sign-up/login with Email/Password.
*   **Expense Tracking:** Log, categorize (Food, Travel, etc.), and manage personal expenses with detailed views and history.
*   **Bill Splitting:**
    *   Split bills equally or assign custom amounts.
    *   Select multiple participants and track settled/unsettled amounts.
    *   View a clear history of all splits.
*   **Integrated Chat:** Communicate with other users directly within the app for expense-related discussions.
*   **Financial Reporting & Visualization:**
    *   Monthly expense summaries and category-wise analysis.
    *   Pie charts and progress bars for at-a-glance understanding of spending habits and budget status.
*   **Budget Management:** Set budgets for different categories and get alerts.
*   **Modern UI/UX:**
    *   Material Design 3 principles.
    *   Support for Light & Dark themes.
    *   Engaging Lottie animations.

---

## Tech Stack

*   **Language:** Kotlin
*   **Platform:** Android (Min SDK 24, Target SDK 34)
*   **Architecture:** MVVM (Model-View-ViewModel)
*   **Backend & Database:**
    *   Authentication (Email/Password)
    *   Firebase Realtime Database (User data, expenses, splits, chats, budgets)
    *   Firebase Cloud Storage (Profile pictures)
*   **UI & Graphics:**
    *   Android XML Layouts
    *   Material Design Components
    *   ViewBinding, RecyclerView, CardView
    *   Glide (Image Loading)
    *   Lottie (Animations)
*   **Local Cache:** SharedPreferences (for some user preferences and cached data)
*   **Chat/Communication:**
    *   Firebase Realtime Database
    *   Agora VideoUIKit & RTC SDK (for video call integration)
*   **Build Tool:** Gradle
*   **Other Key Libraries:** Gson

---

## Project Highlights

BillBuddy isn't just another expense tracker. Here's what sets it apart:

*   **Seamless Integration:** Combines individual expense tracking, group bill splitting, and direct user-to-user chat into one cohesive experience.
*   **Real-time Collaboration:** Firebase ensures that all data, from new expenses to chat messages and bill splits, is synchronized instantly across all participants' devices.
*   **User-Centric Design:** Thoughtful UI/UX with modern Material Design, engaging animations, and customizable themes make managing finances less of a chore.
*   **Comprehensive Financial Overview:** From detailed expense logs to visual charts and budget tracking, users get a clear picture of their financial health.
