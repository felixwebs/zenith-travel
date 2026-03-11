# ✈️ Zenith Travels

A full-featured travel booking web application built as a single-page HTML file — inspired by platforms like MakeMyTrip. Zenith Travels allows users to search and browse flights, hotels, holiday packages, trains, buses, and cabs, complete with an admin dashboard and user authentication system.

---

## 🌟 Features

### 🔍 Search & Booking
- **Flights** — One-way, round-trip, and multi-city search with cabin class and passenger selection
- **Hotels** — Search by destination, dates, and number of guests
- **Holiday Packages** — Browse curated tour packages with pricing and itineraries
- **Trains** — Train search between origin and destination
- **Buses** — Inter-city bus booking search
- **Cabs** — Local and outstation cab booking

### 🏠 Home Page
- Hero search section with animated gradient background
- Scrollable offer cards with discount badges
- Coupon/promo code rail
- Holiday package grid
- Trending destinations gallery
- Featured hotels carousel
- "Why Zenith?" trust strip
- App download banner

### 👤 User Authentication
- Login and Sign Up modal with tab switching
- Demo accounts included for testing:
  - **Admin:** `admin@zenith.com` / `admin123`
  - **User:** `user@zenith.com` / `user123`
- Social login buttons (Google, Facebook)
- User avatar and dropdown menu in the header
- Protected routes (Account page requires login)

### 📋 Account Dashboard
- Profile management panel
- My Trips overview
- Saved/Wishlist items
- Wallet & rewards

### 🛠️ Admin Dashboard
- Accessible only to admin-role users
- Overview stats (bookings, revenue, users, packages)
- Tours management table with add/edit/delete
- Add New Tour form with name, destination, nights, price, and status
- Sidebar navigation between admin panels

### 🔔 UX Details
- Toast notification system for user feedback
- Sticky header with active navigation state
- Smooth page transitions (SPA-style routing)
- Swap button on flight origin/destination fields
- Fully responsive layout

---

## 🗂️ Project Structure

```
zenith-enhanced.html    # Entire application — HTML, CSS, and JS in one file
README.md
```

> This is a self-contained single-file application. No build tools, frameworks, or dependencies are required.

---

## 🚀 Getting Started

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/zenith-travels.git
   cd zenith-travels
   ```

2. Open the file in your browser:
   ```bash
   open zenith-enhanced.html
   # or on Windows:
   start zenith-enhanced.html
   ```

No server, npm install, or build step needed.

---

## 🔐 Demo Credentials

| Role  | Email                  | Password   |
|-------|------------------------|------------|
| Admin | admin@zenith.com       | admin123   |
| User  | user@zenith.com        | user123    |

> Note: Authentication is client-side only and for demonstration purposes. Do not use real credentials.

---

## 🎨 Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Markup     | HTML5                             |
| Styling    | CSS3 (custom properties, flexbox, grid) |
| Fonts      | Google Fonts — Poppins, Nunito Sans |
| Logic      | Vanilla JavaScript (ES6+)         |
| No build   | Zero dependencies, zero bundlers  |

---

## 📸 Pages & Navigation

| Page        | Description                              |
|-------------|------------------------------------------|
| Home        | Main landing with search and offers      |
| Flights     | Dedicated flight search UI               |
| Hotels      | Hotel search and listings                |
| Holidays    | Package tours and deals                  |
| Trains      | Train booking search                     |
| Buses       | Bus booking search                       |
| Cabs        | Cab booking search                       |
| Account     | User profile and trips (login required)  |
| Admin        | Admin dashboard (admin role required)    |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request
