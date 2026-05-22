# 🐾 NAS Cat Sitter Website

A complete 2-page website for NAS Cat Sitter, Parit Raja.

## Files

| File | Description |
|------|-------------|
| `index.html` | Customer-facing website |
| `admin.html` | Admin dashboard (password protected) |

## How to Deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `nas-catsitter`)
2. Upload **both** `index.html` and `admin.html`
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your site will be live at: `https://yourusername.github.io/nas-catsitter`
5. Admin panel: `https://yourusername.github.io/nas-catsitter/admin.html`

## Admin Login

- **Username:** `admin`
- **Password:** `nas2026`

> ⚠️ Change the password after first login via Settings → Change Password

## Admin Features

- 📦 **Packages** — Add, edit, delete packages and prices
- ✅ **Services** — Manage all included services
- ➕ **Add-ons** — Manage optional add-on services
- 📅 **Bookings** — View all bookings, update status
- ⚙️ **Settings** — Edit business name, tagline, contact numbers, password
- 📤 Export / 📥 Import data as JSON

## How It Works

All data is stored in **browser localStorage**. Both `index.html` and `admin.html` share the same data store — any change in admin is reflected on the website immediately.

> 💡 For a production setup with a real database, consider connecting to Firebase Firestore (free tier).
