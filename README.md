# 🧥 Virtual Try-On System — Admin Panel

This repository contains the **Admin Side** of the Virtual Try-On system, developed using **.NET MAUI**. It allows management of clothing items, categories, sessions, and user profiles which are then fetched by the **User Side** (Unity front-end) for the virtual try-on experience.

---

## 📁 Project Structure

- **MAUI.NET (Admin Panel):** Add/manage 3D clothing models, categories, and sessions
- **SQLite Database:** Stores all admin-side data
- **API (Web API / Local Server):** Used to serve 3D model metadata and file paths to the Unity front-end
- **Unity (User Side):** Displays the try-on interface using Kinect / camera input and overlays 3D clothes on users

---

## ✅ Admin Features

- Manage Categories (e.g., Casual, Formal, Ethnic)
- Manage Clothing Items (with 3D `.fbx` model upload)
- Manage Sessions, Students, and Sections
- Auto-generate recursive folders (`0000`, `0001`, ...) with `model.fbx` inside
- Stores models to:


---

## 🔗 User Side (Try-On Interface)

The actual virtual try-on experience is handled by Unity and can be accessed here:

> 🌍 [User Interface (Try-On System)](https://github.com/kausar-fatima/Virtual_Try_On_User)

-
