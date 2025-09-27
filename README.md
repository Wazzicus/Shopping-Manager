# Shopping Manager

![Platform](https://img.shields.io/badge/platform-Android%2013+-green)
![Status](https://img.shields.io/badge/status-Active-blue)

## TL;DR(Summary)
This is a clean and simple **Shopping List Manager** for households.  
✔️ Share lists with family(or anyone, really)
✔️ Works offline in read-only mode  
✔️ Smart suggestions & autocomplete  
✔️ Lists are auto-archived when complete for a clean UI
✔️ Mark items as high priority or add notes to them
✔️ Local lists stored on-device for personal use
✔️ Enjoy a beautiful Material 3 Expressive UI

👉 [Download APK](https://github.com/Wazzicus/Shopping-Manager/releases/latest)

---

## 📖 Description
Shopping Manager is a **household shopping list app** built with a focus on simplicity, collaboration, and great design.  
Unlike messy notes apps, it is designed specifically for collaborative shopping and so it provides **shared lists** with features like priorities, notes, suggestions and much more.  

Key highlights:
- ✨ **Household support** – create or join a household and share shopping lists with everyone in it.  
- 📌 **Item priority levels** – mark items as Normal or High.
- 📝 **Optional notes** – add context to your shopping items. 
- 🔑 **Sign In securely with Google** for quick and easy access.  
- 🔍 **Smart autocomplete** – remember past entries to help you add items quickly.  
- 🗂️ **Auto-archiving** – seperates old lists in the UI for a clean look
- 📋 **Create local lists** stored on-device for solo use. 
- 🎨 **Modern UI** – built with Material 3 & Jetpack Compose.  

This app is backed by a **Flask** backend, with additional support from **Firebase**.  
It’s designed as a learning + portfolio project but is fully usable in real life.


---

## ✨ Features
- 🏠 **Household lists** – create and share shopping lists with family members.  
- 📝 **Notes & priority levels** for items.  
- 📶 **Offline mode** – read-only access when offline.  
- 🌙 **Dark mode support**.  
- 🔍 **Contextual suggestions** when adding items to shared lists.  
- ✨ **Autocomplete** on item names (based on history).  
- 📋 **Support for personal, local lists** stored on-device.  
- 🗂  **Auto-archiving** of completed lists.  
- 🔑 **Google Sign-In** for quick and easy access.  
- 🎨 **Beautiful Material 3 UI** with touches of Material 3 Expressive elements.  
- 🔔 **Push notifications** (Work in Progress).  

---

## 📱 Screenshots

See the app in action:

<p align="center">
  <img src="assets/Onboarding_Screen.png" alt="Onboarding screen" width="250"/>
  <img src="assets/Household_Onboarding_Screen.png" alt="Household Onboarding screen" width="250"/>
  <img src="assets/Home_Screen.png" alt="Home screen" width="250"/>
  <img src="assets/Household_Screen.png" alt="Household Screen" width="250"/>
  <img src="assets/New_Item_Modal_Screen.png" alt="New Item Modal screen" width="250"/>
  <img src="assets/Shopping_List_Screen.png" alt="Shopping List screen" width="250"/>
  <img src="assets/Activity_History_Screen.png" alt="Activity History screen" width="250"/>
  <img src="assets/Settings_Screen.png" alt="Settings screen" width="250"/>
</p>

---

## 📥 Download
👉 Get the latest APK here:  
[**⬇️ Tap/Click here to download**](https://github.com/Wazzicus/Shopping-Manager/releases/latest)

---

## For the Nerds(My Stack):

**Frontend (Android)**  
- Kotlin, Jetpack Compose, Room, Retrofit, Hilt, Firebase  

**Backend**  
- Python (Flask), PostgreSQL, SQLAlchemy, Alembic  

**Other**  
- Firebase for messaging(push notifications) and authentication
- Redis for caching of idempotency keys used in concurrency control
- Backend hosted on [fly.io](https://fly.io)  

---

## Cons / Limitations  
- ❌ Requires internet for full functionality (offline mode is read-only).  
- ❌ Only Android is supported for now.  
- ❌ No price-tracking, items database or budgeting features as of now.
- ❌ Some features (e.g., conflict resolution on simultaneous edits, push notifications) are still being worked on.  

---

## 🚀 Roadmap
- [ ] Multi-platform support(iOS, Web) 
- [ ] Add home screen widgets
- [ ] Add conflict resolution for concurrent edits  
- [ ] Add barcode scanning for quick item entry  
- [ ] Create an item database
- [ ] Improve offline functionality (queue changes + sync)  
- [ ] Add budgeting features and price tracking.

---

## 📜 License
This project is currently **proprietary**.  
You may **view** and [**download the APK**](https://github.com/Wazzicus/Shopping-Manager/releases/latest), but the source code is not open for reuse or modification at this time.

---

## 👤 Author
Developed with ❤️ by [**Emmanuel Abelle (Wazzicus)**](https://github.com/Wazzicus)  
