# HomeSerge Mobile

> Find your next home in Kenya — browse listings, save favorites, and connect with agents, all from your pocket.

HomeSerge is a cross-platform mobile experience built for the Kenyan real estate market. This repository hosts the customer and admin Android builds.

---

## 📲 Download

| App | APK | Purpose |
|-----|-----|---------|
| **HomeSerge** | [`homeserge.apk`](https://github.com/inferno254/homeserge-mobile/releases/download/v1.0.0/homeserge.apk) | For buyers, tenants, and property seekers |
| **HomeSerge Admin** | [`homeserge-admin.apk`](https://github.com/inferno254/homeserge-mobile/releases/download/v1.0.0/homeserge-admin.apk) | For agents, landlords, and admins |

Install the APK directly on any Android device (minimum SDK 21).

---

## ✨ Features

- 🏠 **Browse Listings** — Search homes, apartments, and commercial spaces with filters
- 🗺️ **Map View** — Explore properties geographically
- ⭐ **Saved Homes** — Bookmark listings and compare side by side
- 🔔 **Inquiries** — Chat or call agents directly from the app
- 📱 **Dark Mode** — Easy on the eyes, day or night
- 🌍 **Built for Kenya** — Local phone numbers, WhatsApp integration, and M-PESA-ready contact flows

### Admin Features
- 📋 **Property Management** — Create, edit, and publish listings with photos
- 📊 **Dashboard Analytics** — Track views, inquiries, and leads
- 👥 **User Management** — Manage agents, landlords, and permissions
- 📸 **Media Uploads** — Add image galleries for each property

---

## 🔐 Login

Both apps use **email and password** authentication via Supabase.

- **New users** can create an account from the sign-up screen inside the app
- **Password reset** is available through the "Forgot password" flow
- Admin accounts are pre-provisioned in Supabase with the `admin` or `publisher` role

---

## 🛠 Tech Stack

- **Flutter** — Single codebase, native Android performance
- **Supabase** — Auth, database, and storage
- **Riverpod** — State management
- **GoRouter** — Navigation and routing
- **Google Fonts & Material 3** — Clean, modern UI

---

## 📋 Requirements

- Android 5.0+ (API 21)
- ~55 MB storage per APK
- Internet connection for listing data and authentication

---

## 🚀 Building from Source

This repo ships compiled APKs. If you want to build from source, clone the full monorepo:

```bash
git clone https://github.com/inferno254/homeserge.git
cd homeserge/mobile   # customer app
flutter pub get && flutter build apk --release

cd ../admin          # admin app
flutter pub get && flutter build apk --release
```

---

## 📄 License

Proprietary — all rights reserved © HomeSerge

---

*Built with ❤️ in Kenya*
