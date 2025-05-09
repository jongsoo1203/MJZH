# 📒 Gagebu — Household Ledger App

Gagebu is a simple and modern household ledger (가게부) app built with **Next.js** and **Firebase**. Users can sign up, input expenses manually or upload receipt images to automatically extract amounts using OCR.

---

## 🚀 Features

- 🔐 **User Authentication** (Firebase Auth)
- ✍️ **Manual Expense Entry** (amount, date, category, memo)
- 📷 **Receipt OCR Upload** (optional)
- ☁️ **Realtime Database** (Firebase Firestore)
- 🖼️ **Receipt Storage** (Firebase Storage)
- 📊 **Dashboard & Filtering** (monthly view, category filters - coming soon)

---

## 🛠 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/)
- **Backend**: [Firebase](https://firebase.google.com/)
  - Authentication
  - Firestore (NoSQL database)
  - Storage (for receipt images)
- **OCR** (optional): Google Cloud Vision API or Tesseract.js
- **Styling**: Tailwind CSS (recommended)

---

## 📁 Firebase Data Structure

