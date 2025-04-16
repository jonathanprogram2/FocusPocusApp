# 🌟 Focus Pocus – ADHD Productivity & Reminder App (Dev Branch)

**Focus Pocus** is a futuristic productivity assistant designed to support users with ADHD and executive function challenges. It combines intelligent nudges, calming visuals, and customizable routines to help users stay focused, organized, and in control of their day.

This is a **team project**, and I’m contributing as the **UI Designer** and **API Integration Specialist** — leading the design system, Android UI implementation, and front-end API connections.

---

## 🧠 Concept

Focus Pocus runs in the background and uses contextual nudges, smart reminders, and visual habit tracking to promote mindfulness and focus. The app is designed to be distraction-free, offline-capable, and highly personalized through daily streaks, insights, and calming animations.

---

## 👥 My Role in the Project

- 🎨 UI Designer – Created all mobile UI wireframes using **Figma**  
- 🧪 Frontend Developer – Implemented layouts and navigation using **Android Studio**  
- 🔌 API Integration Specialist – Connected UI to backend via **Retrofit**, **ViewModel**, and **SessionManager**

---

## 🔧 Tech Stack

- **Language:** `Kotlin`  
- **IDE:** `Android Studio`  
- **UI Design:** `XML Layouts`, `Material Design`, `Genos Font`  
- **Animations:** `Lottie`  
- **API Integration:** `Retrofit`, `ViewModel`, `SessionManager`, `Coroutines`  
- **Design & Prototyping:** `Figma`  
- **State Management:** `LiveData`, `MVVM`  
- **Backend (Planned):** Firebase / teammate-developed external APIs

---

## 📸 Screenshots

| UI Wireframes |

![Image](https://github.com/user-attachments/assets/e7eb8f3c-db37-4b0b-a59f-1d007c30da52)

| Splash Screen/Enter Screen |

![Image](https://github.com/user-attachments/assets/df99cbec-5e56-4b9a-9a11-9bd4c161eb64)

| Login Screen |

![Image](https://github.com/user-attachments/assets/8ef3ee01-ab07-4c17-b876-23ff037760b4)

| SignUp Screen |

![Image](https://github.com/user-attachments/assets/7e673fce-2156-4b18-a4e0-a987187ca947)

| Home Dashboard Screen |

![Image](https://github.com/user-attachments/assets/a7124949-b2a4-4faa-8512-1e401cd97d21)

| Nudges Screen |

![Image](https://github.com/user-attachments/assets/de9eb906-c4cd-4c68-8510-4be4e3d9d74d)

**Video link** 
(https://youtube.com/shorts/K4m3TYGVc-o)

---

## ✨ Features Completed So Far

- 🎨 **Custom Dashboard UI** (`activity_dashboard.xml`)  
   - Designed and implemented themed layout with purple backgrounds, glowing card containers, and custom icons

- 🧠 **Nudges Screen** (`NudgesActivity`)  
   - Built scrollable cards with motivational prompts and glowing buttons  
   - Integrated **Lottie animations** and applied custom styling  
   - Added dynamic **RecyclerView** rendering using `NudgeAdapter`  
   - Full API integration: Fetch, Add, Delete, Mark as Complete  
   - Architecture: `ViewModel + Repository` pattern used for clean state handling

- ✅ **Tasks Screen** (`TasksActivity`)  
   - Fully designed UI layout matching the app’s visual theme  
   - Includes task card design with `Confirm` and `Dismiss` buttons  
   - Implemented **RecyclerView** using `TaskAdapter`  
   - Full API integration: Fetch, Add, Delete, Mark as Complete  
   - Connected to backend via `ViewModel + Repository` pattern  
   - Includes functional `CalendarView`

- 🔁 **Shared Bottom Navigation Bar**  
   - Implemented reusable navigation component for consistent app-wide use  
   - Navigation wired for **Home**, **Nudges**, and **Tasks**

- 🔐 **Login & Signup System**  
   - Built secure authentication flow using `Retrofit`, `ViewModel`, `SessionManager`  
   - Includes form validation, API integration, error handling, and secure session state

- 🔐 **Authentication (Firebase)**  
   - FirebaseAuth integrated for logout functionality  
   - Logout button added to `DashboardActivity`, redirects to `SplashActivity`

- 🧭 **Dashboard Navigation Enhancements**  
   - `Tasks` and `Nudges` icons wired to open respective screens  
   - `Logout`, `Account`, `Preferences`, `Customize` buttons are functional

- 🛠️ **Bug Fixes & UI Flow Improvements**  
   - Resolved navigation and visibility issues  
   - Maintained consistent styling and behavior across all screens

---

## 🚧 In Progress

- 🔄 Firebase backend integration for persistent user data and smart reminders  
- 🧠 AI-powered features for dynamic nudges and productivity insights  
- 📊 Dashboard analytics with chart visualizations and time tracking

---

## 📚 What I'm Learning

- Architecting scalable Android apps with **MVVM + Repository patterns**  
- Building secure and efficient API flows using **Retrofit** and **Coroutines**  
- Designing responsive, animated interfaces with **Material Design**, **Lottie**, and custom themes  
- Collaborating effectively in a Git-based team using branches, pull requests, and shared issue tracking

---

## 📁 Project Status

🟢 **Actively developing** – this branch includes complete login/signup functionality, animated UI screens, and full user flow for early modules. Currently integrating Firebase and building advanced features.

---

## 🙋‍♂️ Let’s Connect

I’m always open to feedback, collaboration, or conversations around UI design, mobile development, and mental health tech.

📧 jonathan.a.mirabal@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/jonathanmirabal/)
